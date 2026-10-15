# Infinite Notepad — Android project

A private, offline-first notes app starter for the Infinix Note 30 / Android 14.
Package: `com.johnbosco.infinitenotepad`

## Features in this starter
- Full-screen lock screen with Android system biometric authentication
- Local note storage and autosave
- Note title/body editing, note list, and manual lock
- Screenshot blocking while the app is open (`FLAG_SECURE`)
- No internet permission and no separate app password

## Important limitations
- This is Android source code, not a compiled APK.
- Android system biometric UI may include system-managed fallback behavior; apps cannot override the phone's security rules.
- Test the project on a real device with a fingerprint enrolled.
- This starter uses Android's platform biometric prompt; for broader compatibility, migrate to AndroidX Biometric in Android Studio.
- Before publishing or relying on it for highly sensitive notes, have the code reviewed and test backup/restore, deletion, and device security thoroughly.

## Build APK
1. Install Android Studio on a computer.
2. Open this folder as an existing Gradle project.
3. Let Gradle sync and install Android SDK 35 if prompted.
4. Connect your Infinix Note 30 with USB debugging enabled, or use Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Debug APK output is typically `app/build/outputs/apk/debug/app-debug.apk`.
6. Transfer the APK to your phone and install it. Android may ask permission to install from that source.

## Fingerprint setup
On your phone, go to Settings > Security (menu names can vary) and register a fingerprint first.
