# Project Memory: Project02_Horror

**Dokumen ini WAJIB DIBACA oleh setiap sesi AI (Agent) baru sebelum melakukan pekerjaan apa pun di proyek ini.**

## 1. Ringkasan Proyek
- **Nama Proyek:** `Project02_Horror`
- **Peran:** Pengguna (User) adalah **Game Director** dan pengambil keputusan akhir. AI bertindak sebagai asisten pengembangan.
- **Tujuan Game:** Menciptakan game *psychological horror* berlatar hutan tropis terlarang. Fokus pada eksplorasi, puzzle, narasi misterius, dan ketegangan yang dibangun perlahan.
- **Prinsip Desain Utama:** 
  - Bukan horror generik; hindari *jumpscare* murahan atau mekanik kejar-kejaran tanpa henti.
  - Makhluk (entity) harus terasa hidup, mengawasi, dan reaktif.
  - Lingkungan dan audio berperan paling penting dalam menciptakan ketidaknyamanan.
  - Rencana pengembangan berfokus pada **prototipe kecil yang bisa diuji**, bukan langsung membangun dunia besar.

## 2. Progres Aktual (Status Saat Ini)
- **Fondasi & Workflow:** `GameVision.md`, `project-rules.md`, dan `safe-development.md` sudah tersedia dan menjadi acuan mutlak.
- **Lingkungan (Blockout Hutan):** **[Selesai & Diuji]**
  - Objek di Workspace: Folder `ForestBlockout` yang berisi `DirtPath`, `LeftForestWall`, `RightForestWall`, `Canopy`.
  - Objek `Baseplate` dipertahankan, `SpawnLocation` dipindahkan ke ujung jalur dan disembunyikan.
- **Lighting & Atmosphere:** **[Selesai & Diuji]**
  - Konfigurasi gelap, berkabut pekat (bernuansa hijau-abu kusam) telah diterapkan.
- **Sistem Developer (Mode Terang/Gelap):** **[Selesai & Diuji]**
  - Tersedia sistem *ToggleMode* via Command Bar untuk mempermudah pengerjaan tanpa merusak nilai konfigurasi permanen. Lihat [DEVELOPMENT_MODES.md](./DEVELOPMENT_MODES.md).
- **Mekanik Gameplay / Monster:** **[Belum Dikerjakan]** Belum ada entity, puzzle, atau audio yang ditambahkan.

## 3. Ingatan Desain dan Keputusan
- Horror harus berkembang secara perlahan dari eksplorasi normal menuju suasana yang tidak nyaman.
- Utamakan atmosfer, perubahan lingkungan yang subtil, siluet jauh, perasaan diawasi, dan cerita.
- Puzzle dan cerita harus memiliki tujuan yang kuat.
- **JANGAN** memperluas cakupan proyek sebelum prototipe kecil tervalidasi.
- **JANGAN** menambahkan aset dari *Toolbox* tanpa persetujuan eksplisit dari Game Director.
- **JANGAN** mengubah `Workspace` secara destruktif atau memindahkan objek di dalamnya tanpa persetujuan eksplisit.

## 4. Aturan Kerja Agent (Agent Guidelines)
Setiap agent yang menangani proyek ini **WAJIB**:
1. Membaca dokumentasi memori proyek ini sebelum mengerjakan apa pun.
2. Memeriksa kondisi proyek aktual (status Git, hierarki objek di Roblox Studio) sebelum mengambil kesimpulan.
3. Mematuhi `.agents/rules/project-rules.md` dan `.agents/workflows/safe-development.md`.
4. Mengutamakan perubahan kecil, aman, dan mudah diuji.
5. Menjelaskan rencana *sebelum* melakukan perubahan besar atau berisiko.
6. Tidak melakukan commit atau push ke GitHub kecuali diminta secara eksplisit.
7. Tidak mengklaim tes berhasil apabila belum benar-benar dijalankan.
8. Tidak menambah fitur di luar permintaan.
9. Selalu melaporkan file, objek, perubahan, hasil tes, dan masalah yang belum terselesaikan di akhir tugas.
10. Menghemat token dengan menghindari riset berlebihan atau pengulangan audit yang tidak diperlukan jika informasi sudah tersedia.

## 5. Referensi Cepat
- **Tata Cahaya & Sistem Toggle:** Baca `docs/DEVELOPMENT_MODES.md`
- **Roadmap & Tugas Selanjutnya:** Baca `docs/ROADMAP.md`
- **Cara Melanjutkan di Sesi AI Baru:**
  1. Baca `PROJECT_MEMORY.md` (file ini).
  2. Baca `GameVision.md` dan aturan agent.
  3. Periksa Git status dan kondisi aktual Roblox Studio.
  4. Baca bagian Current State di `ROADMAP.md`.
  5. Lanjutkan tugas aktif tanpa mengulang pekerjaan.
  6. Minta konfirmasi jika ada keputusan yang belum jelas.
