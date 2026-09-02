# Berg_Linux

<img width="1179" height="1172" alt="IMG_1345" src="https://github.com/user-attachments/assets/9d437b0b-54ba-402c-ba73-ce26f4421242" />


BergOS is an Arch Linux-based operating system built on top of the EndeavourOS ecosystem, designed to provide a modern, reliable, and highly customizable desktop environment out of the box.

BergOS combines KDE Plasma 6, a Linux LTS kernel, Btrfs-based system recovery, multiple software distribution methods, and an optional software selection system that allows users to configure their installation according to their needs.

Unlike distributions that ship every application directly inside the installation image, BergOS keeps the base ISO focused on the operating system itself. Additional applications and specialized toolsets can be selected and installed during the first boot through the BergOS software selection interface.

## System Overview

BergOS is based on EndeavourOS and Arch Linux and uses KDE Plasma 6 as its primary desktop environment.

The default graphical session uses Wayland, with X11 available as a fallback for compatibility.

The system is built around the Linux LTS kernel, systemd, dracut, PipeWire, NetworkManager, and Btrfs. Snapper and Timeshift provide additional snapshot and recovery capabilities.

The base installation is intentionally kept lightweight. Applications that are not required for the core desktop experience are not included directly in the ISO.

## Core stack
- Base: EndeavourOS / Arch Linux
- Kernel: Linux LTS
- Kernel Headers: linux-lts-headers
- Desktop Environment: KDE Plasma 6
- Display Server: Wayland
- X11: Available as a fallback session
- Display Manager: SDDM
- Init System: systemd
- Initramfs: dracut
- Audio: PipeWire
- Network Management: NetworkManager
- Filesystem: Btrfs
- Snapshot Management: Snapper and Timeshift
- Native Package Manager: pacman
- AUR Helper: yay
- Universal Package Management: Flatpak
- Flatpak Repository: Flathub
- Desktop Portals: xdg-desktop-portal and xdg-desktop-portal-kde

## First Boot Experience
BergOS uses a modular approach to software installation.

The installation ISO contains the core operating system, desktop environment, essential system utilities, and components required for the system to operate correctly.

Additional applications are presented to the user during the first boot through the BergOS Software Selection interface.

Instead of forcing every user to install the same collection of applications, BergOS allows users to select the software categories they actually need.

The first-boot software selector can be used to install optional applications such as development tools, gaming software, communication applications, and cybersecurity utilities.

This approach keeps the installation image smaller while allowing BergOS to provide a much broader software selection after installation.

Discover more on the APPLICATION.md file.

## Audio and Networking

PipeWire provides the system audio and multimedia infrastructure.

NetworkManager handles wired and wireless networking, VPN connections, and other network configuration requirements.

BergOS also provides both xdg-desktop-portal and xdg-desktop-portal-kde for proper integration between sandboxed applications and the KDE Plasma desktop.

## Design Philosophy

BergOS follows a modular design philosophy.

The base ISO should contain only what is necessary to provide a functional operating system and desktop environment. Everything else should be optional.

This provides several advantages:

- Smaller installation media
- Faster installation
- Less unnecessary software
- User-controlled system configuration
- Easier maintenance
- Clear separation between core components and optional software
- Ability to provide specialized software profiles without maintaining separate ISO images

The goal is to provide a system that starts minimal, but can become highly specialized depending on the user's requirements.

## Project Goals

BergOS aims to provide a flexible Arch-based workstation suitable for a wide range of users.

The project focuses on:

- A modern KDE Plasma 6 desktop
- A stable Linux LTS kernel
- Wayland-first desktop architecture
- Btrfs-based snapshot and recovery capabilities
- Native Arch and AUR package management
- Flatpak and Flathub integration
- Modular first-boot software installation
- Optional development tooling
- Optional gaming support
- Optional cybersecurity tooling
- Container support through Docker and Distrobox

Rather than maintaining different editions for different use cases, BergOS uses a single base system with optional software profiles.

## Project Status

BergOS is currently under development.

The architecture, software selection system, default packages, installation process, and system configuration may change as development progresses.

BergOS should be considered a development project until an official stable release is published.
