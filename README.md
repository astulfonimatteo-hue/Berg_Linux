# Berg_Linux
BergOS

BergOS is an Arch Linux-based operating system built on top of the EndeavourOS ecosystem, designed to provide a modern, reliable, and highly customizable desktop environment out of the box.

BergOS combines KDE Plasma 6, a Linux LTS kernel, Btrfs-based system recovery, multiple software distribution methods, and an optional software selection system that allows users to configure their installation according to their needs.

Unlike distributions that ship every application directly inside the installation image, BergOS keeps the base ISO focused on the operating system itself. Additional applications and specialized toolsets can be selected and installed during the first boot through the BergOS software selection interface.

System Overview

BergOS is based on EndeavourOS and Arch Linux and uses KDE Plasma 6 as its primary desktop environment.

The default graphical session uses Wayland, with X11 available as a fallback for compatibility.

The system is built around the Linux LTS kernel, systemd, dracut, PipeWire, NetworkManager, and Btrfs. Snapper and Timeshift provide additional snapshot and recovery capabilities.

The base installation is intentionally kept lightweight. Applications that are not required for the core desktop experience are not included directly in the ISO.

Core Stack
Base: EndeavourOS / Arch Linux
Kernel: Linux LTS
Kernel Headers: linux-lts-headers
Desktop Environment: KDE Plasma 6
Display Server: Wayland
X11: Available as a fallback session
Display Manager: SDDM
Init System: systemd
Initramfs: dracut
Audio: PipeWire
Network Management: NetworkManager
Filesystem: Btrfs
Snapshot Management: Snapper and Timeshift
Native Package Manager: pacman
AUR Helper: yay
Universal Package Management: Flatpak
Flatpak Repository: Flathub
Desktop Portals: xdg-desktop-portal and xdg-desktop-portal-kde
First Boot Experience

BergOS uses a modular approach to software installation.

The installation ISO contains the core operating system, desktop environment, essential system utilities, and components required for the system to operate correctly.

Additional applications are presented to the user during the first boot through the BergOS Software Selection interface.

Instead of forcing every user to install the same collection of applications, BergOS allows users to select the software categories they actually need.

The first-boot software selector can be used to install optional applications such as development tools, gaming software, communication applications, and cybersecurity utilities.

This approach keeps the installation image smaller while allowing BergOS to provide a much broader software selection after installation.

Optional Software

The following applications are available through the BergOS Software Selection system and are not included directly in the base ISO.

Desktop Applications
Firefox
Dolphin
Konsole
Ghostty
Kate
Ark
Spectacle
Discover
flatpak-kcm
Discord
Development
Visual Studio Code
Git
Python
base-devel
Docker
Distrobox
Gaming
Steam
Proton
GameMode
MangoHud
Cybersecurity

BergOS provides an optional cybersecurity toolkit for users interested in security research, penetration testing, network analysis, and defensive security.

Available tools include:

Nmap
Wireshark
Burp Suite
Metasploit Framework
John the Ripper
Hydra
Aircrack-ng
Netcat
Socat
Gobuster
Hashcat
SQLMap
Nikto
Exploit-DB

These tools are optional and are installed only when explicitly selected by the user.

They are intended for authorized security testing, education, research, and defensive security purposes. Users are responsible for obtaining appropriate authorization before testing systems, networks, applications, or devices.

Software Selection

The BergOS Software Selection interface is designed around categories rather than individual packages.

A typical first-boot installation could provide categories such as:

Desktop Applications
Development
Gaming
Virtualization and Containers
Cybersecurity
Networking
System Administration
Multimedia

Users can select one or more categories and review the applications associated with each category before starting the installation.

The installer then resolves and installs the required packages using the appropriate package source.

This allows the BergOS ISO to remain focused on the core operating system while still providing access to a broad software ecosystem.

Package Management

BergOS supports multiple package management ecosystems.

The primary package manager is pacman, providing access to the official Arch Linux repositories.

yay is available for packages distributed through the Arch User Repository.

Flatpak is supported with Flathub enabled, providing access to applications distributed independently from the native package repositories.

Depending on the selected application, the BergOS Software Selection system can install software from the appropriate source.

Development Environment

Development tools are provided as optional components rather than being included in the base ISO.

Users can select a development environment during the first boot and install tools such as Visual Studio Code, Git, Python, base-devel, Docker, and Distrobox.

This allows users who intend to use BergOS primarily for development to configure a dedicated development environment without requiring every installation to include the same software.

Gaming Environment

Gaming support is also optional.

Users can select the gaming profile during the first boot to install Steam, Proton, GameMode, and MangoHud.

Keeping these components outside the base ISO avoids including large or specialized packages for users who do not intend to use the system for gaming.

Cybersecurity Environment

Cybersecurity tooling is provided as an optional software profile.

Users can choose to install individual tools or an entire security-oriented toolkit through the first-boot software selector.

The toolkit includes utilities for network reconnaissance, packet analysis, web application security testing, password auditing, wireless security, exploitation research, and vulnerability assessment.

This modular approach prevents specialized security software from being installed on systems where it is not required.

Filesystem and Recovery

BergOS uses Btrfs as its primary filesystem.

Snapper and Timeshift are available for snapshot management and system recovery.

The snapshot-based architecture is intended to provide an additional layer of protection when performing system upgrades, installing large software collections, or making significant configuration changes.

Desktop Environment

BergOS uses KDE Plasma 6 as its primary desktop environment.

Wayland is the default display protocol, while an X11 session remains available for compatibility.

SDDM is used as the display manager.

The desktop stack is designed to provide a modern graphical environment while retaining compatibility with applications and hardware that may still require X11.

Audio and Networking

PipeWire provides the system audio and multimedia infrastructure.

NetworkManager handles wired and wireless networking, VPN connections, and other network configuration requirements.

BergOS also provides both xdg-desktop-portal and xdg-desktop-portal-kde for proper integration between sandboxed applications and the KDE Plasma desktop.

Design Philosophy

BergOS follows a modular design philosophy.

The base ISO should contain only what is necessary to provide a functional operating system and desktop environment. Everything else should be optional.

This provides several advantages:

Smaller installation media
Faster installation
Less unnecessary software
User-controlled system configuration
Easier maintenance
Clear separation between core components and optional software
Ability to provide specialized software profiles without maintaining separate ISO images

The goal is to provide a system that starts minimal, but can become highly specialized depending on the user's requirements.

Project Goals

BergOS aims to provide a flexible Arch-based workstation suitable for a wide range of users.

The project focuses on:

A modern KDE Plasma 6 desktop
A stable Linux LTS kernel
Wayland-first desktop architecture
Btrfs-based snapshot and recovery capabilities
Native Arch and AUR package management
Flatpak and Flathub integration
Modular first-boot software installation
Optional development tooling
Optional gaming support
Optional cybersecurity tooling
Container support through Docker and Distrobox

Rather than maintaining different editions for different use cases, BergOS uses a single base system with optional software profiles.

Project Status

BergOS is currently under development.

The architecture, software selection system, default packages, installation process, and system configuration may change as development progresses.

BergOS should be considered a development project until an official stable release is published.

License

The licensing model of BergOS and its individual components will be documented as the project develops.

BergOS is built upon software from multiple upstream projects, each of which remains subject to its respective license.

Contributing

Contributions, testing, bug reports, documentation improvements, and technical feedback are welcome.

Please review the project's contribution guidelines before submitting changes and ensure that proposed modifications are consistent with the architecture and goals of BergOS.
