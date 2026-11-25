# MotoLog Android — Official Releases 🏍️⚡

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84.svg?style=flat&logo=android)](https://www.android.com/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Release](https://img.shields.io/github/v/release/Imagiyy/MotoLog-Android)](https://github.com/Imagiyy/MotoLog-Android/releases)

**MotoLog** is a modern, high-precision motorcycle ride tracking and cockpit telemetry application built specifically for handlebar mounts and pocket storage. Designed from the ground up for motorcycle riders wearing gloves, MotoLog delivers glanceable telemetry, customizable cockpit dashboards, resilient background tracking, and complete on-device data ownership.

---

## 📥 Downloads & Installation

Get the latest production release from the **[Releases Section](https://github.com/Imagiyy/MotoLog-Android/releases)**:

1. Download **MotoLog.apk** from the latest release.
2. Open the file on your Android device.
3. If prompted, allow installation from unknown sources.
4. Launch **MotoLog** and grant Location / Notification permissions when prompted.

> **Upgrading from v1.0.0?** Back up your rides in **Settings → Backup & Restore** before updating, as v2.0.0 introduces a fresh release signing certificate.

---

## ✨ What's New in v2.0.0

- **Launch Splash & Animated Loading Screen**: Instant branded startup splash and smooth loading transition.
- **Redesigned App Theme & Color Customizer**: 8 one-tap curated cockpit color themes, live cockpit preview with WCAG contrast indicator, inline element tabs (`Text`, `Accent`, `Background`, `Surface`), HSV fine-tuning sliders, and HEX input.
- **Reset Mileage Baseline Option**: Reset a bike's mileage period while optionally continuing from its current odometer as the new baseline for subsequent distance and fuel economy.
- **Remembered Dialog Preferences**: Automatically remembers your chosen checkbox options for Mileage Reset, Fuel Fill-Ups, and GPX Imports.
- **MapLibre Ride Summary & Speed Optimizations**: Real dark vector map ride summaries, smoother route geometry, offloaded startup initialization, and faster reactive Garage/Fuel queries.

---

## 🏁 Key Highlights

- **8 Dynamic Themed Cockpits**:
  - 🏆 **Track Day**: Superbike TFT inspired by MotoGP / WorldSBK with dynamic LED shift-light strip and race telemetry.
  - 🏜️ **Desert Rally**: Dakar-style navigation roadbook and digital rally tripmaster with desert gold accents.
  - ⚡ **Neon Cyber**: High-tech digital HUD with glowing hexagonal tachometer and cyberpunk styling.
  - 🕰️ **Vintage Retro**: Classic 1960s/1970s British Smiths chronometer with mechanical rolling odometer drum.
  - 🎯 **Stealth HUD**: Fighter jet collimator head-up display with pitch ladder, altitude tapes, and pure OLED black.
  - 🏔️ **Adventure Touring**: Rugged dual-pane overland cockpit inspired by BMW GS TFT consoles.
  - ⚙️ **Custom Bobber**: Machined billet aluminum 180° radial arc speedometer with warm parchment dial.
  - 🌌 **Night Cruiser**: Sweeping American V-twin highway dashboard with deep indigo ambient glow.
- **Glanceable Telemetry**: Ultra-high contrast, large typography engineered for rapid scanning at speed.
- **Smart GPS Filtering & Auto-Pause**: Advanced jitter suppression, stationary drift rejection, and spike filtering.
- **Resilient Background Tracking**: Foreground service architecture guarantees uninterrupted tracking even when screen is locked or phone is pocketed.
- **100% On-Device Privacy**: All rides, tracks, and telemetry stay strictly on your device.

---

## 🔒 Permissions & Security

- **Location (Fine & Coarse)**: Used only while actively tracking a ride.
- **Foreground Service**: Keeps GPS recording active while navigating or in pocket.
- **Notifications**: Live ride status and lockscreen quick-controls.
- *Never requested*: Background location (no covert tracking), external server syncing, or analytics tracking.
