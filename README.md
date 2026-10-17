# Quest VNC PC setup

One-step setups that get a PC ready for the Quest VNC headset app: a VNC server plus the sound sender.
Each one asks which port to use for the VNC server and for sound, and for a password, then prints what
to enter in the app.

## Current version: 0.1.1

- **Windows:** [QuestVncSetup-0.1.1-windows.zip](setup-v0.1.1/QuestVncSetup-0.1.1-windows.zip). Installs TightVNC Server and the sound sender. Unzip, then double-click `Install Quest VNC.cmd`.
- **Linux:** [QuestVncSetup-0.1.1-linux.zip](setup-v0.1.1/QuestVncSetup-0.1.1-linux.zip). Sets up a TigerVNC virtual desktop and the sound sender. Unzip and run `./install.sh`.
- **macOS:** [QuestVncSetup-0.1.1-macos.zip](setup-v0.1.1/QuestVncSetup-0.1.1-macos.zip). Turns on Screen Sharing (with guidance) and installs the sound sender. Unzip, then right-click `Install Quest VNC.command` and choose Open.

On each file's page, use the download button. Each zip has a README with details and uninstall steps.

## Older: Quest VNC Server (shelved)

`v0.3.0/` and `latest.json` hold the last release of our own VNC server, which the setups above replace.
