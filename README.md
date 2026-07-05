<div align="center">

<img width="600" alt="SysBoost Logo" src="https://github.com/user-attachments/assets/365bac97-5b90-4edd-839e-8aa6e3d3728b" />

# SysBoost

**Android Cleaner & Device Manager**

[![Platform](https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white)](https://developer.android.com)
[![Release](https://img.shields.io/github/v/release/Kirakiller1547/Sysboost?color=blue)](https://github.com/Kirakiller1547/Sysboost/releases/latest)
[![License](https://img.shields.io/github/license/Kirakiller1547/Sysboost)](LICENSE)
[![Min SDK](https://img.shields.io/badge/minSdk-24-orange)](https://developer.android.com/tools/releases/platforms)
[![Downloads](https://img.shields.io/github/downloads/Kirakiller1547/Sysboost/total)](https://github.com/Kirakiller1547/Sysboost/releases)

**📦 [Download the latest release →](https://github.com/Kirakiller1547/Sysboost/releases/tag/V1.0.1)**

</div>

---

## 📖 About

**SysBoost** is an all-in-one Android optimization app designed to help you manage your device efficiently. It keeps your phone organized and lets you monitor its performance with easy-to-use tools — all from a single, clean interface.

## ✨ Features

- 📱 **App Manager** — View, organize, uninstall, or manage installed applications with ease.
- 🧠 **Memory Overview** — Monitor RAM usage and see how your device's memory is being utilized.
- ⚙️ **Task Manager** — Review running tasks and close apps when appropriate to help reduce background activity.
- 💾 **Storage Insights** — Check available storage space and identify files that may be taking up room.
- ℹ️ **Device Information** — Access key details about your phone's hardware, software, battery, and system status.
- 🎨 **Simple & User-Friendly Interface** — Navigate essential device management tools quickly and easily.

SysBoost gives you a convenient overview of your Android device, helping you stay informed about memory, apps, storage, and system performance — all from one place.

> **Note:** Some features may vary depending on your Android version and device manufacturer. Task management capabilities are subject to Android system limitations.

## 📥 Installation

1. Go to the [**Releases page**](https://github.com/Kirakiller1547/Sysboost/releases).
2. Download the latest `.apk` file (currently [**V1.0.1**](https://github.com/Kirakiller1547/Sysboost/releases/tag/V1.0.1)).
3. Enable **Install from unknown sources** on your Android device (Settings → Security).
4. Open the downloaded APK and install it.

## 🖼️ Screenshots

| App Manager | Memory Overview | Storage Insights |
|:---:|:---:|:---:|
| *coming soon* | *coming soon* | *coming soon* |

## 🚀 Getting Started (build from source)

### Prerequisites

- [Android Studio](https://developer.android.com/studio) (Giraffe or newer recommended)
- JDK 17+
- Android SDK with:
  - **Min SDK:** 24 (Android 7.0 Nougat)
  - **Target SDK:** 34 (Android 14)

### Clone the repository

```bash
git clone https://github.com/Kirakiller1547/Sysboost.git
cd Sysboost
```

### Build the project

```bash
./gradlew build
```

### Run on a connected device or emulator

```bash
./gradlew installDebug
```

### Generate a release APK

```bash
./gradlew assembleRelease
```

The signed APK will be located at:

```
app/build/outputs/apk/release/app-release.apk
```

### Generate a release Android App Bundle (for Play Store)

```bash
./gradlew bundleRelease
```

Output location:

```
app/build/outputs/bundle/release/app-release.aab
```

## 🛠️ Tech Stack

- **Language:** Kotlin
- **UI:** Jetpack Compose / XML
- **Architecture:** MVVM
- **Build System:** Gradle (Kotlin DSL)

## 📱 Supported Android Versions

| Android Version | API Level | Supported |
|---|---|---|
| Android 7.0 (Nougat) | 24 | ✅ |
| Android 10 | 29 | ✅ |
| Android 12 | 31 | ✅ |
| Android 14 | 34 | ✅ |

## 🔐 Permissions

SysBoost may request the following permissions to provide its features:

| Permission | Purpose |
|---|---|
| Usage Access / Query All Packages | Required to list and manage installed apps |
| Storage Access | Required to display storage insights |
| Battery/System Stats | Required to display device information |

No personal data is collected, stored, or transmitted off-device. All analysis happens locally on your phone.

## ⚠️ Disclaimer

SysBoost is provided "as is," without warranty of any kind, express or implied. Some system-level actions (such as force-closing apps or clearing certain caches) are limited or restricted by the Android OS depending on version and manufacturer, and results may vary between devices. The developer is not responsible for any data loss, performance issues, or other consequences resulting from use of this application.

## 🤝 Contributing

Contributions are welcome! Please open an issue first to discuss what you'd like to change.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.

## 📬 Contact

Have questions, found a bug, or want to suggest a feature? Open an [issue](https://github.com/Kirakiller1547/Sysboost/issues) or reach out directly.

---

<div align="center">
Made with ❤️ to keep your Android device running smoothly.
</div>
