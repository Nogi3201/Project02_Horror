# Project02_Horror --- Game Vision & Ideation Backup

> **Status:** Fondasi konsep / visi kreatif\
> **Tujuan dokumen:** Menyimpan ide, keputusan desain, dan arah artistik
> agar dapat dipulihkan jika percakapan, konteks AI, atau file kerja
> hilang.\
> **Catatan:** Dokumen ini merekam keputusan yang sudah dibuat sejauh
> ini. Hal yang belum diputuskan ditandai sebagai terbuka, bukan
> dianggap final.

------------------------------------------------------------------------

## 1. Ringkasan Proyek

**Project02_Horror** adalah game horor psikologis berbasis Roblox yang
mengutamakan atmosfer, rasa diawasi, ketidakpastian, eksplorasi, dan
interpretasi pribadi pemain.

Game ini tidak mengandalkan jumpscare berulang atau monster yang
terus-menerus mengejar pemain. Ketegangan tumbuh perlahan: dunia awalnya
terasa cukup normal, kemudian detail-detail kecil mulai terasa tidak
cocok. Pemain ingin meninggalkan tempat itu, tetapi rasa ingin tahu
membuat mereka terus menjelajah.

**Prinsip inti:** Pemain mengalami sesuatu yang terasa nyata di dalam
game, tetapi tidak diwajibkan menerima satu penjelasan tentang maknanya.

## 2. Peran Kreatif dan Batasan Pengembangan

-   Pemilik proyek adalah **Game Director** dan memegang keputusan
    akhir.
-   AI agent berperan sebagai tim pendukung untuk riset, perencanaan,
    implementasi, pengujian, dan dokumentasi.
-   AI tidak boleh mengubah visi atau mengambil keputusan desain besar
    secara sepihak.
-   Pengembangan harus bertahap, sederhana, dan sesuai kemampuan
    perangkat serta anggaran yang tersedia.
-   Prioritaskan fitur yang bisa diuji lebih awal daripada membangun
    dunia besar sekaligus.
-   Setelah fondasi ide tercatat, jangan terus memperluas konsep tanpa
    kebutuhan implementasi. Pilih satu pekerjaan kecil, bangun, uji, lalu
    evaluasi sebelum menambah fitur berikutnya.
-   Jangan menambahkan aset dari Toolbox atau sumber eksternal tanpa
    persetujuan.
-   Jangan melakukan perubahan destruktif pada `Workspace` tanpa
    persetujuan eksplisit.
-   Jangan mengklaim pengujian berhasil jika pengujian sebenarnya belum
    dilakukan.
-   Jangan melakukan commit atau push GitHub kecuali diminta.
-   Jaga keamanan kredensial dan jangan menyimpan token atau rahasia di
    repository.

## 3. Pengalaman yang Ingin Diciptakan

Emosi dan dorongan yang menjadi sumber utama desain:

-   Merasa sedang **diikuti**.
-   Merasa sedang **diawasi**.
-   Tidak yakin apakah sesuatu benar-benar berkaitan dengan diri pemain.
-   Ingin pergi atau meninggalkan hutan, tetapi tetap kembali karena
    penasaran.
-   Merasa tidak nyaman tanpa harus diserang.
-   Merasa bahwa dunia terus berjalan meskipun pemain bukan pusat dari
    segala sesuatu.

Kontradiksi pentingnya adalah: **pemain ingin menjauh, tetapi tetap
terdorong untuk mencari tahu.**

Ini bukan daftar pesan moral yang harus dipahami pemain. Ini adalah
bahan untuk merancang pengalaman.

## 4. Dunia dan Atmosfer

-   Lingkungan utama yang sedang dibayangkan adalah hutan, dengan
    kemungkinan bangunan atau tempat terbengkalai sebagai bagian dari
    eksplorasi.
-   Dunia terkadang terasa normal, tetapi ada sesuatu yang tidak
    sepenuhnya cocok.
-   Hutan bukan hanya panggung untuk monster; lingkungan harus memiliki
    atmosfer dan keberadaannya sendiri.
-   Suara angin, dedaunan, keheningan, jarak pandang, pencahayaan, serta
    perubahan kecil pada lingkungan dapat menciptakan ketegangan.
-   Pemain sebaiknya mendapatkan fase eksplorasi yang relatif tenang
    sebelum rasa tidak nyaman meningkat.
-   Hindari ketergantungan pada jumpscare dan pengejaran terus-menerus.

## Keputusan Desain Lanjutan

Bagian ini merekam keputusan dari pendalaman ide setelah fondasi awal ditulis. Keputusan ini menjaga arah proyek agar tidak bergeser menjadi horror generik. Detail implementasi boleh disesuaikan setelah diuji, tetapi arah dasarnya tidak boleh diubah sepihak.

### Alasan karakter memasuki hutan
Empat latar yang pernah dipertimbangkan adalah camper, pengunjung rutin yang sering menjelajahi hutan sendirian, peneliti, dan penyelidik. Keempatnya adalah konteks cerita, bukan kelas karakter: tidak ada kemampuan khusus atau jalur gameplay berbeda hanya karena latar tersebut. Detail pembuka dapat disederhanakan sesuai kebutuhan produksi.

### Pertemuan karakter
Karakter dapat memasuki hutan melalui jalur atau alasan berbeda, lalu bertemu di persimpangan atau area terbuka kecil. Mereka tidak harus langsung saling percaya atau membentuk kelompok yang kompak. Sebagian kejadian dapat dialami bersama, sementara sebagian lainnya terasa berbeda bagi tiap pemain. Perbedaan pengalaman tidak harus selalu dijelaskan, tetapi tidak boleh membuat tujuan utama tidak adil atau mustahil.

Gunakan chat atau voice Roblox yang tersedia untuk komunikasi. Jangan membangun sistem komunikasi khusus tanpa alasan gameplay yang kuat.

### Eksplorasi dan progres
Tidak ada kejadian wajib yang harus langsung memaksa pemain menjelajah setelah mereka bertemu. Pemain dapat memilih untuk melanjutkan karena rasa ingin tahu, tujuan yang ditemukan, atau hal-hal yang terasa tidak beres.

Progres dapat dibangun melalui area baru yang saling terhubung, puzzle lingkungan, dan petunjuk yang membantu pemain menyusun pemahaman sendiri. Pemain menyimpan temuan dalam ingatan mereka; sistem jurnal khusus bukan kebutuhan saat ini. Inventaris dan item masih terbuka untuk diputuskan jika benar-benar diperlukan.

### Dunia konsisten, pengalaman tidak selalu sama
Geografi inti hutan sebaiknya tetap dapat dipelajari, sementara detail lingkungan atau kejadian tertentu dapat bervariasi. Variasi bukan berarti peta acak tanpa arah. Jaga navigasi, keterbacaan tujuan, performa, dan konsistensi dunia.

### Petunjuk, puzzle, dan konsekuensi
Puzzle dan petunjuk membantu pemain bergerak maju tanpa menjelaskan seluruh misteri. Kegagalan puzzle pada umumnya dapat dicoba kembali. Pilihan pemain boleh memengaruhi kejadian berikutnya tanpa selalu diberi konfirmasi eksplisit.

Jangan mengunci progres utama hanya karena satu petunjuk kecil mudah terlewat. Misteri boleh sulit ditafsirkan, tetapi gameplay inti tetap harus dapat diselesaikan melalui pengamatan dan usaha pemain.

### Makhluk dan kejadian lingkungan
Makhluk tetap langka, sulit dipahami, dan tidak memiliki pola yang dapat dipastikan pemain. Ia dapat tampak mengamati, memanipulasi, atau memburu pemain, tetapi tidak harus selalu menyerang atau mengejar. Ia kadang membiarkan dirinya ditemukan, kadang menghilang, dan kadang bertindak tak terduga.

Makhluk bukan satu-satunya sumber keanehan. Suara hutan, angin yang menggerakkan dedaunan, keheningan, perubahan lingkungan, siluet jauh, dan kesan sedang diamati dapat membangun ketegangan tanpa penampakan langsung. Jangan membuat semua kejadian selalu berujung pada kemunculan makhluk.

### Prinsip pengalaman horror
- Awal permainan memberi waktu untuk eksplorasi yang relatif tenang.
- Ketidaknyamanan meningkat bertahap, bukan melalui jumpscare berulang.
- Pemain tidak terus-menerus dikejar dan game tidak mengandalkan pertarungan.
- Rasa takut tumbuh dari atmosfer, ketidakpastian, rasa diawasi, dan interpretasi pemain.
- Pemain tetap punya alasan untuk melanjutkan meskipun ingin menjauh.
- Tidak semua perbedaan atau kejadian harus dijelaskan.

## 5. Konsep Monster

### 5.1 Sifat umum

Monster dirancang agar dapat terasa seperti pengamat, manipulator, dan
pemburu, tetapi tidak harus memperlihatkan semua sifat itu pada setiap
kemunculan.

Monster terkadang dapat tampak seolah-olah menikmati reaksi pemain atau
sedang bermain-main. Namun, game tidak perlu memastikan apakah ia
benar-benar merasa senang, memiliki emosi seperti manusia, memahami
emosi pemain, atau sama sekali tidak peduli.

Pemain mungkin menganggap semua kejadian berhubungan dengan dirinya,
padahal monster tidak harus selalu bereaksi khusus terhadap pemain.

### 5.2 Perilaku dan kemunculan

-   Tidak ada pola perilaku yang dapat dipastikan oleh pemain.
-   Monster kadang membiarkan dirinya terlihat, kadang menghilang, dan
    kadang bereaksi dengan cara yang tidak terduga.
-   Mendekati monster tidak memiliki satu hasil yang selalu sama.
-   Monster tidak harus sering muncul. Lingkungan dapat membawa sebagian
    besar ketegangan.
-   Perbedaan penampakan tidak dikonfirmasi sebagai perubahan bentuk
    yang nyata ataupun sekadar kesalahan persepsi.
-   Monster tidak wajib terlihat jelas agar pemain dapat menyelesaikan
    permainan.
-   Sebagian pemain mungkin hanya melihat siluet atau penampakan
    sekilas; pemain lain mungkin mengalami pertemuan yang lebih jelas.
-   Tidak ada satu versi pengalaman pemain yang secara otomatis dianggap
    paling benar.

### 5.3 Batasan desain

Perilaku monster boleh dirancang dan dikendalikan secara teknis oleh
pengembang, sementara aturan dan motif di balik perilaku itu tetap tidak
dapat dipastikan oleh pemain.

Ketidakpastian tidak berarti kejadian dibuat asal acak. Setiap kejadian
tetap perlu mendukung atmosfer, eksplorasi, rasa ingin tahu, atau
keputusan pemain. Variasi harus tetap mempertimbangkan pacing, performa,
dan kelancaran gameplay.

## 6. Cerita dan Petunjuk

-   Cerita menggunakan petunjuk yang relatif konsisten.
-   Petunjuk dapat berupa catatan, lingkungan, simbol, rekaman, atau
    kejadian.
-   Makna petunjuk dapat ditafsirkan secara berbeda oleh pemain yang
    berbeda.
-   Petunjuk tidak harus mengarah pada satu teori final tentang monster.
-   Hindari membuat informasi saling bertentangan hanya untuk
    membingungkan pemain.
-   Pemain boleh menyusun teori, tetapi game tidak wajib mengonfirmasi
    teori itu sebagai kebenaran.
-   Misteri sebaiknya memberi cukup bahan untuk dipikirkan, bukan
    menyembunyikan seluruh informasi sampai tidak ada yang bisa
    dipahami.

## 7. Ending

Tujuan permainan dapat diselesaikan, tetapi tidak ada penyelesaian yang
menutup seluruh makna monster.

-   Pemain harus memiliki tujuan konkret dan merasakan penyelesaian
    gameplay.
-   Misteri utama yang berkaitan dengan tugas pemain dapat memperoleh
    penutupan yang memadai.
-   Hakikat, motif, dan makna monster tidak harus dijelaskan sepenuhnya.
-   Ending tidak wajib memberikan jawaban final tentang semua pengalaman
    yang dialami.
-   Pemain dapat meninggalkan game dengan interpretasi yang berbeda.
-   Game tidak menetapkan satu pesan moral atau makna tunggal yang wajib
    dibawa pulang pemain.

## 8. Prinsip Artistik

Pengembang memiliki pengalaman dan makna pribadi sebagai salah satu
sumber inspirasi. Namun, makna pribadi itu bukan batas akhir
interpretasi monster atau game.

**Tujuan artistik:** Menciptakan pengalaman yang memungkinkan pemain
membangun maknanya sendiri, termasuk kemungkinan bahwa mereka tidak
menemukan satu pesan tertentu.

Pernyataan ini bukan berarti semua elemen harus samar. Kejadian di dalam
game perlu terasa konkret; yang dibiarkan terbuka adalah penafsiran dan
maknanya.

## 9. Multiplayer dan Perbedaan Pengalaman

-   Fokus awal adalah pengalaman solo.
-   Multiplayer dapat dipertimbangkan kemudian, setelah pengalaman solo
    cukup kuat.
-   Jika multiplayer ditambahkan, pemain mungkin memperoleh informasi
    atau mengalami kejadian pada waktu yang berbeda.
-   Perbedaan informasi dapat menciptakan ketidakpastian dan percakapan
    antarpemain, tetapi tidak boleh membuat tujuan inti menjadi tidak
    adil atau mustahil.
-   Jangan membangun fitur multiplayer sebelum kebutuhan dan dampaknya
    terhadap desain sudah jelas.

## 10. Batasan Privasi dan Platform

Efek "seolah-olah game mengetahui atau mengawasi pemain" hanya boleh
dibuat melalui desain dan kejadian di dalam game.

-   Jangan mengakses kamera, mikrofon, file pribadi, atau data perangkat
    pemain secara tersembunyi.
-   Jangan mengklaim game mengetahui informasi pribadi yang sebenarnya
    tidak diakses.
-   Efek meta atau fourth-wall boleh dipertimbangkan sebagai ilusi
    naratif yang aman dan transparan dari sisi teknis.
-   Validasi input yang berasal dari klien pada server; jangan
    mempercayai klien untuk keputusan penting.

## 11. Status Proyek yang Diketahui

Berdasarkan catatan pengembangan terakhir:

-   Project kerja bernama `Project02_Horror`.
-   Struktur repository mencakup `.git`, `docs`, `references`, `roblox`,
    `scripts`, dan `tests`, serta `README` dan `GameVision.md`.
-   Aturan agen berada di `.agents/rules/project-rules.md`.
-   Workflow pengembangan aman berada di
    `.agents/workflows/safe-development.md`.
-   Prototipe blockout hutan awal pernah dibuat di Roblox Studio dengan
    `Workspace.ForestBlockout`, jalur tanah, dinding hutan kiri/kanan,
    kanopi, dan SpawnLocation tersembunyi.
-   Baseplate masih dipertahankan.
-   Mode pencahayaan Horror dan Development pernah disiapkan melalui
    ModuleScript di `ServerStorage`.
-   Pengaturan pencahayaan Horror yang tercatat mencakup waktu `18.2`,
    `Brightness = 1`, `FogEnd = 150`, `OutdoorAmbient = RGB(20,30,25)`,
    `Ambient = RGB(15,20,15)`, `FogColor = RGB(15,25,20)`, serta
    Atmosphere dengan `Density = 0.4`, `Haze = 2.5`,
    `Color = RGB(25,35,30)`, dan `Decay = RGB(15,20,15)`.
-   Pengujian pergantian mode Development → Horror pernah dilaporkan
    berjalan baik oleh agen dan pengguna.
-   Status ini harus diperiksa ulang langsung di file dan Roblox Studio
    sebelum dianggap sebagai keadaan proyek saat ini.

## 12. Tahapan Pengembangan yang Disarankan

Tahapan ini adalah roadmap kerja, bukan janji bahwa semua tahap telah
selesai.

1.  **Amankan visi dan catatan proyek.** Simpan dokumen ini dan pastikan
    tersimpan dalam Git.
2.  **Validasi blockout hutan.** Uji skala jalur, keterbacaan arah,
    jarak pandang, suasana, dan kenyamanan navigasi.
3.  **Uji atmosfer tanpa monster.** Pastikan suara, cahaya, kabut, dan
    lingkungan sudah menciptakan rasa tidak nyaman.
4.  **Buat satu kejadian pengamatan yang halus.** Contohnya, siluet jauh
    yang hanya terlihat dalam kondisi tertentu. Jangan langsung
    membangun sistem monster lengkap.
5.  **Uji reaksi pemain.** Catat apa yang benar-benar dirasakan pemain,
    bukan hanya apa yang pengembang harapkan.
6.  **Rancang tujuan eksplorasi dan petunjuk cerita.** Pastikan pemain
    punya alasan untuk bergerak dan menyelesaikan permainan.
7.  **Bangun sistem secara bertahap.** Tambahkan variasi kejadian hanya
    setelah prototipe dasarnya berfungsi.
8.  **Integrasi, optimasi, dan pengujian.** Periksa performa, bug,
    kejelasan tujuan, dan konsistensi atmosfer.
9.  **Pertimbangkan multiplayer dan rilis.** Lakukan hanya setelah
    pengalaman inti solo cukup kuat.

## 13. Hal yang Belum Diputuskan

Jangan menganggap hal berikut sudah final:

-   Nama resmi game dan judul yang akan ditampilkan kepada pemain.
-   Identitas, bentuk definitif, asal-usul, dan motif monster.
-   Tujuan konkret pemain dari awal hingga akhir.
-   Tokoh, lokasi, sejarah, dan kejadian spesifik dalam cerita.
-   Jenis dan urutan puzzle.
-   Apakah ada inventaris, bagaimana cara kerjanya, dan item apa yang
    dibutuhkan.
-   Detail ending secara visual dan gameplay.
-   Durasi final game. Durasi 30--60 menit pernah dipertimbangkan
    sebagai target, belum menjadi komitmen final.
-   Bentuk multiplayer dan apakah akan dirilis.
-   Musik, efek suara, aset visual, dan sumber aset final.
-   Detail teknis sistem kemunculan monster.

## 14. Aturan Kerja untuk AI Agent

Saat menerima tugas terkait Project02_Horror, agen harus:

1.  Membaca dokumen visi ini dan aturan proyek sebelum mengubah file.
2.  Memeriksa keadaan proyek yang sebenarnya; jangan berasumsi catatan
    selalu terbaru.
3.  Untuk tugas berisiko tinggi atau multi-file, jelaskan rencana dan
    file yang akan diubah terlebih dahulu.
4.  Meminta persetujuan sebelum perubahan destruktif atau perubahan
    besar yang belum disetujui.
5.  Membuat perubahan sekecil mungkin dan mempertahankan sistem yang
    sudah berfungsi.
6.  Menguji perubahan yang bisa diuji dan menjelaskan metode serta
    hasilnya dengan jujur.
7.  Memisahkan fakta, asumsi, usulan, dan hal yang belum diputuskan.
8.  Melaporkan file yang diubah, risiko, hasil pengujian, dan langkah
    berikutnya.
9.  Tidak membuat commit, push, atau mempublikasikan tanpa instruksi.
10. Jika ada konflik antara usulan agen dan visi proyek, sampaikan
    trade-off dan tunggu keputusan Game Director.

## 15. Cara Menjaga Dokumen Ini

-   Simpan file ini sebagai `docs/PROJECT02_HORROR_GAME_VISION.md`.
-   Simpan dalam repository Git agar perubahan dapat dilacak.
-   Pertimbangkan membuat salinan cadangan di lokasi terpisah atau
    repository privat.
-   Setelah keputusan besar berubah, perbarui dokumen dan catat tanggal
    serta alasan perubahan.
-   Jangan menghapus keputusan lama begitu saja jika keputusan itu
    penting untuk memahami evolusi ide; pindahkan ke bagian riwayat
    perubahan bila diperlukan.
-   Jangan menyimpan token, kata sandi, atau rahasia di dokumen ini.

------------------------------------------------------------------------

## Riwayat Perubahan

- **Pembaruan ide lanjutan:** Menambahkan latar karakter, pertemuan, eksplorasi, variasi pengalaman, prinsip puzzle, dan batas agar pengembangan tetap sesuai visi.

-   **Versi awal:** Merangkum visi, keputusan artistik, konsep monster,
    prinsip cerita, ending, batasan teknis, status yang diketahui, dan
    roadmap berdasarkan diskusi awal Project02_Horror.
-   Tambahkan tanggal dan alasan pada pembaruan berikutnya.
