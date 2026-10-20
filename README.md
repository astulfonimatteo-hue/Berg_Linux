<img width="1179" height="1172" alt="IMG_1345" src="https://github.com/user-attachments/assets/9d437b0b-54ba-402c-ba73-ce26f4421242" />


# BergOS

A customizable, modular Linux distribution designed for simplicity, performance, and accessibility across all hardware generations and server environments.

BergOS provides a clean desktop experience, a streamlined installation process, and an optional software selection system. The project offers four distinct editions tailored to different hardware capabilities and use cases:

- **BergOS Standard** — A modern flagship operating system for everyday productivity, development, gaming, and multimedia.
- **BergOS Lite** — A lightweight desktop edition engineered for resource-constrained systems and older 64-bit hardware.
- **BergOS Retro** — A dedicated legacy edition based on Debian 32-bit (`i386`) designed to give new life to vintage and legacy computers.
- **BergOS Server** — A minimal, headless server distribution optimized for home labs, cloud instances, container hosting, and self-hosted services.

---

## Project Overview

BergOS aims to make Linux accessible, modular, and easy to maintain. Instead of shipping bloated software suites by default, the project follows a **minimal-core philosophy**: install the essentials first, and allow users to expand the system according to their needs.

### Core Principles

- **Simplicity:** Clean desktop environments and streamlined headless defaults.
- **Modularity:** An optional post-installation system to install categorized software profiles on demand.
- **Compatibility:** Dedicated editions to support modern 64-bit PCs, lightweight setups, legacy 32-bit architectures, and server infrastructure.

---

## BergOS Editions Summary

| Feature / Property | BergOS Standard | BergOS Lite | BergOS Retro | BergOS Server |
| :--- | :--- | :--- | :--- | :--- |
| **Target Use** | Modern / Recent PCs | Low-resource 64-bit PCs | Legacy / Vintage 32-bit PCs | Servers & Home Labs |
| **Architecture** | 64-bit (`x86_64`) | 64-bit (`x86_64`) | 32-bit (`i386`) | 64-bit (`x86_64`) |
| **Base System** | KDE Neon / Ubuntu LTS | Xubuntu / Ubuntu LTS | Debian 12 (Bookworm) | Ubuntu LTS Server |
| **Desktop Environment**| KDE Plasma | XFCE | LXDE / IceWM | None (Headless CLI) |
| **Display Server** | Wayland / X11 | X11 | X11 | None |
| **Installer** | Calamares | Calamares | Calamares / Debian | Subiquity / Calamares |
| **Package Manager** | APT, Flatpak | APT, Flatpak | APT | APT, Docker |

---

## Key Features & Ecosystem

### Minimal Core Base
Each edition ships with a carefully curated base system containing only essential utilities, leaving full control in the hands of the user.

### BergOS Software Selection
During or after installation, users can select optional software profiles, including:
- **Desktop Applications:** Daily productivity tools and web browsers.
- **Development Tools:** Compilers, IDEs, Docker, and version control.
- **Gaming Profile:** Steam, Proton, GameMode, and performance overlay tools.
- **Cybersecurity Toolkit:** Network analysis and security research utilities.
- **Virtualization & Containers:** Tools for running VMs and isolated containers.
- **Networking & Server Profiles:** SSH, WireGuard, OpenVPN, Nginx, Docker, and admin tools.
- **System Administration & Multimedia:** Performance monitors, backup tools, and media production suites.

---

## Documentation & Editions

For detailed information, setup instructions, and architecture specifications for each edition, please refer to the respective documentation:

- [Standard Edition Documentation](editions/standard/README.md)
- [Lite Edition Documentation](editions/lite/README.md)
- [Retro Edition Documentation](editions/retro/README.md)
- [Server Edition Documentation](editions/server/README.md)
- [Project Roadmap](ROADMAP.md)

Release updates will be published on the official Discord server:  
**https://discord.gg/mTVVcZVsx**


---

**BergOS — One project. Two editions. More life for every computer.**

