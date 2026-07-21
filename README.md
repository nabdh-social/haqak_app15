# Hakki Yamani - My Yemeni Right

## Requirements
- Flutter 3.24+
- Dart 3.5+
- Android Studio or VS Code

## What's New in v2 (2026-07-06)
1. **AndroidX Support**: Full AndroidX migration
2. **Updated Dependencies**: All packages updated to latest versions
3. **Fixed intl**: Updated to ^0.20.2
4. **Fixed Gradle**: Updated to 8.2.2 with Java 17
5. **Fixed Kotlin**: Updated to 1.9.22
6. **Memory Leak Fix**: AuthProvider properly cancels listeners
7. **Null Safety**: Added null checks throughout

## Build Instructions

### Step 1: Extract ZIP
```bash
unzip my_yemeni_right_v2.zip
cd my_yemeni_right
```

### Step 2: Install Dependencies
```bash
flutter pub get
```

### Step 3: Build APK
```bash
flutter build apk --release
```

### Output Location
```
build/app/outputs/flutter-apk/app-release.apk
```

## Firebase Setup
1. Add your `google-services.json` to `android/app/`
2. Add your `GoogleService-Info.plist` to `ios/Runner/`

## Features
- Legal encyclopedia with Yemen laws
- Lawyer consultations
- Phone & Email authentication
- RTL Arabic interface
- Dark/Light theme support
