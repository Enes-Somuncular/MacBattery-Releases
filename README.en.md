<p align="right"><a href="README.md">Türkçe</a> · <strong>English</strong></p>

<div align="center">
<img src="site/assets/logo.svg" width="86" height="86" alt="Wattelier mark" />

# wattelier
### Power, clarified.

**See beyond the battery percentage.**  
Understand your Mac's power flow, battery health and app activity at a glance.

<img src="site/assets/hero.svg" width="100%" alt="Wattelier power insights — illustrated product preview" />

[Download](#-download-for-mac) · [Features](#-built-for-clarity) · [Install](#-install-in-three-steps) · [Beta](#-beta-channel)
</div>

---

## ⬇️ Download for Mac

> **Meet Wattelier.** During the brand transition, the app and DMG files retain the technical **MacBattery** name, so existing installations keep working.

<!-- DOWNLOADS:START -->
| **✦ Stable · 1.4.1** | **◇ Beta · 1.4.1-beta.2** |
| :---: | :---: |
| Recommended for everyday use | Early access and testing |
| **[↓ Download stable DMG](https://github.com/Enes-Somuncular/MacBattery-Releases/releases/download/v1.4.1/MacBattery-1.4.1.dmg)** | **[↓ Download beta DMG](https://github.com/Enes-Somuncular/MacBattery-Releases/releases/download/v1.4.1-beta.2/MacBattery-1.4.1-beta.2.dmg)** |
| [Release notes](https://github.com/Enes-Somuncular/MacBattery-Releases/releases/tag/v1.4.1) · [SHA256](https://github.com/Enes-Somuncular/MacBattery-Releases/releases/download/v1.4.1/SHA256SUMS) | [Beta notes](https://github.com/Enes-Somuncular/MacBattery-Releases/releases/tag/v1.4.1-beta.2) · [SHA256](https://github.com/Enes-Somuncular/MacBattery-Releases/releases/download/v1.4.1-beta.2/SHA256SUMS) |
<!-- DOWNLOADS:END -->

[Browse all releases →](https://github.com/Enes-Somuncular/MacBattery-Releases/releases)

**Requirements:** Apple Silicon MacBook · macOS 13+ · no Intel build. The app currently has an **ad-hoc signature**, not an Apple Developer ID signature or Apple notarization, so macOS may request additional approval. [Safe installation guide →](docs/INSTALL.md#english)

## ✨ Built for clarity

| Feature | What it does |
| --- | --- |
| **⚡ Power flow** | Adapter input, battery charging and estimated system power. |
| **📈 Power history** | Short-term 30/60-second trends and inspection. |
| **◉ Battery health** | Level, capacity, cycle count and charge state. |
| **⌘ App activity** | CPU, RAM and **estimated** per-app energy usage. |
| **◷ Battery journal** | Daily and weekly observed usage and local battery history. |
| **🛡 Battery protection** | Optional alerts and Apple's charge-limit Shortcut on supported Macs. |
| **⟳ Updates** | Separate stable and beta channels with signed updates. |

**Transparency:** Power distribution, per-app Watt numbers and journal energy figures may be estimates, not direct hardware meter readings. Charge time may be unavailable when macOS does not provide reliable data.

## ◇ App previews

| Dark overview | App activity |
| :---: | :---: |
| <img src="assets/screenshots/overview-dark.png" width="370" alt="Dark overview panel with battery and power flow" /> | <img src="assets/screenshots/applications.png" width="370" alt="App activity view" /> |

<sub>Images show the previous stable 1.3.0 UI with sample data; details may differ in 1.4.1.</sub>

## 📦 Install in three steps

1. Download the **stable DMG** above and open it.
2. Drag **MacBattery.app** into **Applications**.
3. Launch the installed app from Applications and open it from the menu bar.

[Installation and macOS security notes](docs/INSTALL.md#english) · [Report an issue](https://github.com/Enes-Somuncular/MacBattery-Releases/issues/new/choose)

## ◇ Beta channel

Enable **Ayarlar → Güncellemeler → Beta güncellemelerini al** in the Turkish app interface to opt into beta updates. Disabling beta updates does not automatically downgrade an installed beta.

<details><summary><strong>See the beta previews</strong></summary>

<img src="assets/beta/menu-bar.png" width="860" alt="Beta menu bar designs" />
<img src="assets/beta/battery-journal.png" width="370" alt="Beta battery journal preview" />
</details>

## 🔐 Privacy and distribution

The app does not upload battery readings or running-app lists to a server. Updates and downloads use GitHub; battery-journal records stay local. Ed25519 update signatures do **not** replace Apple notarization.

This repository hosts public **downloads and product documentation only**; app source code remains private. GitHub's auto-generated **Source code (zip/tar.gz)** assets are not installers. Use the DMG.

---

<div align="center">

[Website source](site/index.html) · [All releases](https://github.com/Enes-Somuncular/MacBattery-Releases/releases) · [FAQ (Türkçe)](docs/FAQ.md) · [Brand guide](docs/BRAND.md) · [Issues](https://github.com/Enes-Somuncular/MacBattery-Releases/issues/new/choose)

<sub>Wattelier · Power, clarified. · Enes Somuncular</sub>
</div>
