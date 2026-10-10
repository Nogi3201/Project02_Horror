# Development & Horror Modes

Dokumen ini menjelaskan sistem alat bantu *developer* untuk mengatur pencahayaan map selama tahap pengembangan.

## 1. Ikhtisar Sistem
Sistem ini dibuat secara murni di `ServerStorage` tanpa mengganggu struktur `Workspace` dan tanpa mengubah konfigurasi default secara acak.
- **`ServerStorage.HorrorLightingData`** (ModuleScript): Menyimpan nilai konfigurasi murni Horror Mode.
- **`ServerStorage.ToggleMode`** (ModuleScript): Fungsi yang dijalankan via Command Bar untuk beralih mode.
- **Status `EnforceHorrorMode`**: Dibatalkan. Sistem sengaja dirancang manual agar developer bebas menguji coba fisika atau mekanik saat Playtest dalam keadaan terang (Development Mode).

## 2. Nilai Konfigurasi yang Disepakati & Diuji
Berikut adalah nilai murni dari **Horror Mode** yang menjadi standar default game ini:

**Lighting:**
- `ClockTime` = 18.2
- `Brightness` = 1
- `FogEnd` = 150
- `OutdoorAmbient` = Color3.fromRGB(20, 30, 25)
- `Ambient` = Color3.fromRGB(15, 20, 15)
- `FogColor` = Color3.fromRGB(15, 25, 20)

**Atmosphere:**
- `Density` = 0.4
- `Haze` = 2.5
- `Color` = Color3.fromRGB(25, 35, 30)
- `Decay` = Color3.fromRGB(15, 20, 15)

Sedangkan **Development Mode** akan menggunakan nilai terang: `ClockTime = 14`, `FogEnd = 100000`, `Atmosphere.Density = 0`, dan warna Ambient terang untuk kemudahan inspeksi visual.

## 3. Prosedur Aman Menggunakan Command Bar
Untuk beralih mode, ikuti langkah berikut:
1. Buka Roblox Studio pada proyek yang benar.
2. Buka tab **View** dan aktifkan **Command Bar**.
3. *Copy* dan *paste* perintah berikut di Command Bar lalu tekan Enter:

**Untuk Development Mode (Menerangkan Map):**
```lua
require(game.ServerStorage.ToggleMode)("Dev")
```

**Untuk Mengembalikan Horror Mode (Kondisi Gelap & Kabut):**
```lua
require(game.ServerStorage.ToggleMode)("Horror")
```

## 4. Batasan & Peringatan Penting
- **Penyimpanan:** Perubahan Lighting yang dilakukan via Command Bar di Edit Mode **bersifat permanen** jika Anda melakukan Save/Publish. 
- **Aturan Emas:** Sebelum menyimpan atau memublikasikan game, **PASTIKAN konfigurasi Horror Mode telah dipulihkan** menggunakan perintah Command Bar `"Horror"` di atas.
- Jika Command Bar atau *module* tidak berfungsi pada konteks Studio yang sedang aktif, periksa penyebabnya terlebih dahulu. Jangan langsung membuat sistem pengganti tanpa analisis mendalam.
