
# BergOS Lite

**A lightweight Debian-based operating system for older computers.**

BergOS Lite is the lightweight edition of BergOS, designed to make Linux usable on older computers and systems with limited hardware resources.

It follows the same minimal-core philosophy as BergOS Standard, but prioritizes low memory consumption, reduced background activity, compatibility, and simplicity.

The goal is to extend the useful life of older hardware without sacrificing the essential features of a modern Linux operating system.

---

## Features

The planned features of BergOS Lite include:

- A minimal Debian-based system.
- A lightweight desktop or window manager, such as IceWM.
- X11 support for compatibility with older graphics hardware.
- A reduced set of background services.
- Essential networking and audio components.
- APT as the primary package manager.
- A lightweight graphical installer where supported.
- A simplified software selection interface.
- Optional lightweight desktop applications.
- BergOS branding adapted to the Lite edition.

The final feature set will depend on the target architecture and hardware compatibility.

## System Components

| Component | Planned Technology |
|---|---|
| Base distribution | Debian-based, selected for architecture compatibility |
| Desktop | IceWM or another lightweight window manager |
| Display server | X11 |
| Init system | systemd, where supported by the selected base |
| Networking | NetworkManager or a lighter suitable configuration |
| Audio | PipeWire or another compatible configuration |
| Package management | APT |
| Additional applications | Selected individually for compatibility |
| Installer | Calamares or another suitable installation method |
| Filesystem | ext4 by default, with other options where appropriate |

The configuration will be kept as small as reasonably possible.

## Design Goals

BergOS Lite prioritizes:

### Low Resource Consumption

Keep memory usage and background activity low so that older computers remain responsive.

### Hardware Compatibility

Prefer software that works with older processors, graphics adapters, network devices, and other legacy hardware.

### Simplicity

Provide a straightforward desktop with essential utilities instead of a large collection of preinstalled applications.

### Maintainability

Use a clearly defined package set and a build process that can be tested and reproduced.

### Shared BergOS Identity

Maintain consistent branding, documentation, and project philosophy across both editions.

## Intended Use

BergOS Lite is intended for:

- Older desktop computers and laptops.
- Systems with limited RAM.
- Basic offline computing.
- Lightweight text editing and document work.
- Simple local media playback.
- Terminal-based administration.
- Older hardware that is incompatible with the standard edition.

Modern web browsing may remain limited on very old computers because contemporary browsers and websites can require substantial memory and CPU resources.

## Legacy Hardware and Architecture

BergOS Lite will evaluate support for older x86 systems, including 32-bit hardware where a suitable and maintainable software base is available.

Architecture support will depend on:

- Available Debian repositories and security updates.
- Kernel and bootloader compatibility.
- Graphics and network driver availability.
- Application architecture requirements.
- The project's ability to maintain and test the edition.

**Important:** 32-bit support is not guaranteed. The selected base must remain maintainable and receive appropriate security updates.

A legacy edition must not rely on an unsupported operating system simply to run on older hardware.

## Hardware Requirements

The minimum supported configuration has not yet been established.

The project will test the edition on progressively older hardware, including systems with limited RAM and legacy graphics adapters.

The Acer Aspire 1310 is one of the intended test systems, subject to verification of its exact processor, memory, and hardware configuration.

## Installation Philosophy

BergOS Lite aims to install only the components needed for a functional desktop.

Optional applications should be installed individually or through lightweight software profiles.

The default installation will prioritize:

- A working desktop.
- Network connectivity where hardware permits.
- Basic system utilities.
- Lightweight text and file management tools.
- Simple system maintenance.

Heavy desktop environments and unnecessary background services will be avoided.

## Development Status

BergOS Lite is under development.

Planned milestones:

- [ ] Identify supported processor architectures.
- [ ] Select a suitable and maintainable Debian base.
- [ ] Establish a reproducible lightweight ISO build.
- [ ] Configure a lightweight graphical environment.
- [ ] Test memory and CPU consumption.
- [ ] Verify legacy graphics and network compatibility.
- [ ] Integrate a suitable installer.
- [ ] Define a lightweight software catalog.
- [ ] Test installation and security updates on older hardware.

## Documentation

- [Main Project README](../../README.md)
- [Software Catalog](../../APPLICATIONS.md)
- [Contributing Guidelines](../../CONTRIBUTING.md)

## Philosophy

BergOS Lite is designed to give older computers a practical second life through a lightweight, maintainable, and carefully configured Linux system.

**Less overhead. More life for older hardware.**
