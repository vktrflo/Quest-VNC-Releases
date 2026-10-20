# Quest VNC PC setup

One-step setups that get a PC ready for the Quest VNC headset app: a VNC server plus the sound sender.
Each one asks which port to use for the VNC server and for sound, and for a password, then prints what
to enter in the app.

## Current version: 0.1.2

Downloads for 0.1.2 are hosted as release assets (the per-user Windows zip is too large for GitHub's
repository-file limit).

- **Windows:** [QuestVncSetup-0.1.2-windows.zip](https://github.com/vktrflo/Quest-VNC-Releases/releases/download/v0.1.2/QuestVncSetup-0.1.2-windows.zip). Installs TightVNC Server and the sound sender. Unzip, then double-click `Install Quest VNC.cmd`.
- **Windows (per-user, no admin):** [QuestVncSetup-0.1.2-windows-user.zip](https://github.com/vktrflo/Quest-VNC-Releases/releases/download/v0.1.2/QuestVncSetup-0.1.2-windows-user.zip). Installs both QuestVncServer and the sound sender **for your account only** — no `Program Files`, no Windows service, no admin. Choose either the GUI wizard (`QuestVncUserSetup.exe`) or the command-line wrapper (`Install Quest VNC (Per User).cmd`). Coexists with the legacy install.
- **Linux:** [QuestVncSetup-0.1.2-linux.zip](https://github.com/vktrflo/Quest-VNC-Releases/releases/download/v0.1.2/QuestVncSetup-0.1.2-linux.zip). Sets up a TigerVNC virtual desktop and the sound sender. Unzip and run `./install.sh`.
- **macOS:** [QuestVncSetup-0.1.2-macos.zip](https://github.com/vktrflo/Quest-VNC-Releases/releases/download/v0.1.2/QuestVncSetup-0.1.2-macos.zip). Turns on Screen Sharing (with guidance) and installs the sound sender. Unzip, then right-click `Install Quest VNC.command` and choose Open.

Each zip has a README with details and uninstall steps.

## Previous: 0.1.1

`setup-v0.1.1/` holds the previous release. The only difference is the per-user Windows zip: 0.1.2 adds the
`QuestVncUserSetup.exe` GUI wizard and keeps the command-line wrapper.

- **Windows:** [QuestVncSetup-0.1.1-windows.zip](setup-v0.1.1/QuestVncSetup-0.1.1-windows.zip).
- **Windows (per-user, no admin):** [QuestVncSetup-0.1.1-windows-user.zip](setup-v0.1.1/QuestVncSetup-0.1.1-windows-user.zip).
- **Linux:** [QuestVncSetup-0.1.1-linux.zip](setup-v0.1.1/QuestVncSetup-0.1.1-linux.zip).
- **macOS:** [QuestVncSetup-0.1.1-macos.zip](setup-v0.1.1/QuestVncSetup-0.1.1-macos.zip).

## Older: Quest VNC Server (shelved)

`v0.3.0/` and `latest.json` hold the last release of our own VNC server, which the setups above replace.
