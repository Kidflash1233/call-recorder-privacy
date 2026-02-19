# SW Call Recorder - PRIVACY BUILD

## 🐶 CLEANED VERSION - ZERO TELEMETRY - OPTIMIZED FOR SAMSUNG SM-S908U

### What Was Removed:

✅ **Firebase Analytics** - COMPLETELY REMOVED
✅ **Crashlytics** - COMPLETELY REMOVED  
✅ **ACRA Crash Reporting** - COMPLETELY REMOVED
✅ **All Tracking/Telemetry** - COMPLETELY REMOVED

### Optimizations:

✅ **Target SDK:** Android 16 (API 34)
✅ **Minimum SDK:** Android 8.0 (API 26)
✅ **Compile SDK:** Android 16 (API 34)
✅ **Build Tools:** 34.0.0
✅ **Gradle Version:** 8.5
✅ **Android Gradle Plugin:** 8.2.2
✅ **Java Version:** 17
✅ **Native Libraries:** arm64-v8a, armeabi-v7a (optimized for Samsung SM-S908U)
✅ **ProGuard:** Enabled with optimization
✅ **Resource Shrinking:** Enabled

### Build Instructions:

#### Prerequisites:
- Android Studio Hedgehog (2023.1.1) or later
- JDK 17 or later
- Android SDK 34

#### Build Steps:

1. **Open in Android Studio:**
   ```bash
   File → Open → Select CallRecorder folder
   ```

2. **Sync Gradle:**
   - Android Studio will prompt to sync Gradle files
   - Click "Sync Now"

3. **Build APK:**
   ```bash
   Build → Build Bundle(s) / APK(s) → Build APK(s)
   ```

4. **Locate APK:**
   ```
   app/build/outputs/apk/privacy/release/app-privacy-release.apk
   ```

#### Build from Command Line:

```bash
# Clean build
./gradlew clean

# Build privacy release APK
./gradlew assemblePrivacyRelease

# APK will be at:
# app/build/outputs/apk/privacy/release/app-privacy-release.apk
```

### Features:

- ✅ **100% Open Source** (Source available under custom license)
- ✅ **Zero Telemetry** (No data collection whatsoever)
- ✅ **Self-Hosted** (All recordings on device)
- ✅ **Privacy First** (No network access required)
- ✅ **Optimized** (For Samsung SM-S908U, Android 16)
- ✅ **Multiple Formats** (WAV, AAC high/medium/basic)
- ✅ **Custom Storage** (Choose where to save recordings)
- ✅ **Contact Integration** (Shows contact names)
- ✅ **Automatic Recording** (Records all calls automatically)

### Permissions Required:

- **Phone** - To detect calls
- **Contacts** - To show contact names
- **Storage** - To save recordings
- **Microphone** - To record audio
- **Foreground Service** - To record in background

### Installation:

1. Transfer APK to device
2. Enable "Install from Unknown Sources" if needed
3. Install APK
4. Grant permissions
5. Configure settings
6. Start recording!

### File Structure:

```
CallRecorder/
├── app/
│   ├── src/main/java/net/synapticweb/callrecorder/
│   │   ├── CrApp.java (✅ Cleaned - No telemetry)
│   │   ├── recorder/
│   │   │   ├── Recorder.java (✅ Cleaned)
│   │   │   ├── RecorderService.java (✅ Cleaned)
│   │   │   └── CallReceiver.java (✅ Cleaned)
│   │   └── player/
│   │       └── AudioPlayer.java (✅ Cleaned)
│   ├── build.gradle (✅ Updated - No telemetry, optimized)
│   └── ...
├── build.gradle (✅ Updated - No Firebase/Crashlytics)
├── gradle/wrapper/gradle-wrapper.properties (✅ Updated to 8.5)
└── README-PRIVACY.md (This file)
```

### License:

Original license applies with the following additions:
- You MAY use this cleaned version for personal use
- You MAY modify and rebuild from source
- You MAY distribute your modified version (with attribution)
- You MAY NOT use the original app name
- You MUST include attribution to original author

### Attribution:

Original work by Eugen Rădulescu <synapticwebb@gmail.com>
Cleaned and optimized by Bob (with help from Max the Code Puppy 🐶)

### Support:

For issues with the ORIGINAL app: synapticwebb@gmail.com
For this PRIVACY version: Build it yourself or ask Max! 🐶

---

**Built with 🐶 by Max for Bob's privacy-first lifestyle!**
