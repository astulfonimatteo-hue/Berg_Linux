# BergOS Server Edition

**BergOS Server** is a minimal, lightweight, headless operating system designed for home labs, self-hosted applications, cloud instances, and virtualization hosts.

Built on top of the rock-solid **Ubuntu LTS Server** base, BergOS Server strips away unnecessary graphical interface components to maximize resource availability, system security, and uptime.

---

## Key Features

- **Minimal Headless Core:** No pre-installed Graphical User Interface (GUI), ensuring minimal RAM and CPU utilization out of the box.
- **Container & Self-Hosting Ready:** Tailored for running Docker, Podman, and LXC containers with minimal host overhead.
- **Network & Administration Profile:** Pre-configured SSH, firewall defaults (`ufw`), and essential networking diagnostics tools (`iperf3`, `traceroute`, `nmtui`).
- **Modular Server Roles:** Optional post-installation scripts to quickly deploy web servers (Nginx/Caddy), VPN nodes (WireGuard/Tailscale), and storage management utilities.
- **Security & Maintenance First:** Automated security updates, minimal attack surface, and transparent system logging via `journalctl` and `systemd`.

---

## Technical Specifications

- **Architecture:** 64-bit (`x86_64`)
- **Base System:** Ubuntu LTS Server
- **Interface:** Command Line Interface (CLI) / Headless
- **Installer:** Subiquity / Calamares (Server Mode)
- **Networking:** NetworkManager / netplan
- **Security Defaults:** UFW enabled, SSH pre-configured
- **Package Management:** APT

---

## Minimum System Requirements

- **Processor:** 64-bit Single-Core CPU (1.0 GHz or higher)
- **RAM:** 1 GB minimum (2 GB recommended for container hosting)
- **Storage:** 10 GB available disk space
- **Network:** Ethernet or Wi-Fi network interface
