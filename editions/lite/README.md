
# BergOS Lite

**A lightweight Linux edition for older computers.**

BergOS Lite is designed to make older hardware useful through a carefully configured desktop, a reduced set of background services, and lightweight applications.

It shares the BergOS identity and modular philosophy but prioritizes compatibility, low resource consumption, and maintainability.

---

## Goals

BergOS Lite aims to provide:

- Low memory consumption.
- Minimal background activity.
- A simple and responsive desktop.
- Compatibility with older graphics and network hardware where possible.
- A reduced package selection.
- Lightweight applications.
- A maintainable software base with appropriate security updates.
- Consistent BergOS branding.

## Base Distribution

The base distribution has not yet been finalized.

The choice must account for:

- CPU architecture: 32-bit or 64-bit.
- Kernel and bootloader compatibility.
- Availability of maintained repositories.
- Security update availability.
- Graphics and networking drivers.
- Available lightweight desktop packages.
- The project's ability to test and maintain the resulting system.

A modern Ubuntu LTS image must not be assumed to support every legacy processor.

The project will choose a base that can be maintained securely rather than relying on an unsupported release solely to support old hardware.

## Planned Desktop

BergOS Lite will evaluate lightweight desktop options such as:

- **IceWM:** a lightweight window manager.
- **XFCE:** an option for systems with sufficient memory.
- Other lightweight alternatives where compatibility requires them.

The final desktop will be chosen through testing rather than by assuming that the lightest interface is always the most usable.

## Planned Components

| Component | Planned Approach |
|---|---|
| Base distribution | To be determined |
| CPU architecture | To be verified |
| Desktop | IceWM or another lightweight option |
| Display server | X11 where supported |
| Networking | Minimal compatible configuration |
| Audio | Optional, depending on hardware and resource usage |
| Package management | APT if supported by the selected base |
| Applications | Lightweight and individually selected |
| Installer | To be determined after base selection |
| Filesystem | A simple, compatible default |

Not every component available in Standard will necessarily be included in Lite.

## Target Hardware

BergOS Lite is intended for:

- Older laptops and desktops.
- Computers with limited RAM.
- Legacy x86 hardware where a maintained software base is available.
- Basic offline tasks.
- Lightweight text editing and file management.
- Terminal-based administration.
- Simple local media playback where supported.

## Resource Management

BergOS Lite will prioritize essential functionality over a large selection of preinstalled software.

The project will evaluate:

- Memory consumption after boot.
- Number of running background services.
- Desktop responsiveness.
- Disk usage.
- Boot time.
- Network and graphics compatibility.

Flatpak, heavy desktop environments, and unnecessary background services will remain optional or be excluded where they are unsuitable.


## Philosophy

BergOS Lite is not intended to reproduce every feature of Standard.

Its purpose is to provide a simple, lightweight, and maintainable system for hardware that cannot comfortably run a modern full desktop.

**Less overhead. More life for older hardware.**
