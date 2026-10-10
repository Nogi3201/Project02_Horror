# Roadmap: Project02_Horror

## Tahap Selesai (Completed)
- [x] Persiapan repositori, dokumentasi visi (`GameVision.md`), dan aturan kerja agent.
- [x] Blockout lingkungan dasar (`ForestBlockout` dengan part sederhana).
- [x] Implementasi tata cahaya dan kabut (*Lighting & Atmosphere*) untuk Horror Mode.
- [x] Pembuatan sistem alat bantu developer (`Development Mode` / `Horror Mode`).

## Tahap Aktif (Current Task)
**Status Saat Ini:** Validasi atmosfer dan blockout melalui *Playtest*.

Tugas kita saat ini berhenti pada tahap pengecekan lingkungan, BUKAN membuat monster atau sistem logika gameplay. Daftar pemeriksaan berikutnya yang harus dijawab oleh Game Director setelah melakukan Playtest:
- Apakah jalur hutan nyaman dijelajahi?
- Apakah dinding hutan terlihat seperti lingkungan hutan (meskipun dari balok *Part*), bukan sekadar lorong kotak?
- Apakah kabut cukup membatasi jarak pandang tanpa mengganggu navigasi?
- Apakah suasana tetap menarik tanpa monster atau *jumpscare*?
- Perubahan kecil apa yang paling bermanfaat setelah *playtest* (misalnya menutupi celah `Baseplate` atau menyesuaikan `ClockTime`)?

## Tahap Berikutnya (Next Milestones)
*Hanya boleh dikerjakan setelah tahap aktif di atas divalidasi dan disetujui.*

1. **Revisi Blockout & Visual Dasarnya**
   Menyelesaikan masalah batas dunia (Baseplate) dan memastikan lorong hutan tertutup rapi tanpa merusak performa.
2. **Implementasi Audio Ambient Dasar**
   Menambahkan suara halus angin/hutan yang konstan.
3. **Kejadian *Subtle Stalking* Pertama**
   Membuat objek siluet/bayangan sederhana yang menghilang/hancur ketika pemain mendekat atau menoleh, tanpa menggunakan UI atau suara kejut.
4. **Ekspansi Hutan & Objek Menarik (POI)**
   Merancang bentuk bangunan terbengkalai atau rute eksplorasi lebih lanjut.
