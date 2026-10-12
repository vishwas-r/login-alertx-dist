# Login AlertX Distribution Repository

[![Latest Release](https://img.shields.io/badge/Release-v4.3.0-blue.svg)](https://github.com/vishwas-r/login-alertx-dist)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey.svg)](https://github.com/vishwas-r/login-alertx-dist)
[![Runtime](https://img.shields.io/badge/.NET-10.0-512BD4.svg)](https://dotnet.microsoft.com/)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](#license)

Official distribution repository for Login AlertX binaries, installers, and release packages across Windows and Linux platforms.

---

## Overview

Login AlertX is an endpoint security and session monitoring solution that delivers real-time notifications for authentication events, privilege elevation, and physical workstation access. Alerts are dispatched instantly across multiple enterprise and personal communication channels, including Email, Telegram, WhatsApp, Discord, Slack, Microsoft Teams, Google Chat, and generic Webhooks.

This repository serves as the official package distribution mirror for automated deployment pipelines, system administrators, and direct package downloads.

---

## Product Editions

### Desktop Edition
Designed for interactive workstations running Windows 10/11 and Linux desktop environments.
* Modern Fluent UI with dark and light themes
* Interactive system tray management and delivery health indicators
* Silent hardware media capture (webcam snapshot, WASAPI ambient audio recording, desktop screenshot)
* Hardware GPS and IP-based geolocation tracking
* Local SQLite outbox queue guaranteeing zero alert loss during network outages

### Server Edition
Optimized for headless servers, cloud infrastructure, and remote environments.
* Native daemon integration via Linux `systemd` and Windows Service subsystems
* Five-layer authentication audit parsing: SSH sessions, physical console logins, sudo elevations, screen locks/unlocks, and xRDP sessions
* Full command-line management utility (`loginalertx`) for configuration, alert testing, and event inspection
* Minimal footprint with zero desktop dependencies

---

## Latest Release: v4.3.0

Release Date: October 12, 2026

### Desktop Edition Packages

| Platform | Architecture | Package Format | Download Link | SHA-256 Checksum |
|---|---|---|---|---|
| Windows | x64 / ARM64 | Installer (`.exe`) | [Download](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.3.0/loginalertx-setup-v4.3.0.exe) | `73d99adf8e946163c66f934191d8883aa991fa7e51c40d8a25789de42dc4030b` |
| Linux | x64 | Debian / Ubuntu (`.deb`) | [Download](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.3.0/loginalertx-setup-v4.3.0.deb) | `103d8e277c2e3e5fe70148ccc97354a5aa99a35cfdda74be849a6f4c2bbd0631` |
| Linux | x64 | Portable Archive (`.tar.gz`) | [Download](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.3.0/loginalertx-setup-v4.3.0.tar.gz) | `bd243ac53f188aa76931e08e77fce1864a27ff2b7e6cc11cd2379df82326dc51` |

### Server Edition Packages

| Platform | Architecture | Package Format | Download Link | SHA-256 Checksum |
|---|---|---|---|---|
| Windows | x64 / ARM64 | Installer (`.exe`) | [Download](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.3.0/loginalertx-server-setup-v4.3.0.exe) | `e1733dc4918b1683c8d084554fcae34f073b17d2fd4b0b3c60fa7612b02ea2b2` |
| Linux | x64 | Debian / Ubuntu (`.deb`) | [Download](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.3.0/loginalertx-server-setup-v4.3.0.deb) | `3fe038b8ce573326c13a5d28acdfcebe488e182e4d7ee2bc36efdc92da91a740` |
| Linux | x64 | Portable Archive (`.tar.gz`) | [Download](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.3.0/loginalertx-server-setup-v4.3.0.tar.gz) | `0305e9125d9862a9262c589822841ea694c17bf65e0562fbf65389e26d3cfbe0` |

---

## Release Archive

| Version | Release Date | Desktop Packages | Server Packages | Release Focus |
|---|---|---|---|---|
| **v4.3.0** | 2026-10-12 | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.3.0/loginalertx-setup-v4.3.0.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.3.0/loginalertx-setup-v4.3.0.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.3.0/loginalertx-setup-v4.3.0.tar.gz) | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.3.0/loginalertx-server-setup-v4.3.0.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.3.0/loginalertx-server-setup-v4.3.0.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.3.0/loginalertx-server-setup-v4.3.0.tar.gz) | Generic Webhook alerts, delivery health monitoring, modernized settings UI, 30-day trial |
| **v4.2.0** | 2026-09-29 | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.2.0/loginalertx-setup-v4.2.0.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.2.0/loginalertx-setup-v4.2.0.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.2.0/loginalertx-setup-v4.2.0.tar.gz) | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.2.0/loginalertx-server-setup-v4.2.0.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.2.0/loginalertx-server-setup-v4.2.0.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.2.0/loginalertx-server-setup-v4.2.0.tar.gz) | Storage Management UI, custom retention policies, Microsoft Store license synchronization |
| **v4.1.0** | 2026-09-20 | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.1.0/loginalertx-setup-v4.1.0.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.1.0/loginalertx-setup-v4.1.0.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.1.0/loginalertx-setup-v4.1.0.tar.gz) | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.1.0/loginalertx-server-setup-v4.1.0.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.1.0/loginalertx-server-setup-v4.1.0.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.1.0/loginalertx-server-setup-v4.1.0.tar.gz) | Multi-channel media attachments, Slack dual-mode webhook/bot, machine-learning anomaly scoring |
| **v4.0.0** | 2026-09-04 | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.0.0/loginalertx-setup-v4.0.0.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.0.0/loginalertx-setup-v4.0.0.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.0.0/loginalertx-setup-v4.0.0.tar.gz) | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.0.0/loginalertx-server-setup-v4.0.0.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.0.0/loginalertx-server-setup-v4.0.0.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.0.0/loginalertx-server-setup-v4.0.0.tar.gz) | Stable cross-platform launch, re-engineered silent media engine, WASAPI audio recording |
| **v4.0.0-beta-2** | 2026-08-29 | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.0.0-beta-2/loginalertx-setup-v4.0.0-beta-2.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.0.0-beta-2/loginalertx-setup-v4.0.0-beta-2.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.0.0-beta-2/loginalertx-setup-v4.0.0-beta-2.tar.gz) | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.0.0-beta-2/loginalertx-server-setup-v4.0.0-beta-2.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.0.0-beta-2/loginalertx-server-setup-v4.0.0-deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.0.0-beta-2/loginalertx-server-setup-v4.0.0-beta-2.tar.gz) | Unified license management, improved wizard validation, Microsoft Store WhatsApp fix |
| **v4.0.0-beta-1** | 2026-08-25 | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.0.0-beta-1/loginalertx-setup-v4.0.0-beta-1.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.0.0-beta-1/loginalertx-setup-v4.0.0-beta-1.deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/desktop/v4.0.0-beta-1/loginalertx-setup-v4.0.0-beta-1.tar.gz) | [EXE](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.0.0-beta-1/loginalertx-server-setup-v4.0.0-beta-1.exe) \| [DEB](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.0.0-beta-1/loginalertx-server-setup-v4.0.0-deb) \| [TAR](https://media.githubusercontent.com/media/vishwas-r/login-alertx-dist/main/server/v4.0.0-beta-1/loginalertx-server-setup-v4.0.0-beta-1.tar.gz) | Initial v4 preview, CLI management tool, native Linux daemon, Fluent UI redesign |

---

## Installation Instructions

### Windows

Run the executable installer with administrative privileges:

```cmd
loginalertx-setup-v4.3.0.exe
```

For silent enterprise deployments:

```cmd
loginalertx-setup-v4.3.0.exe /VERYSILENT /NORESTART
```

### Linux (Debian / Ubuntu)

Install using the Debian package manager:

```bash
sudo dpkg -i loginalertx-setup-v4.3.0.deb
sudo apt-get install -f
```

For server installations, verify that the systemd service is active:

```bash
sudo systemctl status loginalertx
```

### Linux (Portable Archive)

Extract the `.tar.gz` package to the desired destination:

```bash
sudo tar -xzf loginalertx-setup-v4.3.0.tar.gz -C /opt/loginalertx
cd /opt/loginalertx
sudo ./install.sh
```

---

## Verification

To verify the integrity of downloaded binaries, compare the computed SHA-256 checksum against the values published above.

### Windows (PowerShell)

```powershell
Get-FileHash -Algorithm SHA256 .\loginalertx-setup-v4.3.0.exe
```

### Linux / macOS

```bash
sha256sum loginalertx-setup-v4.3.0.deb
```

---

## System Requirements

### Windows
* Windows 10 (version 1809 or higher), Windows 11
* Windows Server 2019, 2022, 2025
* 64-bit architecture (x64 / ARM64)
* Microsoft .NET Runtime 10.0 (included in installer)

### Linux
* Ubuntu 20.04 LTS or newer
* Debian 11 or newer
* Red Hat Enterprise Linux / Rocky Linux / AlmaLinux 8 or newer
* glibc 2.28 or newer
* systemd (for background service operation)

---

## Support and Documentation

* Official Website: [https://loginalertx.com](https://loginalertx.com)
* Documentation: [https://loginalertx.com/docs/](https://loginalertx.com/docs/)
* Release Notes: [https://loginalertx.com/changelog/](https://loginalertx.com/changelog/)
* Issue Tracker: [https://github.com/vishwas-r/login-alertx-dist/issues](https://github.com/vishwas-r/login-alertx-dist/issues)

---

## License

Copyright (c) Login AlertX. All rights reserved. Distributed under proprietary commercial licensing terms. Refer to the end-user license agreement included with each installer package.
