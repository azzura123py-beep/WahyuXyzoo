# WahyuXyzoo

Flutter application dengan otomasi build APK menggunakan GitHub Actions.

## Fitur

- ✅ Flutter Application
- ✅ Automated APK Build (GitHub Actions)
- ✅ Release Management
- ✅ Artifact Upload

## Prasyarat

- Flutter SDK 3.24.0+
- Java 17+
- Android SDK

## Setup Lokal

```bash
# Clone repository
git clone https://github.com/azzura123py-beep/WahyuXyzoo.git
cd WahyuXyzoo

# Get dependencies
flutter pub get

# Build APK
flutter build apk --release
```

## CI/CD Workflow

APK dibangun secara otomatis ketika:
- ✅ Push ke branch `main`
- ✅ Pull Request ke branch `main`
- ✅ Manual trigger (Workflow Dispatch)

Hasil APK disimpan di **Artifacts** dan dapat diunduh dari workflow run.

## Build Output

Setelah successful build, APK tersedia di:
- `build/app/outputs/flutter-apk/app-release.apk`

## License

CC0 1.0 Universal
