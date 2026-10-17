<img width="1179" height="1172" alt="IMG_1345" src="https://github.com/user-attachments/assets/9d437b0b-54ba-402c-ba73-ce26f4421242" />


# BergOS

**A customizable Linux distribution with two editions: Standard and Lite.**

BergOS is a Linux distribution project focused on simplicity, customization, and accessibility across different hardware generations.

Based on Ubuntu and its ecosystem, BergOS aims to provide a clean desktop experience, a streamlined installation process, and an optional software selection system.

The project offers two planned editions:

- **BergOS Standard** — a modern desktop operating system for everyday use, development, gaming, and productivity.
- **BergOS Lite** — a lightweight edition designed for older computers and systems with limited hardware resources.

Both editions share the same project identity and modular philosophy while targeting different hardware requirements.

---

## Project Overview

BergOS aims to make Linux easier to install, customize, and maintain.

Instead of shipping every possible application in the base image, the project follows a minimal-core approach: install the essentials first and allow users to expand the system according to their needs.

The project is designed around three principles:

- **Simplicity:** a clean desktop and a straightforward installation experience.
- **Modularity:** optional software and tools organized into categories.
- **Compatibility:** separate editions for different hardware capabilities.

## Editions

### BergOS Standard

A modern desktop edition intended for reasonably recent computers.

Planned features include:

- KDE Plasma desktop environment.
- Ubuntu LTS foundation.
- Graphical installation with Calamares.
- APT package management.
- Optional Flatpak and Flathub integration.
- Development, gaming, multimedia, and virtualization profiles.
- Custom themes, icons, and wallpapers.

[Read the Standard edition documentation](editions/standard/README.md).

### BergOS Lite

A lightweight edition intended for older computers and systems with limited RAM and processing power.

Planned features include:

- A minimal Linux base selected for compatibility and maintainability.
- A lightweight window manager, such as IceWM.
- X11 support where appropriate for legacy hardware.
- A reduced set of background services.
- Lightweight applications and optional software profiles.
- A simplified desktop experience.

Support for this hardware will depend on processor architecture, driver compatibility, available packages, and security maintenance.

[Read the Lite edition documentation](editions/lite/README.md).

## Core Philosophy

BergOS follows a minimal-core, modular-expansion philosophy.

The base installation should contain only the components necessary to provide a functional system. Additional applications should remain optional whenever practical.

The project aims to provide:

- Small and maintainable software selections.
- Clear separation between core components and optional applications.
- Reproducible installation images.
- Consistent branding across both editions.
- Hardware-appropriate defaults.
- Transparent documentation of supported features.

## Technology

The planned technology stack includes:

| Component | Technology |
|---|---|
| Standard base | Ubuntu LTS |
| Standard desktop | KDE Plasma |
| ISO customization | Cubic |
| Graphical installer | Calamares, subject to integration and testing |
| Package management | APT |
| Additional applications | Flatpak, where appropriate |
| Networking | NetworkManager |
| Audio | PipeWire, where appropriate |
| Lite desktop | IceWM or another lightweight alternative |
| Lite display server | X11, where supported |

The final configuration may change during development as compatibility and maintenance requirements are evaluated.

## Roadmap

BergOS is developed through a series of planned milestones, gradually evolving from a minimal Kubuntu-based system into a fully customizable Linux distribution.

Future releases will introduce custom branding, the Calamares installer, BergOS Software Selection, hardware-aware Adaptive Setup, the Lite and Server editions, and a custom desktop experience.

The v0.x development cycle will focus on stability, modularity, accessibility, and giving users greater control over their systems.

For the complete list of planned features and release milestones, see the [BergOS Roadmap](ROADMAP.md).

## License

The project's licensing terms will be documented in the repository's `LICENSE` file.

Third-party software and assets remain subject to their respective licenses.

---

**BergOS — One project. Two editions. More life for every computer.**

## Project Status

BergOS is currently under active development.  
The architecture, installer, software selection system, and default configuration may evolve as development continues.

Release updates will be published on the official Discord server:  
**https://discord.gg/mTVVcZVsx**

