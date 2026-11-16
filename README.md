# SYSTEM RPG — Android wrapper

Project Android Studio untuk mengemas aplikasi HTML offline menjadi APK.

## Build APK
1. Ekstrak ZIP ini.
2. Buka folder `SystemRPG-Android` melalui Android Studio (versi terbaru yang mendukung Android Gradle Plugin 8.7.3).
3. Tunggu Gradle Sync selesai. Pastikan Android SDK Platform 35 terpasang.
4. Pilih **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. APK debug akan tersedia di `app/build/outputs/apk/debug/app-debug.apk`.
6. Pindahkan APK ke HP Android, buka file tersebut, lalu izinkan instalasi dari sumber ini jika diminta.

## Fitur integrasi Android
- HTML, CSS, dan JavaScript disimpan lokal di `app/src/main/assets/index.html`.
- Tidak meminta izin internet; aplikasi dapat dijalankan offline.
- Penyimpanan progres memakai localStorage WebView pada perangkat.
- Restore backup memakai pemilih file Android.
- Backup JSON dapat disimpan melalui pemilih lokasi Android.

Package: `com.systemrpg.productivity`  
Versi: `1.0`  
Minimum Android: 6.0 (API 23)
