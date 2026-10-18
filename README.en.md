<p align="right"><a href="README.md">Türkçe</a> · <strong>English</strong></p>

# MacBattery

**Your MacBook’s battery, power flow and app consumption — in one menu bar panel.**

Apple Silicon MacBook · macOS 13 or later · Turkish interface

<!-- DOWNLOADS:START -->
<p align="center"><a href="https://github.com/Enes-Somuncular/MacBattery-Releases/releases/download/v1.3.0/MacBattery-1.3.0.dmg"><img src="assets/download-stable-en.svg" alt="Download MacBattery for Mac" width="286"></a></p>
<p align="center"><strong>Stable 1.3.0</strong> · <a href="https://github.com/Enes-Somuncular/MacBattery-Releases/releases/tag/v1.3.0">Release notes</a> · <a href="https://github.com/Enes-Somuncular/MacBattery-Releases/releases/download/v1.3.0/SHA256SUMS">SHA256</a><br><a href="https://github.com/Enes-Somuncular/MacBattery-Releases/releases/download/v1.4.0-beta.2/MacBattery-1.4.0-beta.2.dmg">Try beta · 1.4.0-beta.2</a> — Experimental</p>
<!-- DOWNLOADS:END -->

> Current builds are ad-hoc signed and are **not yet Developer ID signed or notarized by Apple**. macOS may block the first launch. See [installation notes](docs/INSTALL.md#english).

<p align="center"><img src="assets/screenshots/overview-dark.png" alt="MacBattery stable 1.3.0 battery and power dashboard with sample data" width="390"></p>

## In the stable release

- Battery level, charging/runtime estimates, cycle count and capacity information.
- Adapter input, battery charging and estimated Mac power consumption.
- A 30/60-second power timeline with hover inspection.
- Searchable app CPU, memory and estimated energy consumption.
- Optional target/full/low battery notifications.
- Apple’s native 80–100% Charge Limit through a bundled Shortcuts action on supported Macs. Requires Apple silicon and macOS 26.4 or later.
- Signed in-app updates and separate stable/beta channels.

Notification targets are reminders; they do not stop charging. MacBattery does not impose a Watt cap or force battery discharge. Power and app energy figures may be estimates.

## Install

1. Download the stable **DMG** above and open it.
2. Drag **MacBattery** into **Applications**.
3. Launch it from Applications and open the panel from the menu bar.

There is no Intel build. Run the app from Applications, not directly from the mounted DMG. [Installation help](docs/INSTALL.md#english) · [Report an issue](https://github.com/Enes-Somuncular/MacBattery-Releases/issues/new/choose)

## Preview the beta channel

Enable **Ayarlar → Güncellemeler → Beta güncellemelerini al** to receive betas. Disabling the option does not downgrade an installed beta. New features are tested in beta before stable publication.

The **1.4.0 beta series** adds a local Battery Journal with daily/weekly summaries and a redesigned menu bar battery with an embedded percentage and charging badges. Journal data stays on the Mac for up to 30 days; recording can be paused or cleared. Unknown time while the app is closed or the Mac is asleep is not filled in.

<img src="assets/beta/menu-bar.png" alt="Beta menu bar battery designs in light and dark appearances" width="850">

Screenshots are generated from the app with sample data. Stable screenshots show 1.3.0; beta previews are labelled separately.

## Updates, privacy and source availability

Updates are checked every six hours by default and can also be requested manually. Update archives and feeds are verified with Ed25519; these signatures do not replace Apple notarization. GitHub hosts update checks and downloads. MacBattery does not upload battery readings or the app list to a server.

This is the **public distribution repository**, not the application source repository. Application source remains private. GitHub’s automatically generated **Source code (zip/tar.gz)** downloads contain only this distribution repository’s documentation, images and update feed. Install the DMG instead.

[Release history](https://github.com/Enes-Somuncular/MacBattery-Releases/releases) · [FAQ (Türkçe)](docs/FAQ.md)
