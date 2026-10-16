
# BergOS Standard

**A modern Ubuntu-based desktop experience.**

BergOS Standard is the main edition of BergOS, designed for everyday computing, productivity, software development, and entertainment.

It aims to combine the familiarity of XFCE with a customizable desktop, a clean software selection, and a streamlined installation experience.

The edition is intended for reasonably recent computers with sufficient resources for a modern Linux desktop.

---

## Features

Planned features include:

- Ubuntu LTS foundation.
- XFCE desktop environment.
- Custom BergOS themes, icons, and wallpapers.
- ISO customization using Cubic.
- Graphical installation through Calamares, subject to integration and testing.
- APT package management.
- Optional Flatpak and Flathub support.
- Networking through NetworkManager.
- PipeWire audio support.
- Optional development, gaming, and multimedia profiles.
- Optional virtualization and container tools.
- Optional system snapshot and recovery features.

Features will be introduced and tested progressively.

## Technology Stack

| Component | Planned Technology |
|---|---|
| Base distribution | Ubuntu LTS |
| Desktop environment | XFCE |
| ISO customization | Cubic |
| Installer | Calamares, subject to testing |
| Display server | Compatible session selected for the chosen XFCE version |
| Display manager | To be determined |
| Init system | systemd |
| Networking | NetworkManager |
| Audio | PipeWire |
| Package management | APT |
| Additional applications | Flatpak and Flathub, optionally |
| Filesystem | ext4 by default; other options may be evaluated |

The exact Ubuntu release and package configuration will be selected according to support lifetime, compatibility, and project requirements.

## Intended Use

BergOS Standard is designed for:

- Everyday desktop computing.
- Web browsing and office productivity.
- Programming and software development.
- Gaming and game compatibility tools.
- Multimedia playback and creation.
- Virtualization and container workloads.
- Networking and system administration.

Optional software profiles will allow users to install additional applications without requiring a separate ISO for each use case.

## Minimal Installation

BergOS Standard follows a minimal-core philosophy.

The base system should include the essential desktop, system utilities, networking components, and the packages required for installation and operation.

Additional applications will be provided through optional software categories whenever practical.

This approach aims to reduce unnecessary preinstalled software while preserving a complete desktop experience.

## Hardware Requirements

Final requirements will be established through testing.

The initial target is x86-64 hardware.

A preliminary development target is:

- **Architecture:** 64-bit x86-64.
- **Memory:** 4 GB RAM or more recommended.
- **Storage:** SSD recommended.
- **Graphics:** Supported by the selected Ubuntu base and graphics drivers.

These are development targets, not verified minimum requirements.

## ISO Development

Cubic is the planned tool for customizing a compatible Ubuntu or Xubuntu live ISO.

The workflow will include:

1. Selecting a supported source ISO.
2. Installing or removing packages.
3. Applying BergOS branding and configuration.
4. Integrating and testing the installer.
5. Generating the customized ISO.
6. Testing boot, installation, networking, and first boot in a virtual machine.
7. Testing on physical hardware before publication.

Cubic does not automatically provide a complete distribution build pipeline or guarantee that all custom installer configurations will work.

## Software Profiles

Planned categories include:

- Desktop applications.
- Development tools.
- Gaming support.
- Cybersecurity utilities.
- Multimedia tools.
- Networking utilities.
- Virtualization and containers.
- System administration.

## Philosophy

BergOS Standard aims to provide a modern, flexible desktop without forcing users to install software they do not need.

**A clean desktop. A customizable workstation.**
