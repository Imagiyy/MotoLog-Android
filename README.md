# 🏍️ MotoLog Android

Offline-first motorcycle telemetry, GPS ride tracker, garage logbook, and customizable TFT cockpit application built for handlebar mounts and gloved hands on Android.

[![Release](https://img.shields.io/github/v/release/Imagiyy/MotoLog-Android?style=for-the-badge&color=15803d)](https://github.com/Imagiyy/MotoLog-Android/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Imagiyy/MotoLog-Android/releases)
[![Storage](https://img.shields.io/badge/Data-100%25%20On--Device-0f766e?style=for-the-badge)](#permissions--privacy)
[![License](https://img.shields.io/badge/License-Freeware-475569?style=for-the-badge)](#license--contact)

![MotoLog Telemetry & KMP Architecture](https://github.com/Imagiyy/MotoLog-Android/releases/download/v2.0.0/motolog-hero.png)

---

## ⚡ Quickstart & Downloads

Download the signed APK from [GitHub Releases](https://github.com/Imagiyy/MotoLog-Android/releases) and open it directly on your Android 8.0+ phone:

| Version | Asset | Size | Notes | Download |
| :--- | :--- | ---: | :--- | :--- |
| **`v2.0.0`** *(Latest)* | `MotoLog.apk` | 41.21 MiB | Splash screen, custom color studio, MapLibre vector summaries, mileage reset | [Download v2.0.0](https://github.com/Imagiyy/MotoLog-Android/releases/download/v2.0.0/MotoLog.apk) |
| **`v1.0.0`** | `MotoLog.apk` | 20.23 MiB | Initial production release | [Download v1.0.0](https://github.com/Imagiyy/MotoLog-Android/releases/download/v1.0.0/MotoLog.apk) |

> **Upgrading from `v1.0.0`?** Export a backup in **Settings → Backup & Restore** before uninstalling, as `v2.0.0` uses an updated release signing certificate.

<details>
<summary>🛠️ Installation guide, v2.0.0 changelog, 8 cockpit themes, and SHA-256 checksums</summary>

### Installation
1. Download `MotoLog.apk` on your Android device.
2. Open the downloaded file and allow **Install unknown apps** if prompted.
3. Grant **Location** and **Notifications** permissions when starting your first ride.

### What's New in `v2.0.0`
- **Branded Launch Splash & Theme Studio:** 8 curated cockpit presets, live WCAG contrast checker, per-element tabs (`Text`, `Accent`, `Background`, `Surface`), HSV sliders, and HEX input.
- **Mileage Baseline Resets & Dialog Memory:** Reset bike fuel/distance cycles from current odometer and persist form checkbox preferences.
- **MapLibre Route Summaries:** Vector map summaries with faster Garage and Fuel startup queries.

### 8 Dynamic Cockpit Themes
Track Day · Desert Rally · Neon Cyber · Vintage Retro · Stealth HUD · Adventure Touring · Custom Bobber · Night Cruiser

### Official SHA-256 Checksums
| Release | SHA-256 Digest |
| :--- | :--- |
| `MotoLog.apk` (`v2.0.0`) | `4bdbe122e23b539d20006199119f0e30afd6ac1ff938044f0d2c145098ad314e` |
| `MotoLog.apk` (`v1.0.0`) | `a18cfdd817898a08f61e8321f5242fff13a5b3d0571833200ecae23690e6542e` |

</details>

---

## ✨ Key Features

- **Glanceable Glove-Friendly UI:** High-contrast typography and large (`>= 56dp`) touch targets built for handlebar mounts.
- **Smart GPS Filtering & Auto-Pause:** Suppresses stationary drift and GPS spikes, pauses at stops, and records reliably under lock screen.
- **Garage, Fuel & Maintenance Logs:** Track multiple motorcycles, fuel economy cycles, barometric elevation, and GPX/CSV/ZIP exports.
- **Turn-by-Turn Navigation:** Supports OSRM/Photon or GraphHopper routing with Bluetooth helmet TTS voice prompts.

---

## 🛡️ Permissions & Privacy

- **Used only while riding:** Fine/Coarse Location, Foreground Location Service, and live notification controls.
- **Never collected:** Zero background covert location tracking, zero analytics SDKs, and zero cloud accounts.
- **Release-Only Repository:** This public repository publishes compiled Android releases and user documentation only.

---

## 📄 License & Contact

**Freeware — All Rights Reserved © 2026 [Imagiyy](https://github.com/Imagiyy).**

- **Issues & Feedback:** Open an issue in [Imagiyy/MotoLog-Android/issues](https://github.com/Imagiyy/MotoLog-Android/issues)
- **Direct Contact:** [zuwiabrar@gmail.com](mailto:zuwiabrar@gmail.com)
