# BergOS Software Selection

BergOS uses a modular software installation system that allows users to install optional software categories during the first boot.

The base ISO remains lightweight and focused on the core operating system, while additional applications and specialized toolsets can be installed as needed.

---

## Available Software Categories

### 1. Desktop Applications
Essential desktop tools for everyday use.

Includes:
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

---

### 2. Development Tools
A complete development environment for programmers and software engineers.

Includes:
- Visual Studio Code  
- Git  
- Python  
- base-devel  
- Docker  
- Distrobox  

---

### 3. Gaming
Optional gaming support for BergOS.

Includes:
- Steam  
- Proton  
- GameMode  
- MangoHud  

---

### 4. Cybersecurity Toolkit
A collection of tools for authorized security research, penetration testing, and defensive security.

Includes:
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

These tools are installed only when explicitly selected by the user.

---

### 5. Virtualization & Containers
Tools for running virtual machines and containerized environments.

Includes:
- Docker  
- Distrobox  
- QEMU  
- VirtualBox (optional)  

---

### 6. Networking Tools
Utilities for network diagnostics, configuration, and monitoring.

Includes:
- nmtui  
- nm-connection-editor  
- traceroute  
- iperf3  
- OpenVPN  
- WireGuard  

---

### 7. System Administration
Tools for managing and maintaining the system.

Includes:
- htop  
- btop  
- Timeshift  
- Snapper  
- Flatpak utilities  

---

### 8. Multimedia Tools
Applications for audio, video, and media production.

Includes:
- VLC  
- OBS Studio  
- Audacity  
- Kdenlive  

---

## Installation Sources

Depending on the selected application, BergOS installs software from:

- **APT** (native Debian packages)  
- **Flatpak** (with Flathub enabled)  

This ensures compatibility and flexibility across different software ecosystems.

---

## Notes

- All software categories are optional.  
- No optional applications are included directly in the ISO.  
- Users can install multiple categories during the first boot.  
- Categories may expand as development continues.

