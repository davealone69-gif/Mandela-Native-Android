# Mandela Native Android

## Download the APK

- [Builds and Debug APK artifacts](https://github.com/davealone69-gif/Mandela-Native-Android/actions/workflows/build-apk.yml). Open a successful run and download the `app-debug-apk` artifact. GitHub may require you to sign in.
- [GitHub Releases](https://github.com/davealone69-gif/Mandela-Native-Android/releases).
- [Full repository audit runs](https://github.com/davealone69-gif/Mandela-Native-Android/actions/workflows/full-audit.yml).
- [Current Android build repair pull request](https://github.com/davealone69-gif/Mandela-Native-Android/pull/1).

## Build status

The build workflow has been updated to use Gradle 8.9 to match the Android Gradle Plugin requirement. Check the live build link above for the latest result. A successful CI build is not a phone installation/runtime test.

## Local build

The CI workflow is the source of truth for the current SDK, Java, and Gradle versions. Do not treat the app as fully verified until the APK has been installed and its main flows tested on an Android device.
