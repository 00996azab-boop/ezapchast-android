# E-Zapchast Android

Android WebView application for https://ezapchast.com/

## Build in Android Studio
1. Install Android Studio (latest stable).
2. Open this folder as a project.
3. Let Gradle sync and install Android SDK 35 if requested.
4. Run `app` on a phone/emulator.
5. For APK: Build → Build Bundle(s) / APK(s) → Build APK(s).

Debug APK output: `app/build/outputs/apk/debug/app-debug.apk`

## Features
- E-Zapchast website inside Android app
- Android back button navigates web history
- Login/session cookies preserved
- File upload support for photos/documents
- Location permission for nearby shops/СТО
- Camera permission for web camera features
- External links open in appropriate Android apps/browser
- Portrait mode
- GitHub Actions workflow included for automatic APK build
