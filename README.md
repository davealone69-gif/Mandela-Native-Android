# Mandela Native Android

Native Android source for the Mandela / Matrix consolidation work.

## Download the APK

- **[Builds and downloadable Debug APK artifacts](https://github.com/davealone69-gif/Mandela-Native-Android/actions/workflows/build-apk.yml)**. Open the latest successful run and download **app-debug-apk**. GitHub may require you to be signed in.
- **[GitHub Releases](https://github.com/davealone69-gif/Mandela-Native-Android/releases)** for versioned releases.
- **[Full repository audit runs](https://github.com/davealone69-gif/Mandela-Native-Android/actions/workflows/full-audit.yml)**.
- **[Current Android build repair pull request](https://github.com/davealone69-gif/Mandela-Native-Android/pull/1)**.

## Build status

The workflow has been updated to use Gradle 8.9, which matches the Android Gradle Plugin requirement. Check the live build link above for the latest result. A successful CI build is not a phone installation/runtime test.

## Local build

The CI workflow is the source of truth for the current SDK, Java, and Gradle versions. The project is being audited; do not treat the app as fully verified until the APK has been installed and its main flows tested on an Android device.
