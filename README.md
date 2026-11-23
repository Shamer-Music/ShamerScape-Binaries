# ShamerScape — Official launcher downloads

Public **binary-only** distribution repository for the private two-player ShamerScape launcher.

**The launcher source is kept separately in a private repository.** Game-server source, character saves, server credentials, authentication tokens, and signing private keys do **not** belong here.

## Install

When the first tested, signed release is published, open [Releases](https://github.com/Shamer-Music/ShamerScape-Binaries/releases/latest) and choose the installer for your computer:

- **Windows x64:** `shamerscape-<version>-windows-installer.exe`
- **Mac with Apple Silicon (M1/M2/M3/etc.):** `shamerscape-<version>-macos-arm64.dmg`
- **Intel Mac:** `shamerscape-<version>-macos-intel.dmg`

These installers have not been published yet. Do **not** distribute a development preview as the finished player release.

## Updates

Once signed releases are activated, the launcher checks the latest version before starting the game. Its updater accepts only packages with a valid signature from the trusted ShamerScape signing key.

The latest update index will live at:

https://github.com/Shamer-Music/ShamerScape-Binaries/releases/latest/download/latest.json

Release assets are public so Windows and Mac can download them without GitHub accounts. This does not grant anyone access to the private game world—game access still depends on the server and private network.

## Security

Only download from this repository or a trusted installer provided by the server owner. Never execute random copied update scripts or disclose the game's Tailscale network access credentials.
