# Quest VNC Server releases

Downloads for Quest VNC Server, the VNC server with sound for the Quest VNC headset app.

## Current version: 0.3.0

- **Windows:** [QuestVncServer-0.3.0-windows.zip](v0.3.0/QuestVncServer-0.3.0-windows.zip). Unzip, double-click `QuestVncServer.exe`, and answer yes to install.
- **Linux (X11):** [QuestVncServer-0.3.0-linux.zip](v0.3.0/QuestVncServer-0.3.0-linux.zip). Unzip and run `./install.sh`.
- **macOS:** [QuestVncServer-0.3.0-macos.zip](v0.3.0/QuestVncServer-0.3.0-macos.zip). Unzip, then right-click `install.command` and choose Open.

On each file's page, use the download button.

Installed servers update themselves from this repository: they read `latest.json` and download the
bare `.exe`, Linux binary or macOS `.tar.gz` it points to, after checking its size and checksum.
