# WiFi Mirror APK releases

This repository stores versioned Android APK releases and update information. Application source is maintained separately.

## Versions

Release tags use `v<versionName>-<versionCode>`, for example `v1.1.0-2`. Android version codes must increase. Existing versions are never overwritten.

Each release contains:

- `WiFiMirror.apk`: non-debuggable release APK signed with the same certificate as the installed app.
- `release.json`: package, version, size, SHA-256 and public signing certificate fingerprint.
- `SHA256SUMS`: checksum for manual verification.

## In-app updates

Open WiFi Mirror, then Settings > App version and updates. Check for updates, download, and confirm installation with Android. The first install from WiFi Mirror may require allowing this installation source in system settings.

PIN and settings are retained. Mirroring briefly disconnects during installation. Open the app after installation if necessary.

The updater uses anonymous GitHub Releases access. This repository must be public for phone updates without GitHub sign-in; source code does not need to be public.
