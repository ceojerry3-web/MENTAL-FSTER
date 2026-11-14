# FloatDeck — Complete Android Floating Window Recent Tasks Project

Synced with your configuration:
- Trigger Style: bubble
- Overlay Layout: list
- Panel Opacity: 96%
- Bubble Size: 60dp
- Edge Snapping: Enabled
- Max Recent Tasks: 8
- Freeform Mini-Window Launch: Enabled

## Option 1: Build an Installable APK via Android Studio (Local)
1. Unzip this folder and open it in **Android Studio Ladybug (or newer)**.
2. Wait for Gradle Sync to finish (all dependencies, adaptive icons, and themes are included).
3. Click **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Copy `app/build/outputs/apk/debug/app-debug.apk` to your Android phone and tap it to install.

## Option 2: Build an Installable APK in the Cloud (No Android Studio Required)
1. Create a new GitHub repository and upload all files from this ZIP (including `.github/workflows/build-apk.yml`).
2. Open the **Actions** tab in GitHub and run **Build FloatDeck Android APK**.
3. Download the `FloatDeck-debug-apk` artifact and install `app-debug.apk` on your Android device.

## First-Run Android Setup
1. Open **FloatDeck Recents** on your phone.
2. Tap **Grant Display Over Other Apps** and allow FloatDeck.
3. Tap **Grant Usage Access** and allow FloatDeck.
4. Tap **Start Floating Recent Window**.
