# Offline Profile Manager Demo

This is a starter Android Studio project for an offline local profile-record manager.

## Features
- Add, edit, and delete profile records
- Choose a platform label (Facebook Page, Instagram, LinkedIn, TikTok, Other)
- Save records locally using Android SharedPreferences
- Works offline after installed
- No internet permission and no external service connection

## Important
This demo does **not** create real social-media accounts, sign in to platforms, or bypass platform rules. It only stores local notes about profiles.

## Build an APK
1. Install Android Studio on a computer.
2. Open this folder as an existing project.
3. Allow Gradle to download the Android Gradle Plugin and Kotlin plugin (first build requires internet unless already cached).
4. Choose **Build > Build APK(s)**.
5. The debug APK is normally placed at `app/build/outputs/apk/debug/app-debug.apk`.
6. Transfer that APK to your Android phone, open it, and allow installation from that file source if Android asks.

The source project itself is not an APK. This environment did not have Android SDK/Gradle build tools available to compile it here.
