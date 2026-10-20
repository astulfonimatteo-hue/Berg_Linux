# BergOS Roadmap

BergOS is developed incrementally, with each release introducing new features, improving reliability, and expanding the project's capabilities.

The roadmap represents planned milestones and may evolve as development progresses.

---

## v0.1 — Minimal Core
- Minimal **KDE Neon-based** system with KDE Plasma.
- Essential desktop components and system utilities.
- Functional live environment.
- Initial boot and compatibility testing.

*Recommended usage: Run BergOS v0.1 in a virtual machine. This release is intended for development and testing, not as a production-ready operating system.*

---

## v0.2 — BergOS Branding
- BergOS wallpapers, themes, icons, and color palette.
- Initial desktop branding.
- Consistent visual identity for the Standard edition.

---

## v0.3 — BergOS Lite Release & Base Refinement
- **Introduce BergOS Lite:** Release the first lightweight 64-bit edition based on XFCE.
- Optimize storage and memory utilization for low-resource 64-bit PCs.
- Configure user accounts and system defaults across Standard and Lite editions.
- Test live environments and installation workflows on physical hardware and virtual machines.

---

## v0.4 — BergOS Software Selection
- Introduce the modular software selection system.
- Desktop Applications profile.
- Development Tools profile.
- Gaming profile.
- Cybersecurity Toolkit profile.
- Virtualization & Containers profile.
- Networking Tools profile.
- System Administration profile.
- Multimedia Tools profile.
- Integrate APT and Flatpak where appropriate.

*Users will be able to select optional software categories without including every application in the base ISO.*

---

## v0.5 — BergOS Adaptive Setup
- Detect hardware during the first boot.
- Apply hardware-appropriate desktop and system defaults.
- Adapt selected settings to available system resources.
- Provide optional software and configuration recommendations.
- Implement safe fallbacks for unsupported or unknown hardware.

*Adaptive Setup will improve the initial experience while avoiding risky automatic changes.*

---

## v0.6 — BergOS Retro Release
- **Introduce BergOS Retro:** Release the dedicated 32-bit (`i386`) edition based on Debian 12 (Bookworm).
- Integrate an ultra-lightweight desktop environment (LXDE / IceWM) tuned for legacy hardware and systems with **512 MB of RAM**.
- Reduce unnecessary background services for vintage processors.
- Maintain consistent BergOS branding and identity across all three editions (Standard, Lite, Retro).
- Improve the reliability of Adaptive Setup on legacy components.

---

## v0.7 — Custom BergOS Desktop
- Introduce a customized KDE Plasma experience for Standard.
- Configure a distinctive panel, launcher, and desktop layout.
- Integrate custom themes, icons, and visual components.
- Refine defaults for everyday productivity.
- Integrate the BergOS visual identity throughout the desktop.

---

## v0.8 — BergOS Server
- Introduce a dedicated Server edition.
- Provide a minimal, headless installation.
- Configure SSH and networking options.
- Introduce optional server roles and administration tools.
- Minimize unnecessary graphical components and services.
- Document security and maintenance procedures.

---

## v0.9 — Custom BergOS Installer
- Develop a BergOS-branded installation experience.
- Streamline the installation workflow.
- Provide edition-aware installation options.
- Integrate BergOS configuration principles.
- Improve installation guidance and error handling.

---

## v0.10 — BergOS System Profiles
- Introduce persistent software profile management.
- Display installed BergOS components and optional toolsets.
- Allow users to review and modify supported configuration choices.
- Detect missing or partially installed profile components.
- Integrate System Profiles with Software Selection.
- Integrate supported settings from Adaptive Setup.
- Provide clear reports of configuration changes and installation results.

*System Profiles will help users understand, maintain, and customize their systems beyond the first boot.*

---

*Note: All roadmap items are planned features and may change based on development progress, testing results, hardware compatibility, and maintenance requirements.*


BergOS — One project. Four editions. More life for every computer.
