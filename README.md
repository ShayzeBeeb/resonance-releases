# Resonance downloads

Resonance is a Windows voice and community chat app with lime green accents, customizable profiles, screen sharing, and local conversation storage.

## Download

[Download the latest Windows installer](https://github.com/ShayzeBeeb/resonance-releases/releases/latest)

Choose the `Resonance-Setup-<version>.exe` file. Windows 10/11, 64-bit.

Close an older copy of Resonance before installing. The installer runs for your Windows account and keeps saved local app data. Older portable copies need this installer once to enable in-app updates.

## Updates

Resonance checks for updates on startup and periodically while open. Choose **Download** when notified, then **Restart to update** when ready. You can also check manually or turn automatic checks off under **Settings > Updates**. Update checks connect to GitHub; no chats or profile contents are sent.

The `.yml`, `.blockmap`, `.json`, and `.sig` assets support in-app updating. You only need to run the `.exe` installer yourself.

## About this repository

This repository contains download information and public release files only. The development source repository is not published here. GitHub's automatically generated “Source code” archives contain only the download information in this repository.

The Electron application includes its executable client code. Release signatures check update authenticity within Resonance; this is separate from a Windows publisher certificate. The current installer is unsigned for Windows, so Windows may display a security warning.
