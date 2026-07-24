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

## Koreksi istilah dari contoh RPM

Pada contoh layout RPM yang Bro Cahyo kirim, ada koreksi penting pada bagian Dimensi Profil Lulusan (DPL):
- **DPL 2 Kewarganegaraan** harus ditulis menjadi **DPL 2 Kewargaan**

Koreksi ini wajib dipakai agar nanti penyusunan RPM produktif tidak salah istilah.

## File contoh RPM yang menjadi referensi layout

- `RPM_Bhs_Indonesia_1---803f4927-dd03-4926-96d6-c70a6dd0a78e.docx`
- File ini harus jadi acuan layout tetap untuk semua RPM produktif di project ini.
- Bagian identitas umum, identifikasi, dan asesmen pembelajaran harus mengikuti struktur contoh.

## File contoh RPM di Google Drive

- `https://docs.google.com/document/d/1Goh-vNOhuSoodlWiXp3-O7jMHZTS4iQr/edit`
- File ini sudah disimpan di folder `01 SUMBER` pada Google Drive root project.
- Layout file ini menjadi acuan wajib untuk semua RPM berikutnya.

## File ATP DDPK masuk sumber

- `41_QC1_FINAL_ATP_Yekti_Utari_SMKN_2_Magelang---1f5bb201-9184-4991-8a5a-27601e80d92d.pdf`
- File ini sudah disimpan ke folder `01 SUMBER` lokal.
- Selanjutnya file ini harus ikut di-upload ke Google Drive folder `01 SUMBER` dan menjadi referensi analisis ATP DDPK jurusan RPL.

## File analisis DDPK dalam format xls

- `ANALISIS_ELEMEN_CP_TP_ATP_DDPK.xls`
- Disimpan di folder `02 DASAR-DASAR PROGRAM KEAHLIAN RPL`.
- Di-upload ke Google Drive folder yang sama.
- Formatnya HTML spreadsheet agar tetap bisa dibuka oleh Excel/Drive di environment ini.

Link Drive:
- `https://docs.google.com/spreadsheets/d/1xfekESquHgmPFGb1ZTnIZlBwnXyXs2Cm/edit`
