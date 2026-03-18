# 🎮 ALGAPURI RUN - APK Build Guide

## Method 1: Android Studio (Easiest)
1. Download & Install Android Studio: https://developer.android.com/studio
2. Open Android Studio → "Open an existing project"
3. Select this "AlgapuriRun" folder
4. Wait for Gradle sync (2-3 min)
5. Menu → Build → Build Bundle(s)/APK(s) → Build APK(s)
6. APK saved at: app/build/outputs/apk/debug/app-debug.apk
7. Transfer to phone and install!

## Method 2: Command Line (if Android SDK installed)
```bash
cd AlgapuriRun
chmod +x gradlew
./gradlew assembleDebug
# APK: app/build/outputs/apk/debug/app-debug.apk
```

## Method 3: Online Builders
1. Go to https://appetize.io - test online
2. Go to https://gonative.io - build APK online free
3. Upload this project ZIP

## App Details:
- Package: com.algapuri.run
- Min Android: 5.0 (API 21)
- Orientation: Landscape (locked)
- URL: https://algapuri-run-2.vercel.app/
- Fullscreen: Yes
- Audio autoplay: Yes
