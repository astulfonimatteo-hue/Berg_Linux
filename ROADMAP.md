# BergOS Roadmap

BergOS is developed incrementally across two specialized editions: **Standard** and **Lite**. Each milestone introduces foundational core components, expands hardware compatibility, or adds modular features.

*Note: All roadmap items represent planned milestones and may evolve based on community feedback, hardware compatibility, and maintenance requirements.*

---


### [v1.1 — BergOS Lite](https://github.com/astulfonimatteo-hue/BergOS-Lite-Edition/releases/tag/v1.1) 
- **Introduce BergOS Lite:** 64-bit (`x86_64`) lightweight desktop edition based on Debian 13 with XFCE.
- Baseline system architecture, initial boot stability testing, and live ISO environment verification across real hardware and virtual machines.

### [v1.2 — BergOS Standard](https://github.com/astulfonimatteo-hue/BergOS-Standard-Edition/releases/tag/v1.2)
- **Introduce BergOS Standard:** 64-bit (`x86_64`) modern flagship edition based on Debian 13 with KDE Plasma.
- Baseline system architecture, initial boot stability testing, and live ISO environment verification across real hardware and virtual machines.

### v1.3 — BergOS Lite: Modular Software Selection & Adaptive Hardware Configuration

- **BergOS Lite Edition:** Lightweight Arch Linux desktop built on XFCE (X11) and LightDM, focused on efficiency, reduced resource consumption, and hardware compatibility.
- **Branded Calamares Installer:** BergOS-branded installation experience with UEFI/GPT partitioning, GRUB bootloader, and an automatic cleanup step that turns the live image into a regular installed system.
- **Consistent Visual Identity:** Official BergOS logo, wallpapers, LightDM login screen, Fastfetch configuration, and color palette.
- **Modular Software Selection:** Optional post-installation terminal interface allowing users to install categorized application profiles: Desktop Applications, Development Tools, Gaming, Cybersecurity Toolkit, Virtualization & Containers, Networking Tools, System Administration, and Multimedia Tools.
- **Integrated Package Management:** Unified package installation supporting pacman and Flatpak (Flathub preconfigured), with optional AUR support disabled by default and no partial upgrades.
- **Adaptive Hardware Detection:** First-boot detection engine analyzing CPU, RAM, GPU, and machine type, with a JSON report available to other tools.
- **Dynamic System Configuration:** Reversible adjustments to desktop settings and compositor configuration based on detected hardware, with commands to repeat the detection or undo all changes.
- **Intelligent Software Recommendations:** Suggested software profiles based on available RAM, GPU, and disk space, never installed automatically.
- **Hardware Compatibility & Safe Fallbacks:** Alternative configurations for virtual machines, legacy GPUs, and restricted hardware environments.
- **Multilingual Tools:** BergOS tools follow the system language (English and Italian).
- **Release Testing:** Full installation test on virtual machine and real hardware, first-boot hardware profile verification, and published ISO size and checksums.

### v1.4 — BergOS Standard: Enhanced Installation & Full Desktop Experience

- **BergOS Standard Edition:** Complete desktop experience built on KDE Plasma (Wayland) and SDDM, with a lean base system and optional extra software.
- **Branded Calamares Installer:** Customized and BergOS-branded Calamares installation experience, featuring edition-specific configurations.
- **Consistent Visual Identity:** Official BergOS logo, wallpapers selectable from Plasma settings, branded login screen, and Fastfetch configuration.
- **Modular Software Selection:** Optional post-installation software selection framework with the same categorized application profiles.
- **Integrated Package Management:** Unified pacman and Flatpak management with optional AUR support.
- **Adaptive Hardware Configuration:** Hardware detection and reversible desktop adjustments based on available resources, including Plasma animation and blur settings.
- **Hardware Compatibility & Safe Fallbacks:** Alternative configurations for legacy GPUs and restricted hardware environments.
- **Multilingual Tools:** BergOS tools follow the system language (English and Italian).
- **ISO Size Optimization:** Reduce the image to under 1.5 GiB by trimming firmware and fonts.
- **Higher-Resolution Wallpapers:** Replace the current wallpapers with larger versions for high-resolution displays.

### v1.5 — Custom Desktop Experience
- Redesigned KDE Plasma desktop layout for BergOS Standard (custom dock/panel layout, app launcher, and workflow enhancements).
- Fine-tuned XFCE configurations for optimized resource consumption.
- Enhanced default desktop utilities and user-friendly system settings menus.
