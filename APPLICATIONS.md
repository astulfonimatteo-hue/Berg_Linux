## Optional Software

The following applications are available through the BergOS Software Selection system and are not included directly in the base ISO.

### Desktop Applications
- Firefox
- Dolphin
- Konsole
- Ghostty
- Kate
- Ark
- Spectacle
- Discover
- flatpak-kcm
- Discord
- Development
- Visual Studio Code
- base-devel
- Docker
- Distrobox
- Steam
- Proton
- GameMode
- MangoHud

BergOS provides an optional cybersecurity toolkit for users interested in security research, penetration testing, network analysis, and defensive security.

### Available tools include:

- Nmap
- Wireshark
- Burp Suite
- Metasploit Framework
- John the Ripper
- Hydra
- Aircrack-ng
- Netcat
- Socat
- Gobuster
- Hashcat
- SQLMap
- Nikto
- Exploit-DB

These tools are optional and are installed only when explicitly selected by the user.

They are intended for authorized security testing, education, research, and defensive security purposes. Users are responsible for obtaining appropriate authorization before testing systems, networks, applications, or devices.

### Software Selection

The BergOS Software Selection interface is designed around categories rather than individual packages.

A typical first-boot installation could provide categories such as:

- Desktop Applications
- Development
- Gaming
- Virtualization and Containers
- Cybersecurity
- Networking
- System Administration
- Multimedia

Users can select one or more categories and review the applications associated with each category before starting the installation.

The installer then resolves and installs the required packages using the appropriate package source.

This allows the BergOS ISO to remain focused on the core operating system while still providing access to a broad software ecosystem.

### Package Management

BergOS supports multiple package management ecosystems.

The primary package manager is pacman, providing access to the official Arch Linux repositories.

yay is available for packages distributed through the Arch User Repository.

Flatpak is supported with Flathub enabled, providing access to applications distributed independently from the native package repositories.

Depending on the selected application, the BergOS Software Selection system can install software from the appropriate source.

### Development Enviroment

Development tools are provided as optional components rather than being included in the base ISO.

Users can select a development environment during the first boot and install tools such as Visual Studio Code, Git, Python, base-devel, Docker, and Distrobox.

This allows users who intend to use BergOS primarily for development to configure a dedicated development environment without requiring every installation to include the same software.

### Gaming Environment

Gaming support is also optional.

Users can select the gaming profile during the first boot to install Steam, Proton, GameMode, and MangoHud.

Keeping these components outside the base ISO avoids including large or specialized packages for users who do not intend to use the system for gaming.

### Cybersecurity Environment

Cybersecurity tooling is provided as an optional software profile.

Users can choose to install individual tools or an entire security-oriented toolkit through the first-boot software selector.

The toolkit includes utilities for network reconnaissance, packet analysis, web application security testing, password auditing, wireless security, exploitation research, and vulnerability assessment.

This modular approach prevents specialized security software from being installed on systems where it is not required.

### Filesystem and Recovery

BergOS uses Btrfs as its primary filesystem.

Snapper and Timeshift are available for snapshot management and system recovery.

The snapshot-based architecture is intended to provide an additional layer of protection when performing system upgrades, installing large software collections, or making significant configuration changes.

### Desktop Environment

BergOS uses KDE Plasma 6 as its primary desktop environment.

Wayland is the default display protocol, while an X11 session remains available for compatibility.

SDDM is used as the display manager.

The desktop stack is designed to provide a modern graphical environment while retaining compatibility with applications and hardware that may still require X11.

## Audio and Networking

PipeWire provides the system audio and multimedia infrastructure.

NetworkManager handles wired and wireless networking, VPN connections, and other network configuration requirements.

BergOS also provides both xdg-desktop-portal and xdg-desktop-portal-kde for proper integration between sandboxed applications and the KDE Plasma desktop.

