# OPIC Now releases

This public repository contains only the Android APK release assets and the `version.json` manifest used by OPIC Now to check for updates.

The application source code is kept separately in a private repository.

## Publishing a release

1. Create a GitHub Release with tag `v<version>`.
2. Upload the signed APK as `OPIC-Now-v<version>.apk`.
3. Update `version.json` only after the APK asset is available.
