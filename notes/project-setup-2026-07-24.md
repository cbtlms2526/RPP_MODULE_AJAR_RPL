# Project Setup - RPP_MODULE_AJAR_RPL

Tanggal: 2026-07-24

## Permintaan Bro Cahyo

- Membuat project baru: `RPP_MODULE_AJAR_RPL`
- Menyimpan semua pembicaraan dan pengaturan penting ke catatan
- Setiap ada penambahan/perubahan data di folder lokal VPS harus langsung disinkronkan ke GitHub:
  - `https://github.com/cbtlms2526/RPP_MODULE_AJAR_RPL.git`
- Menyiapkan project terlebih dahulu
- Mengecek koneksi ke GitHub
- Membuat 5 folder utama:
  1. `01 SUMBER`
  2. `02 DASAR-DASAR PROGRAM KEAHLIAN RPL`
  3. `03 KONSENTRASI KEAHLIAN RPL`
  4. `04 MATAPELAJARAN PILIHAN`
  5. `05 PROYEK KREATIF KEWIRAUSAHAAN`
- Sinkron ke Google Drive:
  - `https://drive.google.com/drive/folders/1IirabHwxcd0KJn7JTuHjCM4npMiMycZN`
- Memakai metode OAuth yang sama seperti project `practical-learning-modules`

## Status setup lokal

- Repo lokal sudah di-clone ke:
  - `/home/mvp-openclaw/.openclaw/workspace/projects/RPP_MODULE_AJAR_RPL`
- Struktur 5 folder utama sudah dibuat secara lokal.
- README project sudah dibuat.
- Catatan ini dibuat agar detail setup tidak hilang.

## Status GitHub

- Remote repo berhasil dicek dengan `git ls-remote`.
- Clone repo berhasil.
- Push belum berhasil karena GitHub menolak akses dengan error 403 dari token/credential yang tersedia untuk repo ini.
- Artinya koneksi ke GitHub hidup, tetapi akses tulis ke repo baru ini belum valid dari credential yang ada saat ini.

## Status Google Drive

- Setup Drive akan memakai OAuth client/token yang sama pola-nya dengan project lama.
- Root folder dan subfolder target sudah disiapkan untuk dibuat/ditautkan.
- Percobaan langsung ke Drive target masih gagal dengan error `invalid_client`, jadi perlu verifikasi ulang OAuth client yang dipakai sebelum folder Drive bisa dibuat.

## Status terbaru GitHub

- Repo `RPP_MODULE_AJAR_RPL` sudah berhasil dipush ke GitHub.
- Branch `main` sudah tracking `origin/main`.
- Remote repo aktif dan perubahan lokal berhasil tersinkron.

## Catatan penting

Kalau ada perubahan lokal berikutnya, project ini harus langsung disinkronkan ke GitHub.
Untuk Drive, perlu credential OAuth yang valid agar proses folder sync bisa dijalankan.
