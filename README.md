# BubbleGum downloads

BubbleGum is the new name for Resonance: voice, chat and screen sharing for small friend groups, with a light powder-blue default appearance and customizable profiles.

## Download

[Download the latest Windows installer](https://github.com/ShayzeBeeb/resonance-releases/releases/latest)

Choose the `Resonance-Setup-<version>.exe` file. Windows 10/11, 64-bit. The compatibility filename keeps existing installations connected to updates.

The installer runs for your Windows account and keeps saved local app data. Older portable copies need this installer once to enable in-app updates.

## Updates

The app checks for updates on startup and periodically while open. Choose **Download** when notified, then **Restart to update** when ready. You can also check manually or turn automatic checks off under **Settings > Updates**. Update checks connect to GitHub; no chats or profile contents are sent.

BubbleGum uses public versions such as **0.1.1**. Installer filenames and GitHub tags retain a separate **1.10.x** compatibility sequence so existing Resonance installations can keep updating. The release title and installed app show the public BubbleGum version.

The `.yml`, `.blockmap`, `.json`, and `.sig` assets support in-app updating. You only need to run the `.exe` installer yourself.

## About this repository

This repository contains download information and public release files only. The private development checkout, user profiles, conversations and credentials are not published here. GitHub's automatically generated "Source code" archives contain only the download information in this repository.

As with Electron applications generally, the shipped client code is extractable from the installer. The app verifies update metadata and downloaded installers using its pinned signing key. This is separate from a Windows publisher certificate; the current installer does not have one, so Windows may display a security warning.
