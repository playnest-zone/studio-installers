<p align="center">
  <img src="assets/playnest-studio-logo.png" alt="PlayNest Studio logo" width="144">
</p>

<h1 align="center">PlayNest Studio</h1>

<p align="center">
  A desktop AI video production suite for turning scripts into narrated videos with generated visuals, synchronized subtitles, and a reusable production pipeline.
</p>

<p align="center">
  <a href="https://github.com/playnest-zone/studio-installers/releases/latest"><img src="https://img.shields.io/github/v/release/playnest-zone/studio-installers?display_name=tag&amp;sort=semver" alt="Latest release"></a>
  <a href="https://github.com/playnest-zone/studio-installers/releases"><img src="https://img.shields.io/github/downloads/playnest-zone/studio-installers/total" alt="Downloads"></a>
  <a href="#choose-an-installer"><img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-6b7280" alt="Platforms"></a>
</p>

## Download

### [Download the latest release](https://github.com/playnest-zone/studio-installers/releases/latest)

This repository contains official PlayNest Studio installers and release notes. It does not contain the application source code.

## Choose an installer

| Platform | Package | Recommended for |
| --- | --- | --- |
| Windows 10 or later (64-bit) | `.exe` | Most users and standard interactive installation |
| Windows 10 or later (64-bit) | `.msi` | Managed, silent, or enterprise deployment |
| macOS — Apple silicon | `.dmg` or `.pkg` marked `arm64` | Macs with Apple M-series processors |
| macOS — Intel | `.dmg` or `.pkg` marked `x64` | Intel-based Macs |

Only packages available on the latest release page are currently published.

## First-time setup

PlayNest Studio downloads and verifies its managed AI runtime and model files during initial setup. Keep the application open and maintain a stable internet connection until setup completes.

Large model downloads can take several minutes depending on network speed.

## Verify your download

Every release includes a `SHA256SUMS.txt` file. Verify the installer before opening it:

**Windows PowerShell**

```powershell
Get-FileHash .\PlayNest.Studio_*.exe -Algorithm SHA256
```

**macOS Terminal**

```bash
shasum -a 256 PlayNest-Studio-*
```

Compare the resulting hash with the matching entry in `SHA256SUMS.txt`.

## Operating-system security notices

Unsigned or newly published desktop applications may trigger Windows Smart App Control, Microsoft Defender SmartScreen, or macOS Gatekeeper warnings. Download PlayNest Studio only from this repository and verify the checksum before installation.

## Getting support

When reporting an installation or runtime problem, include:

- PlayNest Studio version
- Operating-system name and version
- Processor architecture (`x64`, Intel, or Apple silicon)
- Relevant application log lines
- A screenshot of the error, when available

Do not include access tokens, API keys, credentials, or other sensitive information in reports.

---

Copyright © PlayNest. All rights reserved.
