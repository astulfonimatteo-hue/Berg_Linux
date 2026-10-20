<img width="1179" height="1172" alt="IMG_1345" src="https://github.com/user-attachments/assets/9d437b0b-54ba-402c-ba73-ce26f4421242" />


# BergOS

A customizable, modular Linux distribution designed for simplicity, performance, and accessibility across all hardware generations.

BergOS provides a clean desktop experience, a streamlined installation process, and an optional software selection system. The project offers three distinct editions tailored to different hardware capabilities and use cases:

- **BergOS Standard** — A modern flagship operating system for everyday productivity, development, gaming, and multimedia.
- **BergOS Lite** — A lightweight desktop edition engineered for resource-constrained systems and older 64-bit hardware.
- **BergOS Retro** — A dedicated legacy edition based on Debian 32-bit (`i386`) designed to give new life to vintage and legacy computers.

---

## Project Overview

BergOS aims to make Linux accessible, modular, and easy to maintain. Instead of shipping bloated software suites by default, the project follows a **minimal-core philosophy**: install the essentials first, and allow users to expand the system according to their needs.

### Core Principles

- **Simplicity:** Clean desktop environments with straightforward out-of-the-box defaults.
- **Modularity:** An optional post-installation system to install categorized software profiles on demand.
- **Compatibility:** Dedicated editions to support modern 64-bit PCs, lightweight setups, and legacy 32-bit architectures.

---

## BergOS Editions Summary

| Feature / Property | BergOS Standard | BergOS Lite | BergOS Retro |
| :--- | :--- | :--- | :--- |
| **Target Hardware** | Modern / Recent PCs | Low-resource 64-bit PCs | Legacy / Vintage 32-bit PCs |
| **Architecture** | 64-bit (`x86_64`) | 64-bit (`x86_64`) | 32-bit (`i386`) |
| **Base System** | KDE Neon / Ubuntu LTS | Xubuntu / Ubuntu LTS | Debian 12 (Bookworm) |
| **Desktop Environment** | KDE Plasma | XFCE | IceWM |
| **Display Server** | Wayland / X11 | X11 | X11 |
| **Installer** | Calamares | Calamares | Calamares |
| **Package Manager** | APT, Flatpak | APT, Flatpak | APT |

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
- **System Administration & Multimedia:** Performance monitors, backup tools, and media production suites.

---

## Documentation & Editions

For detailed information, setup instructions, and architecture specifications for each edition, please refer to the respective documentation:

- [Standard Edition Documentation](editions/standard/README.md)
- [Lite Edition Documentation](editions/lite/README.md)
- [Retro Edition Documentation](editions/retro/README.md)
- [Project Roadmap](ROADMAP.md)
## Project Status

BergOS is currently under active development.  
The architecture, installer, software selection system, and default configuration may evolve as development continues.

Release updates will be published on the official Discord server:  
**https://discord.gg/mTVVcZVsx**


---

**BergOS — One project. Two editions. More life for every computer.**

