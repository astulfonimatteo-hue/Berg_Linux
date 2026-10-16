# BergOS Standard

**A modern, customizable Debian-based desktop operating system.**

BergOS Standard is the main edition of BergOS, designed to provide a balanced desktop experience combining usability, performance, stability, and flexibility.

Built on Debian GNU/Linux, it aims to offer a clean desktop environment with a minimal base installation and an optional software selection system.

The goal is to provide a reliable everyday operating system that can be expanded into a complete workstation for development, gaming, multimedia, and general productivity.

---

## Features

The planned features of BergOS Standard include:

- Debian-based operating system.
- XFCE desktop environment.
- Graphical installation through Calamares.
- Modular first-boot software selection.
- APT package management.
- Flatpak and Flathub integration.
- PipeWire audio support.
- NetworkManager for network configuration.
- Optional Btrfs filesystem and snapshot management.
- Optional development, gaming, and multimedia profiles.
- Custom BergOS themes, icons, and wallpapers.

Features will be implemented and tested progressively during development.

## System Components

| Component | Planned Technology |
|---|---|
| Base distribution | Debian GNU/Linux |
| Desktop environment | XFCE |
| Display server | Wayland where supported, with X11 compatibility |
| Display manager | SDDM |
| Init system | systemd |
| Audio | PipeWire |
| Networking | NetworkManager |
| Package management | APT |
| Additional applications | Flatpak |
| Application repository | Flathub |
| Installer | Calamares |
| Filesystem | Btrfs, where appropriate |
| Snapshot management | Snapper and/or Timeshift |

The final configuration may change according to compatibility and testing results.

## Intended Use

BergOS Standard is intended for:

- Everyday desktop use.
- Web browsing and office productivity.
- Software development and programming.
- Gaming and game compatibility tools.
- Multimedia creation and playback.
- Virtualization and container workloads.
- System administration and networking.

Additional software will be available through optional installation profiles.

## Installation Philosophy

BergOS Standard follows a minimal-core approach.

The base installation is intended to contain the essential operating system, desktop environment, system utilities, and installer.

Additional applications can be installed through the BergOS Software Selection interface.

This approach aims to reduce unnecessary preinstalled software while allowing users to configure their systems according to their needs.

## Hardware Requirements

Final requirements will be determined through testing.

The intended target is modern or reasonably recent x86-64 hardware.

A practical starting point for testing is:

- **Architecture:** x86-64.
- **Memory:** 4 GB RAM or more recommended.
- **Storage:** SSD recommended.
- **Graphics:** Hardware supported by the selected Debian kernel and graphics stack.

Actual requirements depend on the installed applications and desktop configuration.

## Development Status

BergOS Standard is under development.

Planned milestones:

- [ ] Establish a reproducible ISO build.
- [ ] Configure the base Debian system.
- [ ] Integrate XFCE and system services.
- [ ] Configure the Calamares installer.
- [ ] Implement BergOS Software Selection.
- [ ] Define optional software profiles.
- [ ] Integrate Flatpak and Flathub.
- [ ] Test installation, updates, and recovery.

## Documentation

- [Main Project README](../../README.md)
- [Software Catalog](../../APPLICATIONS.md)
- [Contributing Guidelines](../../CONTRIBUTING.md)

## Philosophy

BergOS Standard aims to provide a clean and flexible desktop without forcing users to install software they do not need.

**A minimal foundation. A complete workstation when you need it.**
