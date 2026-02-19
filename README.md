# Privacy Call Recorder

> **100% Clean Build - Zero Telemetry - Self-Hosted**

[![Build APK](https://github.com/YOUR_USERNAME/YOUR_REPO/actions/workflows/build.yml/badge.svg)](https://github.com/YOUR_USERNAME/YOUR_REPO/actions/workflows/build.yml)

## 🐶 What is this?

A **privacy-first, self-hosted call recorder** for Android - forked from SW Call Recorder with **ALL telemetry removed**.

## ✨ Features

- ✅ **100% Open Source** - Source available under custom license
- ✅ **Zero Telemetry** - No Firebase, Crashlytics, or ACRA
- ✅ **Self-Hosted** - All recordings stored locally on device
- ✅ **Privacy First** - No network access required
- ✅ **Multiple Formats** - WAV, AAC (high/medium/basic)
- ✅ **Custom Storage** - Choose where to save recordings
- ✅ **Contact Integration** - Shows contact names
- ✅ **Automatic Recording** - Records all calls automatically

## 🔒 What Was Removed

| Component | Status |
|-----------|--------|
| **Firebase Analytics** | ❌ REMOVED |
| **Crashlytics** | ❌ REMOVED |
| **ACRA Crash Reporting** | ❌ REMOVED |
| **All Tracking/Telemetry** | ❌ REMOVED |
| **Data Collection** | ❌ REMOVED |

## 📥 Download

### Option 1: Download from Releases

1. Go to [Releases](../../releases)
2. Download the latest APK
3. Install on your device

### Option 2: Download from Artifacts

1. Go to [Actions](../../actions)
2. Click on the latest successful build
3. Scroll down to "Artifacts"
4. Download `call-recorder-privacy-apk`
5. Unzip and install APK

### Option 3: Build Yourself

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# Build with Gradle
./gradlew assemblePrivacyRelease

# APK will be at:
# app/build/outputs/apk/privacy/release/app-privacy-release.apk
```

## 📱 Requirements

- **Android 8.0+** (API 26+)
- **Permissions:**
  - Phone (to detect calls)
  - Contacts (to show contact names)
  - Storage (to save recordings)
  - Microphone (to record audio)
  - Foreground Service (to record in background)

## 🚀 Installation

1. Download APK
2. Enable "Install from Unknown Sources" if prompted
3. Open APK and install
4. Grant required permissions
5. Configure settings (format, storage location, etc.)
6. Start recording!

## 🔧 Building from Source

### Prerequisites

- **Android Studio Hedgehog** (2023.1.1) or later
- **JDK 17** or later
- **Android SDK 34**

### Build Steps

```bash
# 1. Open in Android Studio
File → Open → Select project folder

# 2. Sync Gradle files
Click "Sync Now" when prompted

# 3. Build APK
Build → Build Bundle(s) / APK(s) → Build APK(s)

# 4. Locate APK
app/build/outputs/apk/privacy/release/app-privacy-release.apk
```

### Command Line Build

```bash
# Clean build
./gradlew clean

# Build privacy release APK
./gradlew assemblePrivacyRelease
```

## 📋 Technical Details

| Property | Value |
|----------|-------|
| **App ID** | `net.synapticweb.callrecorder.private.privacy` |
| **Version** | 1.1.4-private-privacy |
| **Min SDK** | Android 8.0 (API 26) |
| **Target SDK** | Android 16 (API 34) |
| **Java Version** | 17 |
| **Native Libraries** | arm64-v8a, armeabi-v7a |

## 📄 License

This project is based on **SW Call Recorder** by Eugen Rădulescu.

### Original License

The original source code is licensed under a custom license by Eugen Rădulescu <synapticwebb@gmail.com>.

You may use, distribute, and modify this code only under the conditions stated in the original license file (`LICENSE.md`).

### Modifications

This fork includes the following modifications:
- Removal of all telemetry components (Firebase, Crashlytics, ACRA)
- Optimization for modern Android devices
- Build configuration updates

### Your Rights

- ✅ Use for personal purposes
- ✅ Modify and rebuild from source
- ✅ Distribute your modified version (with attribution)
- ❌ Cannot use the original app name commercially
- ✅ Must include attribution to original author

## 🙏 Attribution

- **Original Author:** Eugen Rădulescu <synapticwebb@gmail.com>
- **Original Project:** [SW Call Recorder](https://github.com/synapticweb/CallRecorder)
- **Privacy Clean Build:** Forked and modified with ❤️

## 🐶 About This Fork

This fork was created to provide a **truly privacy-first** version of SW Call Recorder by removing all telemetry and tracking components. Perfect for users who want:

- Complete control over their data
- No cloud services or tracking
- Self-hosted, offline-only operation
- 100% transparency in what the app does

## 🤝 Contributing

Contributions are welcome! Please ensure:

1. No telemetry or tracking is added
2. Code follows the existing style
3. All changes are documented
4. License requirements are respected

## 📞 Support

- **Original app issues:** synapticwebb@gmail.com
- **This fork:** Open a GitHub Issue
- **Build problems:** Check the [Actions](../../actions) tab for build logs

## ⚠️ Disclaimer

Call recording laws vary by country and region. Users are responsible for:
- Understanding local laws regarding call recording
- Obtaining necessary consent from parties
- Complying with applicable regulations

This software is provided "as is" without warranty of any kind.

---

**Built with 🐶 for privacy-conscious users everywhere!**
