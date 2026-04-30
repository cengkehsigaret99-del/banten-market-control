# Banten Market Control

Aplikasi web statis untuk prototype team pemasaran wilayah Banten.

## Fitur
- Dashboard pemasaran
- Input kunjungan sales
- Data outlet/prospek
- Input order masuk
- Follow-up customer
- Data kompetitor
- Laporan harian print/save PDF
- Export/Import JSON
- Export CSV ringkas
- Bisa dipasang ke layar utama HP karena sudah PWA sederhana

## Cara upload ke GitHub Pages
1. Buat repository baru di GitHub, misalnya `banten-market-control`.
2. Upload semua file ini: `index.html`, `manifest.json`, `sw.js`, `icon.svg`, `README.md`.
3. Masuk ke Settings > Pages.
4. Source pilih `Deploy from a branch`.
5. Branch pilih `main` dan folder `/root`.
6. Save.
7. Tunggu sampai muncul link GitHub Pages.

## Catatan penting
Versi ini tidak memakai database online. Data tersimpan di browser/perangkat masing-masing memakai localStorage.
Untuk memindahkan data antar perangkat, gunakan menu Export/Import Data.
Kalau ingin data semua sales otomatis terkumpul real-time, perlu upgrade ke Supabase/Firebase.
