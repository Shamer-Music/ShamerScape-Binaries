# ShamerScape — Official launcher downloads

Public **binary-only** distribution repository for the private two-player ShamerScape launcher.

**The launcher source is kept separately in a private repository.** Game-server source, character saves, server credentials, authentication tokens, and signing private keys do **not** belong here.

## Install

Open [Releases → latest](https://github.com/Shamer-Music/ShamerScape-Binaries/releases/latest) and download the installer for your computer:

- **Windows x64:** `shamerscape-<version>-windows-installer.exe`
- **Mac with Apple Silicon (M1/M2/M3/etc.):** `shamerscape-<version>-macos-arm64.dmg`
- **Intel Mac:** `shamerscape-<version>-macos-intel.dmg`

The other files in each release (`latest.json`, `*.app.tar.gz`, `*-windows-x86_64.exe`) are signed **update packages** that the launcher downloads by itself. You don't need to install them by hand.

Signed testing releases are published (v0.2.0 and v0.2.1 as of November 23, 2026). They are **early test builds**: private-server login on macOS has not been verified yet, and macOS builds are not Apple-notarized, so Gatekeeper may ask for confirmation the first time.

## Updates

An installed signed release checks the latest version before starting the game. Its updater accepts only packages with a valid signature from the trusted ShamerScape signing key.

The latest update index is:

https://github.com/Shamer-Music/ShamerScape-Binaries/releases/latest/download/latest.json

Release assets are public so Windows and Mac can download them without GitHub accounts. This does not grant anyone access to the private game world—game access still depends on the server and private network.

## Security

Only download from this repository or a trusted installer provided by the server owner. Never execute random copied update scripts or disclose the game's Tailscale network access credentials.
