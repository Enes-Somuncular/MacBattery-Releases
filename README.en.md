<p align="right"><a href="README.md">Türkçe</a> · <strong>English</strong></p>

<div align="center">

<img src="site/assets/logo.svg" width="86" height="86" alt="Wattelier" />

# Wattelier

**Power, clarified. · See beyond the battery percentage.**

Where does your Mac’s energy go? Follow its charge, power flow and app activity from the menu bar.

**[↓ Download Wattelier 1.6.0](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/download/v1.6.0/Wattelier-1.6.0.dmg)** · [Release notes](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/tag/v1.6.0) · [All releases](https://github.com/Enes-Somuncular/Wattelier-Releases/releases)

Apple Silicon · macOS 13+ · Turkish app interface · Light and dark appearance

</div>

## Clearer energy insights in 1.6.0

**Overview → Analysis → Protection.** Three focused sections: the essentials at a glance, with details when you need them.

| Overview | Unified Analysis |
| :---: | :---: |
| <img src="assets/screenshots/wattelier-1.6.0-overview-dark.png" width="360" alt="Wattelier 1.6.0 circular battery gauge and electrical power flow" /> | <img src="assets/screenshots/wattelier-1.6.0-analysis-dark.png" width="360" alt="Wattelier 1.6.0 shared daily battery and app-energy summary" /> |

<sub>Actual 1.6.0 interface rendered with sample data.</sub>

### See power in motion

An electrical path flows from the adapter to your Mac and, when charging, branches toward the battery. Amber represents system consumption; teal represents battery charging. The battery branch stays dim when full or paused; battery operation uses a single path. Adapter capacity and estimated live input appear separately.

Card transitions, a sliding tab selection and short interaction animations bring the interface to life. macOS **Reduce Motion** is respected, and electrical animation stops when the popover closes.

### Apps and history, together

| Section | What you can see |
| --- | --- |
| **Overview / Genel bakış** | Battery level, charge state, time estimates, power distribution, health and cycle count. |
| **Analysis / Analiz · Live / Anlık** | Running apps, CPU, RAM and estimated Watts; search, sorting and 30/60-second power charts. |
| **Analysis / Analiz · History / Geçmiş** | A shared **Today / Last 7 days** range, battery-use summary, estimated app energy (Wh), app comparisons and the detailed battery journal. |
| **Protection / Koruma** | Charge-target and low-battery reminders, plus Apple’s charge-limit Shortcut on supported systems, run only when you press the button. |

### Alerts when useful, without repeated full-charge reminders

Full-charge alerts wait for macOS to report actual completion. Launching while already full stays quiet. Suppression survives restarts and preference changes; a new full-charge alert requires the battery to first fall to **95% or below**. Use **Test bildirimi gönder** in Protection to check notifications.

## Download and install

1. Download and open **[Wattelier 1.6.0 DMG](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/download/v1.6.0/Wattelier-1.6.0.dmg)**.
2. Drag Wattelier into **Applications**.
3. Open the installed app and click its battery icon in the menu bar.

**Already installed?** Choose **Güncellemeleri Denetle** in the app. Beta 3 users are also offered stable 1.6.0. Select **Ayarlar → Güncellemeler → Kararlı** for the stable channel.

[ZIP archive](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/download/v1.6.0/Wattelier-1.6.0.zip) · [SHA256 checksums](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/download/v1.6.0/SHA256SUMS) · [Installation guide](docs/INSTALL.md#english) · [Report an issue](https://github.com/Enes-Somuncular/Wattelier-Releases/issues/new/choose)

**Requirements:** Apple Silicon MacBook, macOS 13 or later. No Intel build. The app is ad-hoc signed, without Apple Developer ID signing or notarization yet. macOS may require first-launch approval; see the installation guide.

## Your records stay on your Mac

- Battery and app history are stored locally for up to **30 days**.
- App-history recording is **off by default**. Enable it, pause it or delete its records whenever you choose.
- Battery readings and running-app lists are not uploaded. Update checks and downloads use GitHub.
- Watt and Wh figures are **estimates**. App energy is modeled from CPU share; GPU, display and all background activity cannot be attributed precisely. Missing measurements and sleep are not counted as observed usage.
- A charge-reminder target is not a charging limit. The Apple Shortcut runs only when you initiate it; Wattelier does not read the current system charge limit.

## Beta channel and existing installations

Choose **Ayarlar → Güncellemeler → Beta** to receive future preview builds. Stable 1.6.0 rebuilds the approved Beta 3 code with stable metadata; earlier betas remain in the [release archive](https://github.com/Enes-Somuncular/Wattelier-Releases/releases). Turning off beta updates does not automatically downgrade an installed version.

The visible product name is **Wattelier**. The internal **MacBattery.app** path and application identifier are retained to preserve existing MacBattery preferences, history and Sparkle updates. New downloads use **Wattelier-VERSION.dmg / .zip**; old downloads remain available.

This repository hosts **downloads and product documentation**; application source code remains private. GitHub’s automatic **Source code (zip/tar.gz)** files are not installers. Use the DMG or application ZIP.

---

<div align="center">

[Latest stable release](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/latest) · [FAQ (Türkçe)](docs/FAQ.md) · [Brand guide](docs/BRAND.md) · [Feedback](https://github.com/Enes-Somuncular/Wattelier-Releases/issues/new/choose)

<sub>Wattelier · Power, clarified. · Enes Somuncular</sub>

</div>
