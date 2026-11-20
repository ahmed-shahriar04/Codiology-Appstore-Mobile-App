# 🚀 Codiology AppStore v1.0.2 - Performance, UI Polish & Feature Expansion Update

# 📱 Codiology AppStore - v1.0.2 Release Notes

![Version](https://img.shields.io/badge/Version-1.0.2-007AFF?style=for-the-badge&logo=android)
![Build](https://img.shields.io/badge/Build-102-34C759?style=for-the-badge&logo=googleplay)
![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-0A84FF?style=for-the-badge&logo=android)
![Developer](https://img.shields.io/badge/Developer-Shahriar%20Ahmed%20Riaz-FF9500?style=for-the-badge)
![License](https://img.shields.io/badge/Copyright-%C2%A9%202026%20Codiology%20Labs-AF52DE?style=for-the-badge)

---

## 🌟 Overview
**Codiology AppStore v1.0.2** introduces a massive overhaul with instant local catalog caching (0s load latency), advanced download pause/resume controls with speed metrics, an interactive App Categories browser, search history with trending chips, a dedicated Notification History Center, and Codiology Protect security verification!

---

## 📊 App Specifications

| Specification | Details |
| :--- | :--- |
| **App Name** | Codiology AppStore |
| **Package Name** | `com.codiology.appstore` |
| **Version Name** | `1.0.2` |
| **Version Code** | `1` |
| **Target Tag** | `v1.0.2` |
| **APK Size** | `~13.2 MB` |
| **Min Compatibility** | Android 8.0 (Oreo) or higher (`API 26+`) |
| **Language Support** | English (Global) |
| **Lead Developer** | **Shahriar Ahmed Riaz** |
| **Copyright** | © 2026 Codiology Labs. All rights reserved. |

---

## ✨ What's New in v1.0.2 (Change Log)

### 📁 Dynamic App Categories
- **Dynamic Category Browser**: Added `CategoriesActivity` and `CategoriesFragment` that dynamically parse and render categories directly from the Firestore database.
- **Theme-Aware Chips**: Redesigned iOS-style category chips supporting dynamic light and dark theme switching.

### ⏸️ Advanced Download Manager & Speed Metrics
- **Pause & Resume Downloads**: Supports instant pause and resume toggle during APK downloads using HTTP Range stream handling.
- **Real-Time Download Speed**: Displays live transfer rates (e.g. `2.5 MB/s`, `850 KB/s`) directly on progress action buttons.
- **Status Bar Progress & Branding**: Real-time status bar download progress with the clean, non-background App Store logo icon (`R.drawable.appstore`).

### ⚡ Instant Local Caching & Zero-Lag Navigation
- **Local Catalog Cache (`CookieSessionManager`)**: Instantaneous (0s) app startup and tab switching by persisting the catalog to local disk.
- **Full-Screen 8-Item Shimmer Skeleton**: Enhanced loading placeholders with left-to-right sweep animations across Home, Apps, Games, Search, and Categories tabs.

### 🛡️ Codiology Protect & Safety Enhancements
- **Verified Safe Badge**: Integrated **"Codiology Protect • Verified Safe"** security card on the app detail page.
- **Battery & Thermal Protection**: Throttled notification updates (1000ms intervals) and 16 KB buffer sizing to prevent CPU overheating and battery drain.
- **Robust Uninstallation (`REQUEST_DELETE_PACKAGES`)**: Smooth native uninstallation dialog with 3-tier fallback resolution.

### 🔍 Search & Notification History
- **Search History & Trending Chips**: Save recent search queries with one-tap clear options alongside interactive trending search chips.
- **Notification History Center**: Added `NotificationHistoryActivity` accessible from Settings with clear-all capabilities and zero dummy entries.

---

## 📥 Download APK

Directly download the compiled release APK for **Codiology AppStore v1.0.2**:

- 📦 **[Download Codiology-AppStore-v1.0.2.apk](https://github.com/ahmed-shahriar04/AppStore/releases/download/v1.0.2/AppStore-v1.0.2.apk)** *(Size: ~13.2 MB)*

---

## 🔒 Permissions Requested

- 🌐 `INTERNET` & `ACCESS_NETWORK_STATE`: Real-time catalog syncing with Firebase Firestore.
- 📦 `REQUEST_INSTALL_PACKAGES` & `REQUEST_DELETE_PACKAGES`: Direct in-app APK installation, updates, and package uninstallation.
- 🔔 `POST_NOTIFICATIONS`: Real-time status bar notifications for updates and download progress.
- 🔍 `QUERY_ALL_PACKAGES`: 4-tier package detection to determine `OPEN` / `UPDATE` status.

---

## 👨‍💻 Author & Credits

Developed with ❤️ by **Shahriar Ahmed Riaz**

- **GitHub**: [@ahmed-shahriar04](https://github.com/ahmed-shahriar04)
- **Organization**: Codiology Ecosystem / Codiology Labs
- **Web App**: [Codiology AppStore Web](https://codiologyappstore.netlify.app/app/codiology-appstore)
- **Copyright**: © 2026 Codiology Labs. All rights reserved.
