# BergOS

<img width="1179" height="1172" alt="IMG_1345" src="https://github.com/user-attachments/assets/9d437b0b-54ba-402c-ba73-ce26f4421242" />

BergOS is a modern, lightweight, Debian‑based operating system designed to provide a clean, reliable, and customizable XFCE desktop out of the box.  
It focuses on stability, simplicity, modularity, and a streamlined installation experience powered by the Calamares graphical installer.

The base ISO is intentionally minimal: it includes the core Debian system, KDE Plasma 6, essential system components, and the installer.  
All additional software is installed after the first boot through the BergOS Software Selection interface.

---

## System Overview

BergOS is built on top of **Debian Trixie**, using **XFCE** as its primary desktop environment.  

The system is optimized for performance and responsiveness, even on modest hardware.

---

## Core Stack

- **Base:** Debian 13  
- **Kernel:** Debian default
- **Desktop Environment:** XFCE  
- **Display Server:** Wayland (default)  
- **Display Manager:** SDDM  
- **Init System:** systemd  
- **Audio:** PipeWire  
- **Networking:** NetworkManager  
- **Filesystem:** Btrfs  
- **Snapshot Management:** Snapper + Timeshift  
- **Package Manager:** APT  
- **Universal Packages:** Flatpak  
- **Flatpak Repository:** Flathub  
- **Desktop Portals:** xdg-desktop-portal + xdg-desktop-portal-kde  

---

## First Boot Experience

BergOS uses a **modular software installation model**.

The installation ISO contains only the core operating system, XFCE, essential utilities, and the Calamares installer.

During the first boot, users are presented with the **BergOS Software Selection** interface, which allows them to install optional software categories such as:

- Desktop Applications  
- Development Tools  
- Gaming Support  
- Cybersecurity Utilities  
- Virtualization and Containers  
- Multimedia Tools  
- Networking Utilities  
- System Administration Tools  

This approach keeps the ISO small while allowing BergOS to become a powerful workstation depending on user needs.

For details on available software categories, see **APPLICATIONS.md**.

---

## Design Philosophy

BergOS follows a **minimal-core, modular-expansion** philosophy.

The base ISO includes only what is necessary to provide:

- a functional operating system  
- a modern desktop environment  
- a clean installation experience  

Everything else is optional.

### Benefits

- Smaller installation media  
- Faster installation  
- Less unnecessary software  
- User-controlled system configuration  
- Easier maintenance  
- Clear separation between core OS and optional software  
- Ability to provide specialized profiles without separate ISO images  

---

## Project Goals

BergOS aims to provide a flexible Debian-based workstation suitable for a wide range of users.

The project focuses on:

- A modern KDE Plasma 6 desktop  
- A stable Linux LTS kernel  
- Wayland-first desktop architecture  
- Btrfs-based snapshot and recovery capabilities  
- Flatpak and Flathub integration  
- Modular first-boot software installation  
- Optional development tooling  
- Optional gaming support  
- Optional cybersecurity tooling  
- Optional container support  

---

## Project Status

BergOS is currently under active development.  
The architecture, installer, software selection system, and default configuration may evolve as development continues.

Release updates will be published on the official Discord server:  
**https://discord.gg/mTVVcZVsx**

