# 📱 Codiology AppStore - v1.0.0 Official Release

![Version](https://img.shields.io/badge/Version-1.0.0-007AFF?style=for-the-badge&logo=android)
![Build](https://img.shields.io/badge/Build-100-34C759?style=for-the-badge&logo=googleplay)
![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-0A84FF?style=for-the-badge&logo=android)
![Developer](https://img.shields.io/badge/Developer-Shahriar%20Ahmed%20Riaz-FF9500?style=for-the-badge)
![License](https://img.shields.io/badge/Copyright-%C2%A9%202026%20Codiology%20Labs-AF52DE?style=for-the-badge)

---

## 🌟 Overview
**Codiology AppStore** is a next-generation, high-performance, and privacy-focused Android marketplace designed with Apple's **iOS App Store Human Interface Guidelines**. Discover, download, update, and manage your favorite Android apps and games seamlessly with real-time Firebase syncing, in-app Google Play Store style downloading, and dynamic updates management!

---

## 📊 App Specifications

| Specification | Details |
| :--- | :--- |
| **App Name** | Codiology AppStore |
| **Package Name** | `com.codiology.appstore` |
| **Version Name** | `1.0.0` |
| **Version Code** | `100` |
| **Target Tag** | `v1.0.0` |
| **APK Size** | `~12.5 MB` |
| **Min Compatibility** | Android 8.0 (Oreo) or higher (`API 26+`) |
| **Language Support** | English (Global) |
| **Age Rating** | 3+ (Everyone) |
| **Lead Developer** | **Shahriar Ahmed Riaz** |
| **Copyright** | © 2026 Codiology Labs. All rights reserved. |

---

## ✨ What's New in v1.0.0 (Change Log)

### 🎨 User Interface & Experience Redesign
- 🍎 **iOS App Store UI Alignment**: Sleek card layouts, floating navigation tabs, and smooth activity transitions.
- 🖼️ **Dynamic Flexible Preview Screenshots**: Automatic 15px rounded corner screenshot rendering supporting both **Portrait (9:16)** and **Landscape (16:9)** uncropped aspect ratios.
- 🌗 **Adaptive Dark & Light Themes**: Real-time theme switching with full dark mode optimization.
- ⚡ **Skeleton Loading Animations**: Pulsing skeleton loaders on initial database fetch across all tabs.
- 😔 **Centered Sad Emoji Empty States**: Friendly, centered SVG empty state indicators when no apps or search results match.

### ⚙️ Core Engine & In-App Lifecycle
- ⬇️ **In-App Download & Progress Engine**: Real-time percentage progress (`Downloading 45%`) with reduced opacity UI indicators.
- 🔄 **Smart Package & Version Manager**: 4-tier package detection system supporting `OPEN`, `UPDATE` (soft yellow indicator), and `INSTALL` states.
- 🗑️ **In-App Uninstallation**: Direct uninstallation trigger next to the `OPEN` button for installed apps.
- 📜 **Interactive Expandable Sections**: "see more" / "see less" toggles for Description and What's New sections.
- 🗂️ **Version History Bottom Sheet**: Interactive iOS-style bottom sheet displaying current and past release logs.

---

## 🔄 Version Evolution (Before vs Now)

| Feature | Legacy Alpha | v1.0.0 Official Release 🚀 |
| :--- | :---: | :---: |
| **App Lifecycle** | Basic External Intent | Full In-App Progress, Install, Update & Uninstall |
| **Database Sync** | Static Dummy Fallback | Real-time Firebase Firestore Resilient Engine |
| **Package Visibility** | Android 11+ Restricted | Multi-tier `<queries>` & Package Discovery |
| **Screenshots Display** | Fixed Cropped Square | Flexible Uncropped Aspect Ratio (15px Curved) |
| **Banner Engine** | Static Banners | Admin-driven Hero Banner & App Icon Sync |
| **Version History** | Single View | Interactive Bottom Sheet Cards |

---

## 📱 Screenshots & Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/ahmed-shahriar04/reelx/main/Assets/Home.jpeg" width="30%" alt="Home Tab" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/ahmed-shahriar04/reelx/main/Assets/VideoPlayer.jpeg" width="30%" alt="App Details" />
</p>

---

## 📥 Download APK

Directly download the compiled release APK for **Codiology AppStore v1.0.0**:

- 📦 **[Download Codiology-AppStore-v1.0.0.apk](https://github.com/ahmed-shahriar04/AppStore/releases/download/v1.0.0/AppStore-v1.0.0.apk)** *(Size: ~12.5 MB)*

---

## 🔒 Permissions Requested & Safety

- 🌐 **Internet & Network State**: To fetch real-time catalog data from Firebase Firestore.
- 📦 **Request Install Packages**: To download and install/update APK files directly.
- 🔔 **Post Notifications**: To alert you when new updates and releases are available.
- 🔍 **Query All Packages**: To detect installed apps on your device for `OPEN`/`UPDATE` status.

---

## 👨‍💻 Author & Credits

Developed with ❤️ by **Shahriar Ahmed Riaz**

- **GitHub**: [@ahmed-shahriar04](https://github.com/ahmed-shahriar04)
- **Organization**: Codiology Ecosystem / Codiology Labs
- **Copyright**: © 2026 Codiology Labs. All rights reserved.

---
