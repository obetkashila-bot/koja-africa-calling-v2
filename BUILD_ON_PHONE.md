# KOJA AFRICA Calling V2 — APK Build

This project is configured for the Firebase Android app package `Com.KOJA` and includes `android/app/google-services.json`.

## Build
Use an Android-capable Gradle environment. From the `android` directory run:

`./gradlew assembleDebug`

The debug APK will be at:

`android/app/build/outputs/apk/debug/app-debug.apk`

For a release APK, configure a signing key and run `./gradlew assembleRelease`.

## Important
- Do not upload or commit Firebase Admin service-account private keys.
- The included `google-services.json` is the Firebase client configuration for the Android app.
- Render remains the KOJA web/signaling backend at `https://koja-africa.onrender.com/`.
