# Smalix Mobile — Android starter project

This is a starter Android Studio/Gradle project for the Smalix Mobile APK-tooling app.

## Included in this starter
- Native Android Kotlin app shell
- APK file picker
- Basic APK metadata inspection (package name, version, min SDK when available)
- Clean UI prepared for future Smali/XML editing and build/sign workflows

## Important limitations
This starter is **not yet a full APK decompiler/editor**. It does not yet include JADX, Apktool, Smali editing, APK rebuild, or signing engines. Those need to be integrated and tested separately. Apktool's standard Java runtime is not officially supported directly on Android, so on-device integration requires a compatible implementation or a remote/build environment.

## Build
Open this project in Android Studio or another compatible Gradle Android environment, allow Gradle sync, then build the `app` module.
- Android Gradle Plugin: 8.6.1
- Gradle: 8.7
- Kotlin: 2.0.21
- Minimum SDK: 26 (Android 8.0)
- Target SDK: 35

Package: `com.smalix.mobile`
