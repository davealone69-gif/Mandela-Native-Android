# Mandela Native Android

**Clean native Android build** combining the working parts from the Workshop Manual Organiser into a fresh Mandela Re-imaginator foundation.

This is a **totally new repo** — separate from the hybrid Capacitor version.

## Features (from Workshop)
- Dashboard with recent manuals + search
- Manual Library with tags, import, AI scan simulation
- AI VIN Plate Decoder (camera)
- Manual Viewer with TTS + Gemini chat side panel
- Scanner / Digitize Manual flow
- Collaboration / Safety alerts
- Settings (theme + font)
- Full Gemini streaming chat (Flash + Pro thinking mode)

## Tech Stack
- Kotlin
- Jetpack Compose (Material 3)
- Navigation Compose
- Retrofit + Moshi + OkHttp (Gemini API)
- Modern Gradle Kotlin DSL + Version Catalog
- Secrets Gradle Plugin for `GEMINI_API_KEY`

## Quick Start
1. Open this folder in **Android Studio**
2. Copy `.env.example` → `.env` and add your Gemini API key
3. Sync Gradle
4. Run on emulator or device
5. Build APK:
   ```bash
   ./gradlew assembleDebug
   # or assembleRelease (needs keystore)
   ```

## Package
Currently `com.example` (easy to change later to `com.mandelamatrix.reimaginator`).
