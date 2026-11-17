# BubbleGum downloads

BubbleGum is a voice and community chat app. This repository contains public app downloads and the Mac packaging recipe. The private development project is not published here.

## Current release: 0.1.7

- [Download for Windows](https://github.com/ShayzeBeeb/resonance-releases/releases/download/v1.10.7/Resonance-Setup-1.10.7.exe)
- [Download for Apple silicon Mac](https://github.com/ShayzeBeeb/resonance-releases/releases/download/v1.10.7/BubbleGum-0.1.7-mac-arm64.dmg)
- [Mac installation notes](https://github.com/ShayzeBeeb/resonance-releases/releases/download/v1.10.7/BubbleGum-0.1.7-Mac-Readme.txt)
- [Release notes](https://github.com/ShayzeBeeb/resonance-releases/releases/tag/v1.10.7)

Choose an installer from the release assets. GitHub’s automatic “Source code” archives contain only this downloads page and the packaging recipe; they are not the app or its private development source. The compiled Electron app contains extractable client code.

## Windows

Open the installer to install BubbleGum for your Windows account. Existing installations can check for updates in Settings → Updates. The app displays version 0.1.7; the installer uses compatibility version 1.10.7 so older installations can update normally. Windows publisher signing is not configured, so Windows may show an unrecognized-app warning.

## Apple silicon Mac preview

Requires an Apple silicon Mac and macOS 13 Ventura or later. Open the DMG and drag BubbleGum to Applications. The app has an ad-hoc signature and is not Apple-notarized; macOS may require app-specific approval for the first launch. Follow the included installation notes and do not disable system-wide security protections.

The Mac download passed automated native launch checks on two Apple silicon runners. Physical microphones, cameras, wireless headsets, screen capture and real calls still need device testing. Mac updates are manual in this preview.
