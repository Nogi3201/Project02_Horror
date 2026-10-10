---
description: Workflow pengembangan Roblox yang aman, bertahap, dan dapat diverifikasi untuk Project02_Horror.
---

# Safe Development Workflow

Gunakan workflow ini ketika Game Director meminta implementasi fitur, perbaikan bug, refactor, atau perubahan struktur proyek.

## Tahap 1 — Pahami tugas
1. Tulis ulang tujuan tugas dalam satu atau dua kalimat.
2. Tentukan hasil yang diharapkan dan kriteria keberhasilannya.
3. Baca `GameVision.md` dan dokumentasi terkait jika diperlukan.
4. Jangan memperluas lingkup tugas tanpa alasan.

## Tahap 2 — Inspeksi
1. Periksa struktur file dan status Git.
2. Baca script serta dependensi yang relevan.
3. Identifikasi risiko terhadap sistem yang sudah ada.
4. Bedakan fakta yang sudah diperiksa dari asumsi yang belum diverifikasi.

## Tahap 3 — Rencana sebelum eksekusi
Sampaikan kepada Game Director:
- Tujuan dan pendekatan.
- File atau objek yang akan diubah.
- File atau objek yang tidak akan disentuh.
- Risiko dan kemungkinan dampak samping.
- Rencana pengujian dan kriteria keberhasilan.

Berhenti dan minta persetujuan sebelum perubahan berisiko, perubahan besar, atau perubahan di luar izin eksplisit.

## Tahap 4 — Implementasi bertahap
1. Kerjakan perubahan terkecil yang memenuhi tujuan.
2. Hindari refactor yang tidak diperlukan.
3. Pertahankan kompatibilitas dengan sistem terkait.
4. Jangan mengubah Workspace tanpa izin eksplisit.
5. Jangan mengubah banyak subsistem sekaligus jika bisa dipisahkan.
6. Jika ditemukan masalah di luar lingkup tugas, laporkan terlebih dahulu.

## Tahap 5 — Verifikasi
1. Periksa sintaks, referensi objek, dan dependensi.
2. Jalankan pemeriksaan statis atau tes yang tersedia.
3. Uji di Roblox Studio dalam kondisi yang relevan.
4. Periksa Output dan kemungkinan regresi.
5. Jika gagal, cari akar masalah sebelum mencoba perubahan berikutnya.
6. Jangan mengarang hasil tes yang belum dijalankan.

## Tahap 6 — Laporan akhir
Laporkan dengan format berikut:

### Ringkasan
Apa yang berhasil dikerjakan dan apa yang belum.

### File terdampak
Daftar file yang dibuat, diubah, atau dihapus beserta alasannya.

### Pengujian
Tes yang benar-benar dijalankan dan hasilnya.

### Risiko dan masalah tersisa
Error, asumsi, keterbatasan, atau hal yang belum diverifikasi.

### Langkah berikutnya
Satu langkah paling relevan, tanpa menambahkan fitur baru secara otomatis.
