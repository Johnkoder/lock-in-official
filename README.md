# Lock In — official Android release

Lock In is a cozy, local-first Pomodoro productivity app with Timelapse Studio.

## Latest release

**Lock In 1.2.1 (build 16)**

[Download the Android release APK](releases/lock-in-android-v1.2.1-build16-release.apk)

- Package: `app.lockin.mobile`
- Build type: production release
- APK size: 70,684,323 bytes
- SHA-256: `a9c9047db32d82676771e1e643dc27f7236fafaeda4229b56c394830501e1f0b`

### What’s new

- Preserves source footage when reel conversion is interrupted by closing Lock In.
- Detects interrupted conversions after reopening and replaces stuck Processing states
  with a clear, recoverable retry state.
- Adds a prominent Retry reel conversion action that safely reuses the previously
  selected finished-reel duration.
- Prevents duplicate retries and protects active conversions from being marked failed.
- Handles missing source footage without leaving an unusable retry loop.

The APK is release-signed, non-debuggable, 16 KB aligned, and checked for accidental
credentials, private paths, signing files, and local development artifacts.

You can independently verify the download with the accompanying
[SHA-256 checksum file](releases/lock-in-android-v1.2.1-build16-release.apk.sha256).
