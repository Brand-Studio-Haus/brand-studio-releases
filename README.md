# Brand Studio — downloads

Installers for Brand Studio. The app's code lives in a private repo; this repo only hosts releases,
and the app checks here for updates (Update button, bottom of the side menu).

## Install

**Windows** — download `Brand-Studio-Setup-<version>.exe` from [Releases](../../releases/latest) and run it.
Windows may show "Windows protected your PC" until the installer is code-signed: click **More info → Run anyway**.

**Mac (Apple silicon)** — download `Brand-Studio-<version>-arm64.dmg`, open it and drag Brand Studio to Applications.
Until the app is notarized, open it the first time with **right-click → Open**.

**Linux (x64)** — download either package from [Releases](../../releases/latest):
- **Debian / Ubuntu (`.deb`):** `Brand-Studio-<version>-amd64.deb` — install with `sudo apt install ./Brand-Studio-<version>-amd64.deb`.
- **AppImage (`.AppImage`):** `Brand-Studio-<version>-x86_64.AppImage` — make executable (`chmod +x Brand-Studio-<version>-x86_64.AppImage`) and run.

## First run

Brand Studio checks your computer and suggests the free local engines it can use for AI copy and images.
Brands, briefs, moodboards, guidelines and PDF import work without them, so you can skip this and set it up later
(gear icon in the menu).

Your projects are saved in `Documents/Brand Studio`. Updates never touch that folder.
