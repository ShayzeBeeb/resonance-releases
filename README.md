# BubbleGum downloads

BubbleGum is the new name for Resonance: voice, chat and screen sharing for small friend groups, with a light powder-blue appearance and customizable profiles.

## Downloads

- **Windows 10/11, 64-bit — 0.1.6:** [Download the Windows installer](https://github.com/ShayzeBeeb/resonance-releases/releases/download/v1.10.6/Resonance-Setup-1.10.6.exe).
- **Apple silicon Mac, macOS 13 Ventura or later — 0.1.3:** [Download the Mac preview](https://github.com/ShayzeBeeb/resonance-releases/releases/download/v1.10.3/BubbleGum-0.1.3-mac-arm64.dmg).
- [Windows release notes and checksums](https://github.com/ShayzeBeeb/resonance-releases/releases/tag/v1.10.6).

Version 0.1.6 adds candy-inspired buttons and menus, rounded typography, and a choice of Baloo 2, Fredoka, or DynaPuff in Appearance. Fonts are included locally and work offline. It includes General UI fixes. Audio processing is unchanged from 0.1.3.

The Windows installer runs for your Windows account and keeps saved local app data. Older portable copies need the installer once to enable in-app updates. Its compatibility filename keeps existing installations connected to updates.

On Mac, open the DMG and drag BubbleGum to Applications. This preview is not Apple-notarized and does not have an Apple Developer ID signature. macOS may block the first launch. If you trust this download, follow Apple's app-specific [Open Anyway instructions](https://support.apple.com/en-us/102445). The Mac preview passed automated launch checks on separate Apple silicon build machines; microphones, cameras, screen sharing and real calls still need testing on your own Mac.

## Updates

**Windows:** the app checks for updates on startup and periodically while open. Choose **Download** when notified, then **Restart to update** when ready. You can check manually or turn automatic checks off under **Settings > Updates**. Update checks connect to GitHub; no chats or profile contents are sent.

**Mac preview:** install later Mac downloads manually. In-app updates are not enabled on Mac yet.

BubbleGum uses public versions such as **0.1.6**. Windows installer filenames and GitHub tags retain a separate **1.10.x** compatibility sequence so existing Resonance installations can keep updating. The release title and installed app show the public BubbleGum version.

The `.yml`, `.blockmap`, `.json`, and `.sig` assets support Windows in-app updating. The Mac `.sha256` file is a download checksum. To install, use the `.exe` on Windows or the `.dmg` on Mac.

## About this repository

This repository contains download information and a packaging workflow. Public release assets contain the app downloads, update files and installation notes. The private development checkout, user profiles, conversations and credentials stay out of this repository. GitHub's automatically generated "Source code" archives contain these download documents and packaging instructions only.

As with Electron applications generally, the shipped client code is extractable from the app. Windows verifies update metadata and downloaded installers using a pinned signing key. This is separate from a Windows publisher certificate; the current Windows installer does not have one, so Windows may display a security warning.

