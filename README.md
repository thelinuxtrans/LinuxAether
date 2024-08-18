# Linux Aether

Welcome to **Linux Aether**! Linux Aether is a cutting-edge Linux distribution designed to offer an exceptional computing experience. Whether you're a developer, designer, or a casual user, Linux Aether provides a powerful, elegant, and highly customizable environment tailored to your needs.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [System Requirements](#system-requirements)
4. [Installation Guide](#installation-guide)
5. [Getting Started](#getting-started)
6. [Desktop Environment](#desktop-environment)
7. [Package Management](#package-management)
8. [System Configuration](#system-configuration)
9. [Security](#security)
10. [Community and Support](#community-and-support)
11. [Contributing](#contributing)
12. [License](#license)

## Introduction

Linux Aether aims to deliver a superior and highly customizable Linux experience. It combines the stability and performance of the Linux kernel with an intuitive wiki and great documentation.

# Features


### User Interface
- **Custom Desktop Environment**: There are many Desktop Environments (DE) to choose from, i.e Kde Plasma, GNOME etc.
- **Custom Window Manager**: There are also a plethora of Window Managers (WM) to choose from, i.e i3-wm, DWM etc.
- **Themes and Customization**: A variety of themes, icons, and extensions are avalible in most Desktop Environments to personalize your desktop.

### Software
- **Software Repository**: Access to a vast repository of applications through the Aether Package Manager (APM).

### Security
- **Enhanced Security Features**: Linux Aether is designed to have possibility for any and all software to run, this also includes support for firewall, bluetooth etc.
- **Privacy Focused**: Tools and settings to ensure user privacy and data protection.

## System Requirements 

### Minimum Requirements
- **CPU**: 1 GHz dual-core processor
- **RAM**: 2 GB
- **Storage**: 20 GB of available space
- **Display**: 1024x768 resolution

### Recommended Requirements
- **CPU**: 2 GHz dual-core processor or better
- **RAM**: 4 GB or more
- **Storage**: 40 GB of SSD space
- **Display**: 1920x1080 resolution

## Installation Guide

### Download the ISO
Download the latest ISO image from the [Linux Aether website](https://www.linuxaether.org/downloads).

### Create a Bootable USB
Use a tool like Rufus (Windows), Etcher (Linux/Mac), or the command line to create a bootable USB drive.

### Boot from USB
1. Insert the USB drive into your computer.
2. Reboot your system and enter the BIOS/UEFI settings.
3. Disable Secure Boot (REQUIRED)
4. Set the USB drive as the primary boot device.
5. Save changes and reboot.

### Installation Steps
1. Follow the comprehensive guide at: [Aether Install Guide](https://linuxaether.org/install-guide)

## Getting Started

### Initial Setup
Upon first boot, follow the initial setup wizard to:
- Create a user account.
- Set up your network.
- Choose your preferred language and time zone.
- Follow the full install guide at [Aether Install Guide](https://linuxaether.org/install-guide)

### Updating the System
Open a terminal and run the following commands to update the system:
```bash
sudo apm -upd
```

### Installing Additional Software
Use the Aether Package Manager (APM) to install additional software:
```bash
sudo apm install <package_name>
```

## Package Management

### Aether Package Manager (APM)
APM is the primary tool for package management in Linux Aether.
- **Install Packages**: `sudo apm install <package_name>`
- **Remove Packages**: `sudo apm remove <package_name>`
- **Search Packages**: `sudo apm search <package_name>`
- **Update Packages**: `sudo apm update <package_name>`

### Snap and Flatpak Support
Linux Aether supports Snap and Flatpak for additional swoftware availability.
- **Snap**: `sudo snap install <package_name>`
- **Flatpak**: `flatpak install flathub <package_name>`

## System Configuration

### Network Settings
**Connect to wifi**: ispcu (Internet Service Post Configuration Utility)

### Display Settings
Adjust resolution, refresh rate, and monitor arrangement with sysres --mode <resolution> (i.e 1920x1080)

### User Management
List user accounts with usrmgr --list
Add user accounts with usrmgr -n <name> <sudo y/n>

### System Updates
Regular updates ensure your system remains secure and up-to-date. Check for updates via System Settings > Updates or use the terminal:
```bash
sudo apm -upd && sudo apm -upg
```

## Security


### Regular Updates
Ensure your system is secure by regularly applying updates. Enable automatic updates via System Settings > Updates.

## Community and Support

### Documentation
Comprehensive documentation is available at the [Linux Aether Documentation](https://www.linuxaether.org/docs).

### Forums
Join our community forums at [Linux Aether Forums](https://forums.linuxaether.org) to ask questions, share tips, and connect with other users.

### Bug Reports
Report bugs and issues on our [GitHub Issues page](https://github.com/linuxaether/issues).

## Contributing

### How to Contribute
We welcome contributions from the community! Check out our [Contributing Guide](https://github.com/linuxaether/contributing) to get started.

### Code of Conduct
Please read and adhere to our [Code of Conduct](https://linuxaether.com/coc).

### Reporting Issues
Use the [GitHub Issues page](https://github.com/linuxaether/issues) to report bugs or suggest features.

## License

Linux Aether is released under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). You are free to use, modify, and distribute this software under the terms of this license.

---

Thank you for choosing Linux Aether! We hope you enjoy your experience. If you have any questions or need assistance, please reach out to our community and support channels.

---
