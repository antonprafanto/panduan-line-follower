# ðŸ¤– PANDUAN RESMI LOMBA ROBOT LINE FOLLOWER

**Versi:** 3.0 â€” Audit Final & Lengkap
**Berlaku untuk:** Kategori Analog (A) & Digital (D) | Jenjang SMP s.d. Mahasiswa/Umum

> *Disusun & diverifikasi berdasarkan referensi regulasi:*
> *Technocorner UGM Â· RobotChallenge Â· ELCCO Udayana Â· IPB MBF Â· MRC Â· BIRT 2024/2025*

---

## DAFTAR ISI

1. [Ketentuan Umum](#1-ketentuan-umum)
2. [Kategori Lomba](#2-kategori-lomba)
3. [Regulasi Teknis Robot](#3-regulasi-teknis-robot)
4. [Spesifikasi Lintasan](#4-spesifikasi-lintasan)
5. [Prosedur Pra-Pertandingan](#5-prosedur-pra-pertandingan)
6. [Format & Mekanisme Pertandingan](#6-format--mekanisme-pertandingan)
7. [Tata Tertib Area Lomba](#7-tata-tertib-area-lomba)
8. [Sistem Penilaian](#8-sistem-penilaian)
9. [Aturan Retry & Penalti](#9-aturan-retry--penalti)
10. [Diskualifikasi](#10-diskualifikasi)
11. [Dewan Wasit & Prosedur Banding](#11-dewan-wasit--prosedur-banding)
12. [Hadiah & Penghargaan](#12-hadiah--penghargaan)
13. [Contoh Jadwal Hari-H](#13-contoh-jadwal-hari-h)
14. [Checklist Panitia](#14-checklist-panitia)

---

## 1. KETENTUAN UMUM

### 1.1 Target Peserta

Lomba ini terbuka untuk jenjang **SMP ke atas**, meliputi:

| Jenjang | Keterangan |
|---------|-----------|
| SMP / MTs | Kelas 7â€“9 |
| SMA / SMK / MA | Kelas 10â€“12 |
| Mahasiswa | D3, D4, S1 semua jurusan |
| Umum | Lulusan / profesional muda |

### 1.2 Komposisi Tim

| Jenjang | Anggota Tim | Pembimbing |
|---------|-------------|-----------|
| SMP / MTs | 2â€“3 siswa | 1 guru/pembina **(wajib)** |
| SMA / SMK / MA | 2â€“4 siswa | 1 guru/pembina **(wajib)** |
| Mahasiswa / Umum | 2â€“5 orang | 1 mentor *(opsional)* |

> ðŸ“Œ Satu orang **tidak boleh** terdaftar sebagai anggota di lebih dari **satu tim** dalam kategori yang sama.
> Pembimbing **tidak diizinkan** memberikan arahan teknis kepada robot atau anggota tim selama pertandingan berlangsung.

### 1.3 Batas Tim Per Institusi

- Satu sekolah / kampus / lembaga **maksimum mendaftarkan 3 tim per kategori**. Â¹
- Jika jumlah pendaftar dari satu institusi melebihi batas, panitia berhak menyeleksi berdasarkan urutan waktu pendaftaran.

### 1.4 Ketentuan Tim Lintas Jenjang

Jika anggota sebuah tim berasal dari **jenjang yang berbeda** (misal: 1 siswa SMA + 1 mahasiswa), maka:

| Kondisi | Kategori Jenjang yang Berlaku |
|---------|-------------------------------|
| Ada anggota **Mahasiswa / Umum** | Tim dikategorikan sebagai **Mahasiswa/Umum** |
| Semua SMA atau campuran SMP+SMA | Tim dikategorikan sebagai **SMA/SMK** |
| Semua anggota SMP | Tim dikategorikan sebagai **SMP** |

> ðŸ“Œ Kategorisasi jenjang memengaruhi persyaratan **wajib/tidaknya pembimbing**. Kategori jenjang **tidak** membatasi pilihan Kategori Lomba (Analog/Digital).

### 1.5 Ketentuan Robot

- Setiap tim hanya diizinkan mendaftarkan **1 (satu) robot** per kategori yang diikuti.
- Robot **wajib merupakan hasil rancangan dan rakitan sendiri** (*handmade*). Dilarang menggunakan kit rakitan komersial siap pakai (*pre-assembled robot kit*).
- Penggunaan ban dan gearbox bermerek **TAMIYA** diperbolehkan terbatas hanya untuk: ban karet, komponen gearbox, dan motor DC.
- Robot yang terdaftar di homologasi adalah **satu-satunya robot** yang boleh digunakan sepanjang kompetisi. Robot cadangan tidak diizinkan dalam kondisi apapun.
- **Penandaan identitas robot:** Setiap robot **wajib mencantumkan label/stiker nama tim dan nomor peserta** yang terlihat jelas di badan robot. Label diberikan oleh panitia saat proses homologasi.

### 1.6 Prinsip Otonomi Mutlak

> âš ï¸ **ATURAN TIDAK DAPAT DIGANGGU GUGAT**
>
> Setelah sinyal start diberikan, robot **wajib beroperasi 100% otonom tanpa campur tangan manusia apapun**. Penggunaan remote control, Bluetooth, Wi-Fi, modul radio frekuensi (RF), atau alat kendali nirkabel dalam bentuk apapun **saat robot berada di lintasan** adalah pelanggaran fatal yang berujung **diskualifikasi langsung**.

---

## 2. KATEGORI LOMBA

Lomba ini membuka **2 (dua) kategori resmi yang berjalan terpisah:**

### Kategori A â€” Analog

| Aspek | Ketentuan |
|-------|-----------|
| **Teknologi** | Sirkuit IC linear komparator (LM324 / LM339 atau setara) |
| **Larangan keras** | Dilarang menggunakan mikrokontroler / perangkat terprogram apapun |
| **Sensor** | LDR atau Fotodioda, **maksimum 4 sensor** |
| **Logika kontrol** | Murni berbasis tegangan komparator dan H-Bridge transistor |
| **Kalibrasi** | Hanya boleh menggunakan **potensiometer fisik**, bukan software |
| **Target utama** | SMP, SMA/SMK |

### Kategori D â€” Digital / Mikrokontroler

| Aspek | Ketentuan |
|-------|-----------|
| **Teknologi** | Mikrokontroler bebas (Arduino Uno/Nano, ATmega, ARM Cortex, ESP32, STM32, dll.) |
| **Sensor** | IR array / QTR sensor, **maksimum 10 sensor** |
| **Logika kontrol** | Bebas, termasuk algoritma PID, fuzzy, atau lainnya |
| **Kalibrasi** | Boleh melalui software, dip switch, tombol, LCD onboard â€” **hanya saat robot tidak di lintasan** |
| **Target utama** | SMP (diizinkan)*, SMA/SMK, Mahasiswa, Umum |

> *âš ï¸ **Catatan untuk SMP di Kategori Digital:** Peserta SMP **diizinkan** mendaftar di Kategori D selama robot memenuhi seluruh spesifikasi teknis. Tidak ada larangan berdasarkan jenjang â€” kemampuan teknis menentukan kategori.*

> ðŸ’¡ Peserta **boleh mendaftar di kedua kategori sekaligus** dengan robot yang **berbeda** untuk masing-masing kategori.

### 2.3 Jaminan Jadwal Tidak Bentrok

> âœ… **Panitia berkomitmen** bahwa jadwal Kategori A (Analog) dan Kategori D (Digital) **tidak akan dijalankan secara paralel / bersamaan** pada babak manapun.
>
> Peserta yang mendaftar di kedua kategori **dijamin mendapat kesempatan bertanding di keduanya** tanpa konflik waktu. Urutan kategori yang tampil ditentukan oleh panitia dan diumumkan pada saat Technical Meeting.

---

## 3. REGULASI TEKNIS ROBOT

### 3.1 Dimensi Maksimum

| Parameter | **Kategori A (Analog)** | **Kategori D (Digital)** |
|-----------|------------------------|-------------------------|
| Panjang | maks. **20 cm** | maks. **25 cm** |
| Lebar | maks. **20 cm** | maks. **25 cm** |
| Tinggi | maks. **15 cm** | maks. **25 cm** |

> ðŸ“Œ Verifikasi dimensi menggunakan **kotak uji (inspection box)** resmi dari panitia â€” robot harus bisa masuk secara keseluruhan tanpa hambatan.
> Robot **dilarang** berubah bentuk, memperluas panel, atau menjatuhkan komponen apapun saat bergerak di lintasan.

### 3.2 Berat Maksimum

| Kategori | Berat Maks. | Toleransi |
|----------|------------|-----------|
| Kategori A (Analog) | **1,0 kg** | Â±50 gram (Â±5%) |
| Kategori D (Digital) | **1,5 kg** | Â±75 gram (Â±5%) |

> Berat diukur dalam kondisi **baterai terpasang dan terisi penuh** (kondisi siap bertanding).

### 3.3 Motor & Roda

| Komponen | Spesifikasi |
|----------|-------------|
| Jenis motor | Motor DC standar |
| Kecepatan motor | â‰¤ 250 RPM *(dengan gearbox, direkomendasikan)* |
| Diameter roda maksimum | **65 mm** |
| Lebar tapak ban maksimum | **30 mm** |

### 3.4 Sensor

| Kategori | Jumlah Sensor Maks. | Jenis Sensor yang Diizinkan |
|----------|---------------------|-----------------------------|
| Analog (A) | **4 sensor** | LDR, Fotodioda |
| Digital (D) | **10 sensor** | IR Inframerah Array, QTR Series, dan sejenisnya |

> ðŸ“Œ Termasuk sensor tambahan seperti ultrasonik/proximity **tidak dihitung** dalam kuota sensor garis, namun keberadaannya wajib dilaporkan saat homologasi.

### 3.5 Sumber Daya (Baterai)

- Robot wajib menggunakan **baterai onboard** â€” tidak ada kabel daya eksternal dalam kondisi apapun saat bertanding.
- **Tegangan maksimum yang diizinkan:**

| Kategori | Tegangan Maks. |
|----------|----------------|
| Kategori A â€” Analog | **9 Volt DC** |
| Kategori D â€” Digital | **12 Volt DC** |

| Jenis Baterai | Status |
|---------------|--------|
| Baterai kering (Dry Cell / AA) | âœ… Diizinkan |
| Gel Cell | âœ… Diizinkan |
| NiCad (Nikel-Kadmium) | âœ… Diizinkan |
| Li-Ion (Lithium-Ion) | âœ… Diizinkan |
| LiPo (Lithium Polymer) | âœ… Diizinkan |
| Baterai basah / berpotensi bocor cairan | âŒ **Dilarang keras** |

> âš ï¸ Panitia berhak **mengukur ulang voltase baterai** menggunakan multimeter kapan saja sebelum maupun setelah pertandingan tanpa pemberitahuan. Voltase melebihi batas = **diskualifikasi langsung**.

### 3.6 Ketentuan Tambahan

| Ketentuan | Status |
|-----------|--------|
| Aerodinamika aktif (kipas suction, EDF, turbin downforce) | âŒ **Dilarang** di semua kategori |
| Komponen berpotensi bocor (oli, pelumas cair) di lintasan | âŒ **Dilarang** |
| Bagian tajam yang berpotensi melukai orang/merusak lintasan | âŒ **Dilarang** |
| Kabel yang menjuntai / longgar keluar dari bodi robot | âŒ **Dilarang** |

---

## 4. SPESIFIKASI LINTASAN

### 4.1 Jenis & Dimensi Lintasan

Lintasan yang digunakan adalah **lintasan terbuka** (*open track*):
- Robot bergerak dari titik **Start** menuju titik **Finish** â€” bukan loop/melingkar.
- Lintasan **digelar langsung di atas lantai** *(bukan di atas meja/platform)*. Tinggi permukaan lintasan dari lantai = **0 cm** (rata lantai). Â²

**Dimensi area arena standar:**

| Elemen | Dimensi Standar | Referensi |
|--------|----------------|-----------|
| Panjang area arena | **minimum 4,5 meter** | RobotChallenge Â³ |
| Lebar area arena | **minimum 2,8 meter** | RobotChallenge Â³ |
| Panjang total jalur garis (path length) | **5â€“8 meter** | Standar kompetisi regional â´ |
| Lebar area start/finish | **minimum 50 cm** | Technocorner UGM âµ |

> ðŸ“Œ Untuk kompetisi edisi pertama dengan lintasan dasar, dimensi **minimum yang direkomendasikan** adalah area **3 meter Ã— 4 meter**. Peserta dapat menggunakan informasi ini untuk kalibrasi sensitivitas robot sebelum hari-H.

> ðŸ’¡ Lintasan digelar di atas lantai rata (bukan meja), sehingga **tidak ada risiko robot jatuh dari ketinggian**. Batas fisik arena hanya berupa penanda tali/pita di sekeliling area.

### 4.2 Material & Tampilan

| Parameter | Spesifikasi |
|-----------|-------------|
| Material dasar | **Banner cetak** (flex banner) |
| Warna dasar | **Putih bersih** |
| Warna garis panduan | **Hitam pekat** |
| Permukaan | **Matte / doff** (tidak mengkilap) |
| Sambungan lintasan | Disambung dengan **selotip hitam buram** (tidak reflektif) |
| Pencahayaan area | Pastikan merata, tanpa silau langsung ke permukaan lintasan |

### 4.3 Lebar Garis Panduan

| Kategori | Lebar Garis Hitam | Toleransi Cetak |
|----------|--------------------|-----------------|
| Kategori A â€” Analog | **28â€“30 mm** | Â±2 mm |
| Kategori D â€” Digital | **20 mm** | Â±2 mm (18â€“22 mm) |

### 4.4 Geometri Lintasan (Edisi Pertama â€” Lintasan Dasar)

| Elemen | Status | Spesifikasi Teknis |
|--------|--------|-------------------|
| âœ… **Tikungan Tajam** | **DIGUNAKAN** | Sudut 45Â°â€“65Â°, radius minimum 150 mm |
| âœ… **Garis Putus (Line Gap)** | **DIGUNAKAN** | Jeda/gap sepanjang 3â€“5 cm |
| âœ… **Persimpangan** | **DIGUNAKAN** | Tipe `T` (pertigaan) dan/atau `+` (palang) |
| âŒ Elevasi / Bukit | Tidak digunakan edisi ini | â€” |
| âŒ Obstacle / Penghalang | Tidak digunakan edisi ini | â€” |
| âŒ Inversi Warna | Tidak digunakan edisi ini | â€” |
| âŒ Terowongan Gelap | Tidak digunakan edisi ini | â€” |
| âŒ Persimpangan S / V / Z | Tidak digunakan edisi ini | â€” |

### 4.5 Ketentuan Kerahasiaan Lintasan

> ðŸ”’ **Desain spesifik lintasan Semifinal dan Final berbeda dari lintasan Penyisihan.**
> - Desain lintasan babak lanjut **tidak diperlihatkan kepada peserta sebelum babak tersebut dimulai**.
> - Lintasan Penyisihan dapat ditampilkan pada saat Technical Meeting sebagai preview.
> - Seluruh lintasan tetap menggunakan **elemen yang sama** (lihat tabel atas) â€” tidak ada elemen kejutan baru.

---

## 5. PROSEDUR PRA-PERTANDINGAN

### 5.1 Jadwal Registrasi

| Fase | Waktu | Keterangan |
|------|-------|-----------|
| Buka pendaftaran | H-30 | Publikasi panduan + buka formulir |
| Tutup pendaftaran | H-7 | **Tidak ada perpanjangan** |
| Konfirmasi & rekap | H-5 | Panitia menghubungi setiap tim |
| Technical Meeting | H-1 atau pagi H-0 | Lihat poin 5.2 |
| Homologasi | Pagi Hari-H | Lihat poin 5.3 |

**Dokumen wajib dilengkapi saat mendaftar:**
- [ ] Formulir pendaftaran (nama tim, nama anggota, jenjang, kategori yang diikuti)
- [ ] Scan / foto kartu pelajar / KTM / KTP **semua anggota tim**
- [ ] Foto robot tampak **depan, samping kiri, samping kanan, atas** (4 foto)
- [ ] Bukti pembayaran biaya pendaftaran

> âŒ Pendaftaran yang tidak melengkapi **semua** dokumen di atas sebelum batas waktu = **otomatis ditolak tanpa pemberitahuan lebih lanjut**.

### 5.2 Technical Meeting (TM)

- Dilaksanakan **H-1** atau **pagi Hari-H** *(minimal 1 jam sebelum homologasi dimulai)*.
- Wajib dihadiri **minimal 1 perwakilan resmi** yang namanya tercantum di formulir pendaftaran.

**Agenda TM:**
1. Pembacaan ulang aturan final oleh Ketua Panitia
2. Presentasi / preview **desain lintasan penyisihan** kepada peserta
3. Sesi tanya jawab terbuka *(semua pertanyaan wajib diajukan di sini, bukan saat lomba)*
4. **Pengundian nomor urut penampilan** secara transparan di depan seluruh perwakilan
5. Pembagian **nomor peserta resmi** dan formulir homologasi

> âš ï¸ **Konsekuensi tidak hadir di TM:**
> - Kehilangan hak undian â†’ urutan penampilan ditentukan panitia secara acak.
> - **Kehilangan hak untuk mengajukan keberatan/protes** atas keputusan apapun sepanjang kompetisi.
> - Wajib menerima dan mematuhi seluruh keputusan panitia tanpa sanggahan.

### 5.3 Homologasi / Scrutineering (Hari-H, Sebelum Pertandingan)

Semua robot **wajib lolos** pemeriksaan teknis sebelum diizinkan masuk arena pertandingan:

| Item Pemeriksaan | Metode | Syarat Lulus |
|-----------------|--------|--------------|
| **Dimensi** | Kotak uji (inspection box) | Masuk sempurna tanpa hambatan |
| **Berat** | Timbangan digital | â‰¤ batas + toleransi Â±5% |
| **Tegangan baterai** | Multimeter | â‰¤ batas voltase kategori |
| **Modul nirkabel** | Inspeksi visual + scanning | Tidak ada RF / BT / WiFi |
| **Jenis teknologi** | Inspeksi komponen | Sesuai kategori yang didaftarkan |
| **Keamanan komponen** | Inspeksi visual | Tidak ada cairan bocor, bagian tajam, kabel menjuntai |
| **Identifikasi robot** | Foto vs fisik robot | Sesuai 4 foto yang dikirim saat pendaftaran |
| **Motor & roda** | Pengukuran fisik | Diameter roda â‰¤ 65mm, lebar tapak â‰¤ 30mm |

**Alur bila gagal homologasi:**
1. Tim diberi waktu **maksimal 5 menit** untuk perbaikan di tempat (area homologasi).
2. Setelah 5 menit, diuji ulang **sekali** oleh petugas yang sama.
3. Jika tetap gagal â†’ **robot gugur**, tim tidak diizinkan bertanding di kategori tersebut.

**Bila lulus:**
- Robot diberi **stiker / label homologasi resmi** + **label nomor peserta** dari panitia.
- Label ini wajib menempel selama kompetisi berlangsung. Jika terlepas â†’ lapor ke panitia segera.
- Tim diizinkan masuk ke **zona pit stop** yang telah disiapkan.
- Modifikasi signifikan pasca-homologasi wajib **dilaporkan ke panitia** untuk pemeriksaan ulang.

---

## 6. FORMAT & MEKANISME PERTANDINGAN

### 6.1 Struktur Babak (Standar â€” Peserta â‰¥ 9 Tim)

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚          BABAK PENYISIHAN  (Hari 1)               â”‚
â”‚  Format : TIME TRIAL (solo, bergantian per tim)   â”‚
â”‚  Run    : 2 run per tim â€” diambil WAKTU TERBAIK   â”‚
â”‚  Jeda   : 5 menit antar run (tuning di pit stop)  â”‚
â”‚  Catatan: Kat. A dan D terpisah jalur/waktu       â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                  â†“  Top 8 waktu tercepat tiap kategori maju
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚          BABAK SEMIFINAL  (Hari 2, sesi 1)        â”‚
â”‚  Format : TIME TRIAL (lintasan baru)              â”‚
â”‚  Run    : 2 run per tim â€” diambil WAKTU TERBAIK   â”‚
â”‚  Jeda   : 5 menit antar run (tuning di pit stop)  â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
     Top 2 maju   â†“              â†“  Peringkat 3 & 4 bersaing
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚          BABAK FINAL  (Hari 2, sesi 2)            â”‚
â”‚  Format : BATTLE MODE â€” Head-to-Head              â”‚
â”‚  Posisi jalur start ditentukan lewat UNDIAN       â”‚
â”‚  2 robot terbaik berpacu bersamaan                â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

### 6.2 Contingency â€” Format Alternatif (Peserta Sedikit)

| Jumlah Tim per Kategori | Format yang Digunakan |
|-------------------------|-----------------------|
| â‰¥ 9 tim | Format standar: Penyisihan â†’ Semifinal â†’ Final |
| 5â€“8 tim | **Penyisihan dihapus** â†’ Langsung Semifinal (Top 4) â†’ Final |
| 3â€“4 tim | **Langsung Final** â€” semua tim bertanding Time Trial, lalu Top 2 Battle Final |
| â‰¤ 2 tim | Kategori digabung atau hanya Time Trial tanpa babak Battle |

> ðŸ“Œ Format yang berlaku diumumkan **pada saat Technical Meeting** setelah jumlah peserta akhir dikonfirmasi.

### 6.3 Penentuan Juara 3

- Juara 3 **tidak memerlukan babak playoff** tersendiri.
- Juara 3 = robot dengan **peringkat ke-3 terbaik dari hasil Semifinal** (waktu terbaik dari 2 robot yang kalah di semifinal).
- Jika waktu kedua robot yang kalah **identik** â†’ diadakan **1 run Time Trial tambahan** untuk menentukan Juara 3.

### 6.4 Ketentuan Waktu Per Run

| Parameter | Ketentuan |
|-----------|-----------|
| Waktu persiapan di start line | **Maksimum 2 menit** sejak dipanggil masuk area start |
| Waktu maksimum per run | **3 menit (180 detik)** setelah sinyal start |
| Syarat finis sah | Robot **berhenti â‰¥ 5 detik** di dalam kotak finish setelah melewati garis akhir |
| Jika tidak finis dalam 3 menit | Dicatat berdasarkan **jarak terjauh** yang dicapai |
| Jeda antar run (run 1 â†’ run 2) | **5 menit** â€” tim boleh tuning di pit stop |
| Pengukur waktu | Stopwatch digital / sensor inframerah di garis Start & Finish |

### 6.5 Kalibrasi Sensor di Garis Start

> ðŸ“Œ **Ketentuan kalibrasi robot sebelum sinyal start:**
>
> - Selama **2 menit waktu persiapan**, tim boleh melakukan **kalibrasi sensor otomatis** (menekan tombol + menyapukan robot di atas garis) selama robot **belum melangkahi titik start**.
> - Kalibrasi yang dilakukan **setelah robot melewati/berada di atas garis start** namun **sebelum sinyal start dibunyikan** = diizinkan, selama tidak menggerakkan robot maju ke lintasan.
> - Segala bentuk **penyesuaian perangkat lunak jarak jauh (laptop/HP)** selama robot berada di area start = **DILARANG**.

### 6.6 Alur Satu Run (Prosedur Lengkap)

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚  1. Panitia memanggil tim (nomor urut undian)    â”‚
â”‚  2. Tim masuk area start â€” WAKTU PERSIAPAN 2'    â”‚
â”‚  3. Tim atur posisi robot + kalibrasi sensor     â”‚
â”‚  4. Seluruh anggota tim mundur dari lintasan     â”‚
â”‚  5. Panitia beri aba-aba "SIAP!" â€” robot diam    â”‚
â”‚  6. Peluit / sinyal start â†’ â±ï¸ TIMER MULAI       â”‚
â”‚  7. Robot bergerak otonom di lintasan            â”‚
â”‚  8a. Robot lewati garis Finish â†’ timer berhenti  â”‚
â”‚  8b. 3 menit habis â†’ peluit panitia â†’ stop       â”‚
â”‚  9. Jarak terjauh dicatat (jika tidak finis)     â”‚
â”‚  10. Tim ambil robot setelah izin wasit          â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

> âŒ Tim **dilarang** mendekati atau menyentuh robot selama run berlangsung, kecuali dalam prosedur Retry yang sah (Bab 9).

### 6.7 Klausul Gangguan Teknis & Force Majeure

Jika terjadi gangguan di luar kendali peserta selama run berlangsung:

| Kondisi | Penanganan |
|---------|-----------|
| **Listrik padam / timer rusak** | Run dihentikan sementara, diulangi dari awal (jatah run tidak berkurang) |
| **Lintasan rusak** bukan karena robot peserta | Run dihentikan, lintasan diperbaiki, run diulangi dari awal |
| **Gangguan dari luar** (orang lain menabrak lintasan, dll.) | Run dihentikan, diulangi dari awal |
| **Lintasan rusak karena robot peserta** | Run dihentikan, jarak dicatat sampai titik kerusakan, tim menanggung biaya perbaikan ringan |

> Keputusan dalam kondisi force majeure merupakan **hak mutlak Ketua Wasit** â€” tidak dapat diprotes.

---

## 7. TATA TERTIB AREA LOMBA

### 7.1 Peta Zona Area Lomba

| Zona | Akses | Keterangan |
|------|-------|-----------|
| ðŸ”´ **Area Lintasan** | Panitia & wasit saja (saat run) | Tim masuk hanya saat giliran dan seizin wasit |
| ðŸŸ¡ **Area Start/Finish** | Tim saat giliran tampil | Maksimum **2 orang** dari tim boleh masuk |
| ðŸŸ¢ **Pit Stop** | Tim terdaftar saja | Zona eksklusif perbaikan & tuning robot |
| âšª **Area Penonton/Tunggu** | Umum | Tim yang tidak sedang tampil menunggu di sini |
| ðŸ“· **Zona Fotografer** | Media / dokumentasi panitia | Hanya dari luar batas tali arena, tidak boleh masuk area lintasan |

### 7.2 Aturan Alas Kaki di Area Lintasan

> ðŸ‘Ÿ **WAJIB DIPATUHI â€” Berlaku untuk SEMUA orang: peserta, panitia, wasit, dan tamu**
>
> Siapapun yang **menginjak permukaan lintasan** (banner cetak):
> - **WAJIB melepas alas kaki** terlebih dahulu
> - Hanya boleh menggunakan **kaos kaki bersih**
>
> Alas kaki bersol keras, sepatu, sandal, atau alas kaki apapun dapat mengikis dan mengotori permukaan banner yang berdampak langsung pada akurasi sensor robot.
>
> ðŸ’¡ Panitia disarankan menyediakan **kaos kaki cadangan** bagi peserta yang lupa.

### 7.3 Aturan Fotografi & Pencahayaan Saat Run Berlangsung

> ðŸ“¸ **WAJIB DIPATUHI â€” Berlaku saat robot sedang berjalan di lintasan**

| Ketentuan | Status | Alasan |
|-----------|--------|--------|
| **Flash kamera** (HP, DSLR, mirrorless) | âŒ **DILARANG** saat run berlangsung | Kilatan cahaya IR dapat membutakan / mengacaukan sensor fotodioda dan IR array robot secara permanen â¶ |
| **Lampu sorot / spotlight** diarahkan ke lintasan | âŒ **DILARANG** saat run berlangsung | Sama seperti di atas |
| Foto/video tanpa flash dari area penonton | âœ… Diizinkan | â€” |
| Dokumentasi panitia (non-flash) | âœ… Diizinkan dari zona fotografer | â€” |

> âš ï¸ Jika flash kamera dari penonton menyebabkan robot gagal/crash saat run berlangsung, wasit **berhak memutuskan run diulang** atas kebijaksanaan Ketua Wasit. Identitas pelaku flash dicatat dan diperingatkan.

### 7.4 Dress Code Peserta

| Ketentuan | Status |
|-----------|--------|
| Pakaian sopan (kemeja, polo, kaos berkerah) | âœ… Dianjurkan |
| Kaos biasa yang bersih & tidak menyinggung | âœ… Diizinkan |
| Seragam tim dengan nama/logo tim | âœ… **Sangat dianjurkan** |
| Kaos tanpa lengan (*singlet*) | âŒ Tidak diizinkan |
| Celana pendek di atas lutut | âŒ Tidak diizinkan |
| Pakaian bertulisan / bergambar tidak pantas | âŒ Tidak diizinkan |

> Tim yang melanggar â†’ **peringatan lisan**. Jika tidak diindahkan â†’ **tidak diizinkan masuk area pertandingan** hingga mematuhi aturan.

### 7.4 Aturan Pit Stop

Pit stop adalah **satu-satunya zona** di mana anggota tim boleh melakukan modifikasi:

| Aktivitas | Status |
|-----------|--------|
| Mengganti baterai | âœ… Diizinkan |
| Mengubah parameter tuning (kecepatan, PID, threshold) | âœ… Diizinkan |
| Upload ulang kode program | âœ… Diizinkan |
| Kalibrasi ulang sensor (offline, di pit stop) | âœ… Diizinkan |
| Memperbaiki komponen mekanik kecil yang longgar | âœ… Diizinkan |
| Mengganti motor / board mikrokontroler utama | âš ï¸ Wajib lapor ke panitia untuk pemeriksaan ulang |
| Mengubah dimensi sasis secara signifikan | âŒ Dilarang tanpa homologasi ulang |
| Membawa robot ke luar venue tanpa izin panitia | âŒ Dilarang |

---

## 8. SISTEM PENILAIAN

### 8.1 Babak Penyisihan & Semifinal â€” TIME TRIAL

> **Prinsip: Robot tercepat menyelesaikan lintasan dari Start ke Finish = peringkat tertinggi.**

**Syarat run dinyatakan VALID:**
- Robot menyelesaikan lintasan dari **Start hingga Finish** dalam batas 3 menit.
- Robot **berhenti minimal 5 detik** di dalam kotak Finish setelah melewati garis akhir.
- Waktu direkam oleh sensor/stopwatch di garis Start dan Finish.

**Penentuan Ranking:**

| Prioritas | Kriteria | Berlaku Jika |
|-----------|---------|-------------|
| 1ï¸âƒ£ **Utama** | Waktu tercepat finis (detik) | Ada minimal 1 robot yang berhasil finis |
| 2ï¸âƒ£ **Cadangan** | Jarak terjauh (cm) | Tidak ada robot yang berhasil finis |
| 3ï¸âƒ£ **Tie-breaker** | Run ulang 1 kali | Waktu / jarak benar-benar identik |

**Pengambilan nilai:**
- Setiap tim mendapat **2 run**.
- Yang diambil = **waktu terbaik** (run tercepat yang valid di antara 2 run).
- Jika kedua run gagal finis â†’ nilai = **jarak terjauh** dari kedua run.
- Jika kedua run tidak bergerak sama sekali (0 cm) â†’ nilai = 0, peringkat terbawah.

---

### 8.2 Babak Final â€” BATTLE MODE (HEAD-TO-HEAD)

> **Dua robot terbaik berpacu bersamaan di satu lintasan secara serentak.**

**Persiapan Final Battle:**
1. Dilakukan **undian posisi start** (jalur kiri vs. jalur kanan) oleh Ketua Wasit di hadapan kedua tim.
2. Kedua robot ditempatkan di posisi start masing-masing.
3. Panitia membunyikan "SIAP!" â†’ kedua tim mundur dari lintasan.
4. Panitia membunyikan sinyal start â†’ **kedua robot berjalan bersamaan**.

**Sistem Poin Battle Mode (4-Tier):**

| Kondisi | Poin | Keterangan |
|---------|------|-----------|
| ðŸ¥‡ **Finis pertama** â€” lewati garis finish lebih cepat | **3 poin** | Kemenangan mutlak |
| ðŸ **Finis kedua** â€” berhasil finis meski kalah waktu | **1 poin** | Kalah tapi finis |
| ðŸ“ **Tidak finis, jarak lebih jauh** â€” jarak lebih jauh dari lawan yang juga tidak finis | **2 poin** | Menang berdasarkan jarak |
| ðŸ’€ **Tidak finis, jarak lebih pendek** â€” jarak lebih pendek dari lawan | **0 poin** | Kekalahan total |

**Tabel skenario lengkap:**

| Skenario | Robot A | Robot B |
|----------|---------|---------|
| A finis duluan, B finis juga | **3 poin** | 1 poin |
| A finis duluan, B tidak finis | **3 poin** | 0 poin |
| Keduanya tidak finis, A lebih jauh | **2 poin** | 0 poin |
| A tidak finis, B finis | 0 poin | **3 poin** |
| Keduanya tidak finis, jarak sama persis | Rematch | Rematch |

**Rematch:**
- Jika jarak **benar-benar identik** â†’ **rematch**, maksimum **2 kali**.
- Jika setelah 2 rematch masih imbang â†’ keputusan **Ketua Wasit bersifat mutlak dan final**.

---

## 9. ATURAN RETRY & PENALTI

### 9.1 Batas Retry (Hak Angkat Robot)

**Retry** = tim mengangkat robot yang crash/keluar jalur dan menempatkan kembali di titik yang sah.

| Babak | Maks. Retry per Run | Catatan |
|-------|---------------------|---------|
| **Penyisihan** | **8 kali** | Toleransi penuh untuk uji kalibrasi |
| **Semifinal** | **5 kali** | Mulai diperketat |
| **Final (Battle Mode)** | **3 kali** | Batas elite |

> â±ï¸ **Timer TIDAK berhenti** selama proses retry berlangsung. Waktu terus berjalan.

**Prosedur Retry yang SAH â€” wajib diikuti urutan ini:**

```
LANGKAH 1: Anggota tim angkat SATU TANGAN, ucapkan "RETRY!" dengan keras
LANGKAH 2: Tunggu â†’ wasit membunyikan PELUIT TANDA IZIN
LANGKAH 3: Baru boleh menyentuh dan mengangkat robot
LANGKAH 4: Robot dikembalikan ke titik START
           (jika ada checkpoint yang sudah dilalui: ke checkpoint terakhir)
LANGKAH 5: Anggota tim mundur dari lintasan
LANGKAH 6: Wasit beri sinyal lanjut â†’ robot distart kembali
```

> âŒ **DILARANG KERAS:**
> - Menyentuh robot sebelum ada peluit izin dari wasit
> - Meletakkan robot di titik tempat crash â†’ harus kembali ke Start atau checkpoint terakhir
> - Memperbaiki atau memodifikasi komponen apapun selama proses retry (hanya diatur posisi)

### 9.2 Kondisi yang Mewajibkan Retry atau Penghentian Run

Selain atas permintaan tim, wasit **berhak memerintahkan** retry atau menghentikan run jika:

| Kondisi | Tindakan Wasit |
|---------|----------------|
| Robot **diam/stuck > 3 detik** tanpa bergerak sama sekali | Perintahkan tim deklarasi retry, atau nyatakan run selesai di titik tersebut |
| Robot **jatuh keluar dari area fisik lintasan** (ke lantai) | Hentikan run â€” robot diangkat tim, retry jika jatah masih ada |
| Robot **mengeluarkan asap / bau terbakar** | Hentikan run seketika â€” robot diangkat langsung oleh tim |
| Robot **merusak permukaan lintasan** | Hentikan run, evaluasi kerusakan, putuskan apakah run diulang |
| Robot **terus berputar di satu titik > 5 detik** | Wasit memperingatkan tim, jika tidak ada retry yang diminta â†’ run dinyatakan selesai |

> âš ï¸ **Catatan jatuh dari lintasan:** Robot yang jatuh ke lantai diangkat oleh **tim** (bukan wasit). Wasit hanya boleh menyentuh robot dalam kondisi darurat keselamatan (kebakaran, asap, dll.).

### 9.3 Penalti Waktu (+5 Detik â€” berlaku di Time Trial)

| No. | Pelanggaran | Keterangan |
|-----|------------|-----------|
| 1 | **False Start** | Robot bergerak sebelum sinyal start resmi dari wasit |
| 2 | **Push Start** | Anggota tim mendorong / memberi momentum fisik pada robot saat start atau restart retry |
| 3 | **Sentuh tanpa izin** | Menyentuh robot di lintasan tanpa izin dan peluit wasit |
| 4 | **Terlambat ke arena** | Tim belum siap di area start setelah **2 menit** dipanggil |

> ðŸ“ Penalti dicatat oleh **wasit lini** dan diumumkan oleh Ketua Wasit setelah run selesai. Tim tidak boleh protes saat run masih berlangsung.

### 9.4 Sistem Peringatan di Battle Mode Final

Penalti +5 detik **tidak berlaku** di Battle Mode. Gantinya:

| Kejadian | Tindakan |
|---------|---------|
| Pelanggaran ringan pertama | **Peringatan lisan** dari wasit |
| Pelanggaran kedua | **Robot dinyatakan gugur di laga tersebut â†’ 0 poin** |
| Interferensi fisik sengaja ke robot lawan | **Langsung gugur â†’ 0 poin**, tanpa peringatan |

---

## 10. DISKUALIFIKASI

Tim akan **langsung didiskualifikasi tanpa hak banding** jika terbukti melakukan:

| No. | Pelanggaran | Detail |
|-----|-------------|--------|
| 1 | ðŸš« **Remote Control** | Penggunaan kendali nirkabel (Bluetooth, WiFi, RF, IR remote) saat robot di lintasan |
| 2 | ðŸš« **Ganti Hardware di Lintasan** | Mengganti komponen (chip, baterai, kabel, sensor) di dalam/atas area lintasan tanpa izin resmi |
| 3 | ðŸš« **Substitusi Robot Ilegal** | Menukar robot dengan unit lain yang tidak terdaftar / dimodifikasi signifikan pasca-homologasi |
| 4 | ðŸš« **Membahayakan Keselamatan** | Robot bocor cairan, mengeluarkan asap/api, meledak, atau melukai orang |
| 5 | ðŸš« **Absen 3 Kali Panggilan** | Tidak merespons 3 kali panggilan berturut-turut dari panitia di babak manapun |
| 6 | ðŸš« **Curang / Sabotase** | Memanipulasi data waktu, merusak robot tim lain, atau kecurangan sistematis |
| 7 | ðŸš« **Pelanggaran Etika Berat** | Intimidasi, penghinaan, ancaman, atau tindakan kekerasan fisik |

**Prosedur diskualifikasi:**
1. Ketua Wasit mengumpulkan bukti (kesaksian wasit lini, rekaman video jika ada).
2. Tim dipanggil dan diberi kesempatan klarifikasi **maksimal 2 menit**.
3. Ketua Wasit mengumumkan keputusan â€” **bersifat final, tidak dapat diganggu gugat**.
4. Stiker homologasi robot dicabut. Tim diminta meninggalkan area pertandingan dengan tertib.

---

## 11. DEWAN WASIT & PROSEDUR BANDING

### 11.1 Struktur Dewan Wasit

| Jabatan | Jumlah | Tugas Utama |
|---------|--------|-------------|
| **Ketua Wasit (Chief Referee)** | 1 orang | Keputusan tertinggi, diskualifikasi, penyelesaian sengketa, force majeure |
| **Wasit Lini** | 2 orang | Mengawasi jalannya run, mencatat penalti, memantau retry, jaga area lintasan |
| **Pencatat Waktu (Timer Officer)** | 1 orang | Mengoperasikan stopwatch, mencatat & mengumumkan hasil setiap run |
| **Petugas Homologasi** | 2 orang | Memeriksa dimensi, berat, voltase, dan kepatuhan teknis robot |

> ðŸ… Keputusan **Ketua Wasit** adalah keputusan tertinggi. Tidak ada jalur banding di atas Ketua Wasit.

### 11.2 Prosedur Banding / Protes Resmi

```
LANGKAH 1 â€” dalam 5 menit setelah kejadian/keputusan:
   Tim LISAN mengajukan keberatan ke Wasit Lini

LANGKAH 2:
   Wasit Lini melaporkan ke Ketua Wasit

LANGKAH 3:
   Ketua Wasit mendengar kedua pihak
   (masing-masing maksimum 3 menit berbicara)

LANGKAH 4 â€” maksimum 10 menit setelah protes diterima:
   Ketua Wasit mengumumkan keputusan akhir

LANGKAH 5:
   Keputusan BERSIFAT FINAL â€” tidak ada banding lebih lanjut
```

**Batas waktu pengajuan protes:**

| Jenis Protes | Batas Waktu |
|-------------|-------------|
| Atas hasil run / waktu | â‰¤ **5 menit** setelah hasil diumumkan |
| Atas keputusan homologasi | Sebelum babak pertandingan pertama dimulai |
| Atas keputusan diskualifikasi | Segera saat keputusan diumumkan *(lewat prosedur di atas)* |
| Protes di luar batas waktu | **Tidak akan diproses** |

> âš ï¸ Tim yang **tidak hadir di Technical Meeting** kehilangan **hak banding sepenuhnya** atas keputusan apapun sepanjang kompetisi.

---

## 12. HADIAH & PENGHARGAAN

### 12.1 Struktur Penghargaan

Setiap kategori (**Analog** dan **Digital**) memiliki juara **terpisah dan mandiri**:

| Peringkat | Penghargaan |
|-----------|-------------|
| ðŸ¥‡ **Juara 1** | Uang pembinaan + Tropi Emas + Sertifikat Juara 1 |
| ðŸ¥ˆ **Juara 2** | Uang pembinaan + Tropi Perak + Sertifikat Juara 2 |
| ðŸ¥‰ **Juara 3** | Uang pembinaan + Tropi Perunggu + Sertifikat Juara 3 |
| ðŸŒŸ **Juara Harapan** *(opsional)* | Plakat + Sertifikat Juara Harapan |
| ðŸŽ¨ **Best Design** *(opsional)* | Tropi Desain Terbaik + Uang pembinaan + Sertifikat |
| âœ… **Seluruh Tim Peserta** | Sertifikat Partisipasi resmi berlogo panitia |

### 12.2 Referensi Nominal Hadiah (Acuan Anggaran)

| Peringkat | Technocorner UGM | IPB MBF | Rekomendasi Minimal |
|-----------|-----------------|---------|---------------------|
| Juara 1 | Rp 5.000.000 | Rp 2.000.000 | Rp 500.000 |
| Juara 2 | Rp 3.500.000 | Rp 1.500.000 | Rp 300.000 |
| Juara 3 | Rp 1.500.000 | Rp 1.000.000 | Rp 200.000 |
| Harapan | Rp 1.000.000 | â€” | Rp 100.000 |
| Best Design | Rp 750.000 | â€” | Rp 150.000 |

> ðŸ’¡ Hadiah **uang tunai bersifat opsional** â€” yang terpenting adalah tropi dan sertifikat resmi sebagai bukti prestasi akademik peserta.

### 12.3 Kriteria Best Design *(Opsional)*

| Kriteria Penilaian | Bobot |
|--------------------|-------|
| Kerapian manajemen kabel (*cable management*) | 30% |
| Orisinalitas dan kreativitas desain sasis | 30% |
| Estetika keseluruhan (warna, finishing, identitas tim) | 20% |
| Portofolio / dokumentasi teknis desain | 20% |

---

## 13. CONTOH JADWAL HARI-H

> Jadwal ini bersifat **panduan** dan dapat disesuaikan dengan jumlah tim peserta.

### Asumsi: 16 tim per kategori (32 tim total, 2 kategori)

| Waktu | Kegiatan |
|-------|----------|
| 07.00 | Venue dibuka, panitia bersiap |
| 07.30 | **Homologasi** dimulai â€” Kat. A dan D paralel |
| 09.00 | Homologasi selesai, pengumuman robot lulus |
| 09.15 | Briefing terakhir wasit + panitia |
| 09.30 | **Babak Penyisihan Kategori A** (Analog) dimulai |
| 11.00 | Penyisihan Kat. A selesai â†’ pengumuman Top 8 |
| 11.15 | **Babak Penyisihan Kategori D** (Digital) dimulai |
| 13.00 | ISHOMA â€” jeda makan siang |
| 13.45 | Penyisihan Kat. D selesai â†’ pengumuman Top 8 |
| 14.00 | Ganti lintasan (pasang lintasan semifinal) |
| 14.15 | **Babak Semifinal Kategori A** (Top 8) |
| 15.15 | Semifinal Kat. A selesai â†’ umumkan Juara 3 + 2 Finalis |
| 15.30 | **Babak Semifinal Kategori D** (Top 8) |
| 16.30 | Semifinal Kat. D selesai â†’ umumkan Juara 3 + 2 Finalis |
| 16.45 | Ganti lintasan (pasang lintasan final) |
| 17.00 | **Babak Final Kat. A â€” Battle Mode** |
| 17.20 | **Babak Final Kat. D â€” Battle Mode** |
| 17.40 | **Pengumuman & Penyerahan Hadiah** |
| 18.00 | Foto bersama, acara selesai |

> â±ï¸ Estimasi waktu per tim di penyisihan: ~8 menit (2 run Ã— 3 menit + jeda 5 menit). Untuk 16 tim = Â±128 menit â‰ˆ 2 jam per kategori.

---

## 14. CHECKLIST PANITIA

### ðŸ“‹ H-30 â€” Persiapan Awal
- [ ] Finalisasi panduan dan publikasikan ke calon peserta
- [ ] Buka formulir pendaftaran online
- [ ] Tentukan nominal hadiah + cari sponsor jika perlu
- [ ] Desain lintasan penyisihan (kirim ke vendor cetak banner)
- [ ] Desain lintasan semifinal & final *(simpan rahasia)*
- [ ] Konfirmasi ketersediaan venue

### ðŸ“‹ H-14 â€” Dua Minggu Sebelum
- [ ] Buat / pesan inspection box (kotak uji dimensi) untuk Kat. A dan D
- [ ] Beli: timbangan digital, multimeter, stopwatch/timer digital, meteran
- [ ] Rekrut wasit: 1 Ketua Wasit, 2 Wasit Lini, 1 Timer Officer, 2 Petugas Homologasi
- [ ] Cetak: formulir homologasi, lembar penilaian, stiker label homologasi, label nomor peserta
- [ ] Siapkan perlengkapan pit stop (meja, kursi, power strip untuk charging)
- [ ] Siapkan kaos kaki cadangan untuk peserta yang lupa (opsional tapi dianjurkan)

### ðŸ“‹ H-7 â€” Seminggu Sebelum
- [ ] Tutup pendaftaran â€” rekap daftar peserta final per kategori
- [ ] Verifikasi kelengkapan dokumen semua tim
- [ ] Konfirmasi pembayaran semua tim
- [ ] Kirim reminder TM kepada seluruh perwakilan tim
- [ ] Terima & cek kualitas cetakan banner lintasan penyisihan
- [ ] Briefing internal seluruh panitia & wasit â€” bacakan panduan bersama

### ðŸ“‹ H-1 â€” Sehari Sebelum
- [ ] Pasang lintasan penyisihan di venue â€” **uji dengan robot panitia** (wajib!)
- [ ] Cek pencahayaan: tidak ada silau, bayangan, atau refleksi ke permukaan lintasan
- [ ] Pasang penanda zona (area lintasan, area start/finish, pit stop, area penonton)
- [ ] Lakukan **Technical Meeting** â€” hadirkan semua perwakilan tim
- [ ] Umumkan nomor urut penampilan hasil undian di TM
- [ ] Siapkan sistem dokumentasi (kamera/HP + tripod untuk merekam setiap run)
- [ ] Test stopwatch / sensor inframerah garis finish

### ðŸ“‹ Hari-H â€” Pagi
- [ ] Buka venue 30 menit sebelum jadwal homologasi
- [ ] Mulai **proses homologasi** â€” Kat. A dan D paralel
- [ ] Tempelkan stiker homologasi + label nomor peserta ke robot yang lulus
- [ ] Umumkan robot yang tidak lulus (dengan alasan jelas)
- [ ] Pastikan semua wasit sudah di posisi sebelum pertandingan dimulai
- [ ] Test ulang sistem timer

### ðŸ“‹ Hari-H â€” Pertandingan
- [ ] Jalankan Penyisihan Kat. A â†’ rekap â†’ umumkan Top 8
- [ ] Jalankan Penyisihan Kat. D â†’ rekap â†’ umumkan Top 8
- [ ] Pasang lintasan baru (Semifinal) â€” pastikan peserta tidak melihat proses ini
- [ ] Jalankan Semifinal Kat. A â†’ rekap â†’ umumkan Juara 3 dan 2 Finalis
- [ ] Jalankan Semifinal Kat. D â†’ rekap â†’ umumkan Juara 3 dan 2 Finalis
- [ ] Pasang lintasan Final
- [ ] Lakukan undian posisi start Battle Final (Kat. A, lalu Kat. D)
- [ ] Jalankan Final Battle Kat. A â†’ umumkan Juara 1 & 2
- [ ] Jalankan Final Battle Kat. D â†’ umumkan Juara 1 & 2

### ðŸ“‹ Hari-H â€” Penutupan
- [ ] Pengumuman semua pemenang (Juara 1, 2, 3 tiap kategori)
- [ ] Penyerahan tropi, plakat, hadiah uang pembinaan
- [ ] Foto bersama semua pemenang
- [ ] Buka sesi keberatan resmi (**15 menit** â€” setelah itu ditutup)
- [ ] Informasikan jadwal pengiriman sertifikat ke seluruh peserta

### ðŸ“‹ Pasca Pertandingan
- [ ] Publikasikan rekap waktu/nilai seluruh peserta (transparansi)
- [ ] Cetak dan kirim sertifikat partisipasi ke semua tim
- [ ] Laporan pertanggungjawaban kegiatan
- [ ] Backup dokumentasi foto & video
- [ ] Evaluasi internal panitia + kumpulkan feedback peserta untuk edisi berikutnya

---

## RINGKASAN KEPUTUSAN FINAL

| Parameter | Keputusan |
|-----------|-----------|
| **Target peserta** | SMP ke atas (SMP, SMA/SMK, Mahasiswa, Umum) |
| **Kategori resmi** | **2 kategori: Analog (A) & Digital (D)** â€” berjalan terpisah |
| **SMP di Kategori Digital** | âœ… **Diizinkan** â€” tidak ada pembatasan berdasarkan jenjang |
| **Lintasan** | **Dasar** â€” Tikungan tajam, garis putus, persimpangan T/+ |
| **Elemen lanjutan** | âŒ Tidak digunakan (elevasi, obstacle, inversi, S/V/Z) |
| **Jenis lintasan** | Terbuka (*open track*) â€” Start ke Finish, bukan loop |
| **Format penyisihan** | **Time Trial** â€” 2 run, ambil waktu terbaik |
| **Format semifinal** | **Time Trial** â€” 2 run, lintasan baru, ambil waktu terbaik |
| **Format final** | **Battle Mode Head-to-Head** â€” sistem poin 4-tier (3/2/1/0) |
| **Penentuan Juara 3** | Dari data peringkat 3 semifinal (tanpa babak playoff) |
| **Posisi start Battle** | Ditentukan lewat **undian** sebelum Final |
| **Retry penyisihan** | **8 kali** per run |
| **Retry semifinal** | **5 kali** per run |
| **Retry final** | **3 kali** per run |
| **Waktu persiapan start** | 2 menit sejak dipanggil masuk area start |
| **Kalibrasi sensor di start** | âœ… Diizinkan selama masa persiapan 2 menit |
| **Jeda antar run** | 5 menit untuk tuning di pit stop |
| **Alas kaki di lintasan** | âŒ Wajib lepas â€” hanya kaos kaki saja |
| **Aerodinamika aktif** | âŒ Dilarang semua kategori |
| **Remote control** | âŒ Diskualifikasi langsung |
| **Penandaan robot** | âœ… Wajib: label nama tim + nomor peserta dari panitia |
| **Contingency peserta sedikit** | Format disesuaikan â€” diumumkan di TM |
| **Force majeure** | Keputusan Ketua Wasit mutlak |
| **Hadiah** | Ditentukan menyusul â€” struktur & referensi sudah tercantum |

| **Batas tim per institusi** | Maks. **3 tim per kategori** per institusi |
| **Tim lintas jenjang** | Dikategorikan berdasarkan jenjang tertinggi anggota |
| **Jaminan jadwal** | Kat. A dan D **tidak berjalan bersamaan** |
| **Dimensi arena** | Min. 3m Ã— 4m (rekomendasi dasar); standar internasional 4,5m Ã— 2,8m |
| **Posisi lintasan** | **Di lantai** (0 cm elevasi) â€” bukan di meja |
| **Flash kamera** | âŒ Dilarang saat run berlangsung |

---

## DAFTAR REFERENSI

Panduan ini disusun berdasarkan regulasi kompetisi resmi berikut:

| No. | Referensi | Sumber |
|-----|-----------|--------|
| Â¹ | Batas 3 tim per institusi per kategori | Adaptasi dari Technocorner UGM 2016 â€” *Petunjuk Teknis Line Follower Competition* |
| Â² | Lintasan digelar di atas lantai (0 cm) | Standar umum kompetisi LFR regional Indonesia; Robotex International Line Following Rules |
| Â³ | Dimensi arena 4,5m Ã— 2,8m | **RobotChallenge â€” *Line Follower Rules*** (RC-LineFollower.pdf) â€” arena internasional resmi |
| â´ | Panjang total jalur 5â€“8 meter | Standar kompetisi regional: MRC VIII, ELCCO Udayana, Technocorner UGM |
| âµ | Lebar area start/finish minimum 50 cm | **Technocorner UGM 2016** â€” *Petunjuk Teknis LFC* |
| â¶ | Larangan flash kamera (sensor IR interference) | **MEB Robot Turkey 2023** â€” *line follower robot category rules*; RoboCore Line Follower Rules (Brazil) |
| â€” | Dimensi robot Analog (20Ã—20Ã—15 cm, 1 kg) | **Technocorner UGM 2016**; **MEB Robot Turkey 2024** |
| â€” | Dimensi robot Digital (25Ã—25Ã—25 cm, 1,5 kg) | **MRC VIII** â€” *Rule Line Follower Digital SMP* |
| â€” | Voltase maks. 12V DC | **MEB Robot Turkey 2024**; **RobotChallenge** |
| â€” | Sensor Analog maks. 4, Digital maks. 10 | **MRC VIII**; **MEB Robot Turkey 2023** |
| â€” | Retry 8Ã—/5Ã—/3Ã— (Penyisihan/Semi/Final) | **Scribd â€” Line Follower Robot Competition Rules**; Technocorner UGM 2016 |
| â€” | Sistem poin Battle Mode 4-tier (3/2/1/0) | **Technocorner UGM 2016** â€” *Petunjuk Teknis LFC* |
| â€” | Waktu maks. per run 3 menit | **Technocorner UGM 2016**; **RobotChallenge** |
| â€” | Radius tikungan min. 150 mm | **Micromouse Online** â€” *Line Follower Test Track* |
| â€” | Lebar garis 20Â±2 mm (Digital) | **MEB Robot Turkey 2023** |
| â€” | Lebar garis 28â€“30 mm (Analog) | **MRC VIII** â€” *Rule Line Follower Digital SMP* |
| â€” | Lintasan banner cetak putih + garis hitam | Standar umum kompetisi tingkat menengah Indonesia |
| â€” | Kalibrasi hanya boleh di luar lintasan | **RoboCore Line Follower Rules** (Brazil, AWS bucket) |
| â€” | Homologasi + stiker resmi anti-substitusi | **Technocorner UGM 2016**; **ELCCO Udayana 2022** |

### Dokumen Sumber Primer

1. Petunjuk Teknis Line Follower Competition â€” *Technocorner UGM 2016* â€” https://2016.archive.technocorner.id/download/Petunjuk-Teknis-LFC.pdf
2. Line Follower Robot Category Rules â€” *MEB Robot Turkey 2023* â€” https://robot.meb.gov.tr/yukleme/Robot2023/3_Cizgi_izleyen_ileri_en.pdf
3. Line Follower Basic 2024 â€” *MEB Robot Turkey 2024* â€” https://robot.meb.gov.tr/yukleme/Robot2024/1_line_follower_basic2024_erzurum.pdf
4. Line Follower â€” *RobotChallenge International* â€” https://www.robotchallenge.org.cn/doc/en/RC-LineFollower.pdf
5. Line Following â€” *Robotex International* â€” https://robotex.international/line-following/
6. Petunjuk Pelaksanaan Line Follower ELCCO 2022 â€” *Universitas Udayana* â€” https://elcco.unud.ac.id/Line%20Follower/PETUNJUK%20PELAKSANAAN%20LINE%20FOLLOWER%20ELCCO%202022.pdf
7. Rule Line Follower Digital SMP â€” *MRC VIII* â€” https://www.scribd.com/document/764833389/Rule-Line-Follower-Digital-smp-MRC-VIII-1
8. RoboCore Line Follower Rules â€” *RoboCore (Brazil)* â€” https://robocore-eventos.s3.sa-east-1.amazonaws.com/public/RoboCore_Line_Follower_Rules.pdf
9. Line Follower Test Track â€” *Micromouse Online* â€” https://micromouseonline.com/2008/11/16/line-follower-test-track/
10. Line Follower Robot Competition Rules â€” *Scribd* â€” https://www.scribd.com/doc/284284340/Line-Follower-Robot-Limit

---

*Panduan ini dinyatakan **FINAL** untuk edisi pertama lomba.*
*Perubahan aturan hanya dapat dilakukan **sebelum Technical Meeting** dan wajib dikomunikasikan kepada seluruh peserta terdaftar.*

*Versi 4.0 â€” Disusun & diverifikasi berdasarkan 10 regulasi kompetisi Line Follower nasional & internasional.*
