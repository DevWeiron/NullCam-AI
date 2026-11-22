# NullCam AI — Android build package

This is a mobile camera app prototype and a cloud workflow that builds an Android debug APK without Android Studio on your phone.

## Current functionality
- Live camera preview (front/rear camera switch)
- Live brightness, contrast and saturation tuning
- Night-style preset
- Capture and save a JPEG
- Flash toggle when the device supports torch control

**Honest status:** this first prototype uses real-time image filters, not a trained neural-network AI model. It does not yet perform true AI denoising, super-resolution or computational multi-frame night photography. Those require a model and device-specific optimization.

## Build APK without Android Studio
1. Create a GitHub repository and upload the contents of this folder.
2. Open the repository's **Actions** tab.
3. Run **Build NullCam AI APK**.
4. Open the completed workflow run and download the `NullCam-AI-debug` artifact.
5. Extract `app-debug.apk` and install it on Android. Allow installs from your file manager if prompted.

The result is a debug APK for testing, not a signed Play Store release.
