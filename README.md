# 📱 Codiology AppStore - v1.0.1 Release Notes

![Version](https://img.shields.io/badge/Version-1.0.1-007AFF?style=for-the-badge&logo=android)
![Build](https://img.shields.io/badge/Build-101-34C759?style=for-the-badge&logo=googleplay)
![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-0A84FF?style=for-the-badge&logo=android)
![Developer](https://img.shields.io/badge/Developer-Shahriar%20Ahmed%20Riaz-FF9500?style=for-the-badge)
![License](https://img.shields.io/badge/Copyright-%C2%A9%202026%20Codiology%20Labs-AF52DE?style=for-the-badge)

---

## 🌟 Overview
**Codiology AppStore v1.0.1** brings a major performance overhaul, interactive step-by-step onboarding, a dedicated **Downloads & Updates Manager**, native system notifications with sound, uncropped dynamic screenshots, persistent dark mode caching, and an improved multi-tier package visibility engine!

---

## 📊 App Specifications

| Specification | Details |
| :--- | :--- |
| **App Name** | Codiology AppStore |
| **Package Name** | `com.lagradost.cloudstream3` |
| **Version Name** | `1.0.1` |
| **Version Code** | `101` |
| **Target Tag** | `v1.0.1` |
| **APK Size** | `~12.8 MB` |
| **Min Compatibility** | Android 8.0 (Oreo) or higher (`API 26+`) |
| **Language Support** | English (Global) |
| **Age Rating** | 3+ (Everyone) |
| **Lead Developer** | **Shahriar Ahmed Riaz** |
| **Copyright** | © 2026 Codiology Labs. All rights reserved. |

---

## ✨ What's New in v1.0.1 (Change Log)

### 🚀 Performance Optimizations & Zero-ANR Engine
- ⚡ **ANR & UI Freeze Elimination**: Removed blocking package manager loop calls from the UI thread. App details and tab switching now open **instantly (1-2ms)**.
- 🖼️ **PostImg & GitHub Fast CDN Sanitizer**: Automatically transforms PostImg webpage URLs (`postimg.cc/...`) into direct fast image streams (`i.postimg.cc/...`).
- 🏎️ **Glide High-Priority Memory Caching**: Optimized image preloading with `DiskCacheStrategy.ALL`, `Priority.HIGH`, and `.dontAnimate()` for instant screenshot rendering.

### ⬇️ Dedicated Downloads & Updates Manager
- 📲 **New Downloads & Updates Page**: Track all available app updates in one dedicated interface (`UpdateAppsActivity`).
- ⚡ **"Update All" Batch Process**: Download and install pending app updates sequentially with a single tap.
- 🔔 **System Notifications with Sound**: Triggers native status-bar update alerts with sound (`RingtoneManager.TYPE_NOTIFICATION`) whenever store updates are available.

### 🎨 Onboarding & UI Enhancements
- 👋 **Interactive 3-Page Onboarding Slider**: Clean welcome flow featuring high-resolution transparent app branding (`appstore.png`).
- 🔒 **Non-Blocking Permission Flow**: Optional, step-by-step permission setup (`Grant Install Permission` ➔ `Granted • Continue` ➔ `Get Started`).
- 📐 **Flexible Preview Screenshots**: 100% uncropped aspect ratio rendering with 15px rounded corners, seamlessly supporting both **Portrait (9:16)** and **Landscape (16:9)** screenshots.
- 🎯 **Firestore Banner Screen Filtering**: Banners now dynamically render based on admin placement flags (`showOnHome`, `showOnApps`, `showOnGames`).

### 🌗 Dark Mode & System Enhancements
- 🌙 **Persistent Dark Mode Engine**: Dark mode preferences are saved to disk (`SharedPreferences`) and applied during process startup via `AppStoreApplication`.
- 🔁 **Recreation Bugfix**: Resolved fragment state loss and bottom navigation unresponsiveness upon theme switching.
- 🔙 **Smart Back Button Handling**: Pressing the back button returns to the Home tab before prompting a custom exit warning dialog (`dialog_warning.xml`).
- 🏷️ **Dynamic Version Display**: Dynamically reads `versionName` (`1.0.1`) from `build.gradle` across Splash and About screens.
- 📤 **Native Share Sheet**: Integrated system share sheet featuring app invite text and download URL (`https://codiologyappstore.netlify.app/app/codiology-appstore`).

---

## 📥 Download APK

Directly download the compiled release APK for **Codiology AppStore v1.0.1**:

- 📦 **[Download Codiology-AppStore-v1.0.1.apk](https://github.com/ahmed-shahriar04/AppStore/releases/download/v1.0.1/AppStore-v1.0.1.apk)** *(Size: ~13 MB)*

---

## 🔒 Permissions Requested

- 🌐 `INTERNET` & `ACCESS_NETWORK_STATE`: Real-time catalog syncing with Firebase Firestore.
- 📦 `REQUEST_INSTALL_PACKAGES`: Direct in-app APK installation and app updates.
- 🔔 `POST_NOTIFICATIONS`: System notifications with sound for pending app updates.
- 🔍 `QUERY_ALL_PACKAGES`: Multi-tier package detection to determine `OPEN` / `UPDATE` status.

---

## 👨‍💻 Author & Credits

Developed with ❤️ by **Shahriar Ahmed Riaz**

- **GitHub**: [@ahmed-shahriar04](https://github.com/ahmed-shahriar04)
- **Organization**: Codiology Ecosystem / Codiology Labs
- **Web App**: [Codiology AppStore Web](https://codiologyappstore.netlify.app/app/codiology-appstore)
- **Copyright**: © 2026 Codiology Labs. All rights reserved.
