# Astral Launcher — Android Studio project

Futuristic companion launcher UI for Minecraft Bedrock on Android.

## What it does
- Sci-fi home screen with animated portal ring and dark neon theme
- Realm selector for Astral Realms, Ember Wilds and Sky Sanctuary
- Home / Profile / Modifications / Settings navigation
- Opens the official Minecraft Bedrock app if it is installed
- Settings toggles and official Minecraft website shortcut

## Important limitations
This is a **companion launcher**, not a replacement Minecraft client. It does not download Minecraft, authenticate Microsoft accounts, install add-ons automatically, or inject code into the game. The realm cards are UI selectors; selecting a realm does not teleport into it. Import the corresponding `.mcaddon` in Minecraft and enable its packs in a world.

The project source has not been built or tested on a physical Android device in this environment.

## Build an APK
1. Install Android Studio (current stable) and Android SDK Platform 35.
2. Open this folder in Android Studio.
3. Allow Gradle to sync and download dependencies.
4. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Debug APK is normally created at `app/build/outputs/apk/debug/app-debug.apk`.

Requirements: JDK 17, Android Gradle Plugin 8.7.3, Kotlin 2.0.21. Internet is needed on the first build to download Gradle/Android dependencies.

Package: `com.astral.launcher`
Minimum Android: 8.0 (API 26)
