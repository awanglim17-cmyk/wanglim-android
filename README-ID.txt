Wanglim Android project

Folder ini adalah project Android, bukan APK siap instal.

Cara paling ringkas membuat APK tanpa Android Studio:
1. Buat repository baru di GitHub.
2. Upload semua isi folder ini ke repository, pastikan file .github/workflows/build-apk.yml ikut ter-upload.
3. Buka tab Actions > Build Wanglim APK > Run workflow.
4. Setelah selesai, buka hasil run dan unduh artifact "Wanglim-debug-APK".
5. Ekstrak artifact ZIP, lalu instal app-debug.apk di Android.

Build memerlukan internet dan GitHub account. APK debug belum ditandatangani untuk distribusi publik.
Catatan: Firebase belum dikonfigurasi pada project ini.
