# CBT AI Companion

Aplikasi Android pendamping mandiri untuk membuka layanan AI dari satu halaman.

## Fitur
- ChatGPT, Gemini, Microsoft Copilot, DeepSeek, Claude, dan Perplexity.
- Membuka aplikasi Android jika terpasang.
- Membuka situs resmi jika aplikasi belum terpasang.
- Tampilan gelap sederhana dan daftar aplikasi yang mudah diperluas.

## Batasan penting
- Ini aplikasi pendamping terpisah, bukan patch untuk CBT Exam Browser.
- Fitur tidak otomatis muncul di aplikasi CBT asli maupun versi modifikasi.
- Tidak ada overlay/floating bubble di atas CBT, bypass kiosk, atau mekanisme untuk menghindari pengawasan ujian.
- Gunakan hanya di luar sesi ujian atau jika penggunaan AI diizinkan.

## Build
1. Buka folder project ini di Android Studio.
2. Gunakan JDK 17.
3. Izinkan Gradle mengunduh Android Gradle Plugin 8.7.3 dan Kotlin plugin 2.0.21.
4. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).

Minimum Android: 12 (API 32). Compile/target SDK: 35.

## Menambah layanan AI
Edit daftar `aiApps` pada `MainActivity.kt`. Tambahkan nama, package Android, URL resmi, dan deskripsi. Package name aplikasi dapat berbeda antar versi/region, jadi verifikasi sebelum rilis.
