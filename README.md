# Login AlertX Distribution Repository

[![Latest Release](https://img.shields.io/badge/Release-v4.4.0-blue.svg)](https://github.com/vishwas-r/login-alertx-dist)
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

## Latest Release: v4.4.0

Release Date: October 31, 2026

### Desktop Edition Packages

| Platform | Architecture | Package Format | Download Link | SHA-256 Checksum |
|---|---|---|---|---|
| Windows | x64 / ARM64 | Installer (`.exe`) | [Download](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-setup-v4.4.0.exe) | `6945163dd66ab4096ef08eff71cdabc5677b28b108965692bf272e4121daf89a` |
| Linux | x64 | Debian / Ubuntu (`.deb`) | [Download](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-setup-v4.4.0.deb) | `eb644f129d202ed43c2af3ade813e82b51b400d6d58452bd8a0df97846c27d64` |
| Linux | x64 | Portable Archive (`.tar.gz`) | [Download](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-setup-v4.4.0.tar.gz) | `65819aec89896d57e7f7c89fd64c44c5b7e0e011185d50baa07c530935bd9622` |

### Server Edition Packages

| Platform | Architecture | Package Format | Download Link | SHA-256 Checksum |
|---|---|---|---|---|
| Windows | x64 / ARM64 | Installer (`.exe`) | [Download](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-server-setup-v4.4.0.exe) | `c3bff2cd90e35f5fc9bee89c9a57a7d5c64a77008109cbfa1ba4b8c975bc9cd8` |
| Linux | x64 | Debian / Ubuntu (`.deb`) | [Download](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-server-setup-v4.4.0.deb) | `c50448c5bd7ca5b3c6f5fc111dabe551ab631a415e49333b02b75db6064168b9` |
| Linux | x64 | Portable Archive (`.tar.gz`) | [Download](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-server-setup-v4.4.0.tar.gz) | `2962e321b43b0b79961b5c44017d7c75144aae253af719d17e7780895b7a1d0d` |

---

## Release Archive

| Version | Release Date | Desktop Packages | Server Packages | Release Focus |
|---|---|---|---|---|
| **v4.4.0** | 2026-10-31 | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-setup-v4.4.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-setup-v4.4.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-setup-v4.4.0.tar.gz) | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-server-setup-v4.4.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-server-setup-v4.4.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.4.0/loginalertx-server-setup-v4.4.0.tar.gz) | Telegram native integration, WhatsApp Computer Name alerts, HMAC-signed payloads, public IP fix, smart duplicate suppression, security patch (Pkcs CVE) |
| **v4.3.1** | 2026-10-23 | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.1/loginalertx-setup-v4.4.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.1/loginalertx-setup-v4.4.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.1/loginalertx-setup-v4.4.0.tar.gz) | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.1/loginalertx-server-setup-v4.3.1.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.1/loginalertx-server-setup-v4.3.1.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.1/loginalertx-server-setup-v4.3.1.tar.gz) | Multi-recipient email alerts, automated audit policy verification, delivery health diagnostics, Windows failed login fix, and Linux CLI startup fix |
| **v4.3.0** | 2026-10-12 | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.0/loginalertx-setup-v4.3.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.0/loginalertx-setup-v4.3.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.0/loginalertx-setup-v4.3.0.tar.gz) | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.0/loginalertx-server-setup-v4.3.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.0/loginalertx-server-setup-v4.3.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.3.0/loginalertx-server-setup-v4.3.0.tar.gz) | Generic Webhook alerts, delivery health monitoring, modernized settings UI, 30-day trial |
| **v4.2.0** | 2026-09-29 | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.2.0/loginalertx-setup-v4.2.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.2.0/loginalertx-setup-v4.2.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.2.0/loginalertx-setup-v4.2.0.tar.gz) | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.2.0/loginalertx-server-setup-v4.2.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.2.0/loginalertx-server-setup-v4.2.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.2.0/loginalertx-server-setup-v4.2.0.tar.gz) | Storage Management UI, custom retention policies, Microsoft Store license synchronization |
| **v4.1.0** | 2026-09-20 | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.1.0/loginalertx-setup-v4.1.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.1.0/loginalertx-setup-v4.1.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.1.0/loginalertx-setup-v4.1.0.tar.gz) | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.1.0/loginalertx-server-setup-v4.1.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.1.0/loginalertx-server-setup-v4.1.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.1.0/loginalertx-server-setup-v4.1.0.tar.gz) | Multi-channel media attachments, Slack dual-mode webhook/bot, machine-learning anomaly scoring |
| **v4.0.0** | 2026-09-04 | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0/loginalertx-setup-v4.0.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0/loginalertx-setup-v4.0.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0/loginalertx-setup-v4.0.0.tar.gz) | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0/loginalertx-server-setup-v4.0.0.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0/loginalertx-server-setup-v4.0.0.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0/loginalertx-server-setup-v4.0.0.tar.gz) | Stable cross-platform launch, re-engineered silent media engine, WASAPI audio recording |
| **v4.0.0-beta-2** | 2026-08-29 | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-2/loginalertx-setup-v4.0.0-beta-2.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-2/loginalertx-setup-v4.0.0-beta-2.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-2/loginalertx-setup-v4.0.0-beta-2.tar.gz) | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-2/loginalertx-server-setup-v4.0.0-beta-2.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-2/loginalertx-server-setup-v4.0.0-beta-2.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-2/loginalertx-server-setup-v4.0.0-beta-2.tar.gz) | Unified license management, improved wizard validation, Microsoft Store WhatsApp fix |
| **v4.0.0-beta-1** | 2026-08-25 | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-1/loginalertx-setup-v4.0.0-beta-1.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-1/loginalertx-setup-v4.0.0-beta-1.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-1/loginalertx-setup-v4.0.0-beta-1.tar.gz) | [EXE](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-1/loginalertx-server-setup-v4.0.0-beta-1.exe) \| [DEB](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-1/loginalertx-server-setup-v4.0.0-beta-1.deb) \| [TAR](https://github.com/vishwas-r/login-alertx-dist/releases/download/v4.0.0-beta-1/loginalertx-server-setup-v4.0.0-beta-1.tar.gz) | Initial v4 preview, CLI management tool, native Linux daemon, Fluent UI redesign |

---

## Installation Instructions

### Windows

Run the executable installer with administrative privileges:

```cmd
loginalertx-setup-v4.4.0.exe
```

For silent enterprise deployments:

```cmd
loginalertx-setup-v4.4.0.exe /VERYSILENT /NORESTART
```

### Linux (Debian / Ubuntu)

Install using the Debian package manager:

```bash
sudo dpkg -i loginalertx-setup-v4.4.0.deb
sudo apt-get install -f
```

For server installations, verify that the systemd service is active:

```bash
sudo systemctl status loginalertx
```

### Linux (Portable Archive)

Extract the `.tar.gz` package to the desired destination:

```bash
sudo tar -xzf loginalertx-setup-v4.4.0.tar.gz -C /opt/loginalertx
cd /opt/loginalertx
sudo ./install.sh
```

---

## Verification

To verify the integrity of downloaded binaries, compare the computed SHA-256 checksum against the values published above.

### Windows (PowerShell)

```powershell
Get-FileHash -Algorithm SHA256 .\loginalertx-setup-v4.4.0.exe
```

### Linux / macOS

```bash
sha256sum loginalertx-setup-v4.4.0.deb
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
