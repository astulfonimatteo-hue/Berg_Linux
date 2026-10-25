# BergOS Roadmap

BergOS is developed incrementally across four specialized editions: **Standard**, **Lite**, **Retro**, and **Server**. Each milestone introduces foundational core components, expands hardware compatibility, or adds modular features.

*Note: All roadmap items represent planned milestones and may evolve based on community feedback, hardware compatibility, and maintenance requirements.*

---

## Phase 1 — Foundations & Core Editions

### [v1.0 — BergOS Retro (32-bit Core)](https://github.com/astulfonimatteo-hue/BergOS-Retro-Edition/releases/tag/v1.0)
- **Official release of BergOS Retro:** Dedicated 32-bit (`i386`) edition based on Debian 12 (Bookworm).
- Ultra-lightweight IceWM desktop environment tuned for legacy computers with 512 MB+ RAM.
- Optimized system defaults, minimal background services, and core system utilities.
- Functional live ISO environment with Calamares graphical installer integration.

### [v1.1 — BergOS Lite](https://github.com/astulfonimatteo-hue/BergOS-Lite-Edition/releases/tag/v1.1) 
- **Introduce BergOS Lite:** 64-bit (`x86_64`) lightweight desktop edition based on Debian 13 with XFCE.
- Baseline system architecture, initial boot stability testing, and live ISO environment verification across real hardware and virtual machines.

### [v1.2 — BergOS Standard](https://github.com/astulfonimatteo-hue/BergOS-Standard-Edition/releases/tag/v1.2)
- **Introduce BergOS Standard:** 64-bit (`x86_64`) modern flagship edition based on KDE Neon / Ubuntu LTS with KDE Plasma.
- Baseline system architecture, initial boot stability testing, and live ISO environment verification across real hardware and virtual machines.

### [v1.3 — BergOS Server Edition](https://github.com/astulfonimatteo-hue/BergOS-Server-Edition/releases/tag/v1.3)
- **Introduce BergOS Server:** Headless 64-bit (`x86_64`) server distribution based on Ubuntu LTS Server.
- Optimized for home labs, cloud instances, Docker hosting, and self-hosted microservices.
- Automated SSH configuration, firewall profiles, and lightweight CLI admin utilities.
- Comprehensive security hardening and maintenance guidelines documentation.

### v1.4 — Unified BergOS Branding
- Consistent visual identity across Standard, Lite, Retro and Server editions.
- Official BergOS wallpapers, window manager themes, fastfetch and color palettes.

---

## Phase 2 — Modularity & Adaptive Setup

### v2.0 — BergOS Modular Software Selection
- Introduction of the optional post-installation **Software Selection** framework.
- Categorized application profiles:
  - **Desktop Applications:** Daily productivity suite and modern web browsers.
  - **Development Tools:** Compilers, IDEs, Docker, and version control.
  - **Gaming Profile:** Steam, Proton, GameMode, and performance overlays.
  - **Cybersecurity Toolkit:** Network diagnostics and auditing tools.
  - **Virtualization & Containers:** VM managers and container engines.
  - **Networking & Server Profiles:** SSH, WireGuard, OpenVPN, Nginx, and admin tools.
  - **System Administration & Multimedia:** Performance monitors, backup solutions, and audio/video suites.
- Integrated package management handling both APT repositories and Flatpak packages.

### v2.1 — BergOS Adaptive Hardware Setup
- First-boot hardware detection engine.
- Dynamic adjustments to desktop settings, compositor pipelines, and power management based on system resources.
- Safe fallbacks for unsupported legacy GPU configurations or restricted hardware environments.
- Recommended software profile suggestions tailored to detected RAM and CPU performance.

---

## Phase 3 — Ecosystem Expansion & Custom Tooling

### v3.0 — Custom Desktop Experience
- Redesigned KDE Plasma desktop layout for BergOS Standard (custom dock/panel layout, app launcher, and workflow enhancements).
- Fine-tuned XFCE and IceWM configurations for optimized resource consumption.
- Enhanced default desktop utilities and user-friendly system settings menus.

### v3.2 — Custom BergOS Installer & System Profiles
- **BergOS Custom Installer:** Edition-aware, branded installation wizard extending Calamares/Subiquity.
- **Persistent System Profiles:** Post-install configuration manager allowing users to enable, review, or modify installed software profiles and system defaults.
- Diagnostic tools and visual reports for applied system configurations and package status.
