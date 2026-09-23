# 💸 Weekly Money Challenge

> **Simulasi finansial harian** — 7 hari. Rp500.000. Banyak pilihan.

Weekly Money Challenge adalah game simulasi keuangan berbasis web yang menguji kemampuan pemain dalam mengelola pemasukan mingguan, menghadapi kejadian tak terduga, dan menemukan gaya finansial mereka sendiri.

---

## 🎮 Tentang Game

Kamu mendapat pemasukan mingguan dan harus mengelolanya selama 7 hari. Setiap hari menghadirkan situasi nyata yang menguji prioritasmu: apakah kamu akan memilih yang hemat atau yang nyaman? Setiap keputusan memengaruhi saldo, tabungan, dana darurat, dan skor finalmu.

---

## ⚙️ Tingkat Kesulitan

Pilih level sebelum memulai tantangan:

| Level | Ikon | Pemasukan | Karakteristik |
|-------|------|-----------|---------------|
| **Pelan-pelan** | 🌱 | Rp500.000 | Event ringan, cocok untuk pemula |
| **Seimbang** | ⚖️ | Rp500.000 | Event lebih sering, tantangan sedang |
| **Survival Mode** | 🔥 | Rp450K–550K (acak) | Pemasukan berubah, kejutan sering & harga bisa naik tiba-tiba |

---

## 📊 Indikator Keuangan

Pantau 5 metrik selama bermain:

| Metrik | Ikon | Keterangan |
|--------|------|------------|
| **Saldo tersedia** | 💰 | Uang yang masih bisa dipakai |
| **Pengeluaran hari ini** | 📤 | Total yang dikeluarkan hari ini |
| **Total minggu ini** | 📊 | Akumulasi pengeluaran sepanjang minggu |
| **Tabungan** | 🌱 | Dana yang disisihkan untuk masa depan |
| **Dana darurat** | 🛟 | Cadangan untuk kejutan tak terduga |

---

## 🗓️ Kejadian 7 Hari

Setiap hari menyajikan satu situasi nyata dengan dua pilihan keputusan:

| Hari | Situasi | Pilihan Hemat | Pilihan Nyaman |
|------|---------|---------------|----------------|
| **Senin** | 🥪 Sarapan sebelum kelas | Masak dari stok rumah (Rp7.000) | Beli menu hemat (Rp18.000) |
| **Selasa** | 🚌 Ongkos mendadak | Jalan kaki + shuttle (Rp8.000) | Naik ojek online (Rp28.000) |
| **Rabu** | 📈 Harga makanan naik | Pilih menu alternatif (Rp16.000) | Tetap beli favorit (Rp32.000) |
| **Kamis** | 📝 Tugas presentasi | Cetak hitam putih (Rp9.000) | Cetak warna lengkap (Rp24.000) |
| **Jumat** | 🏷️ Diskon kejutan! | Simpan voucher (GRATIS) | Beli barang incaran (Rp35.000) |
| **Sabtu** | 🍿 Hangout dengan teman | Piknik di taman (Rp12.000) | Nonton + makan (Rp50.000) |
| **Minggu** | 🔧 Dana darurat terpakai | Pinjam dari teman (GRATIS) | Beli kabel berkualitas (Rp28.000) |

---

## 💰 Anggaran Mingguan

Sebelum menghadapi kejadian harian, atur alokasi anggaran untuk 7 kategori dengan **slider interaktif**:

| Kategori | Ikon | Default | Maksimal |
|----------|------|---------|----------|
| Makanan | 🍜 | Rp180.000 | Rp250.000 |
| Transportasi | 🚌 | Rp70.000 | Rp150.000 |
| Kuliah | 📚 | Rp50.000 | Rp120.000 |
| Pulsa / Internet | 📶 | Rp30.000 | Rp100.000 |
| Tabungan | 🌱 | Rp80.000 | Rp200.000 |
| Hiburan | 🎮 | Rp30.000 | Rp100.000 |
| Dana darurat | 🛟 | Rp60.000 | Rp150.000 |

---

## 🏆 Skor & Hasil Akhir

Setiap keputusan menghasilkan poin. Skor akhir ditentukan dari akumulasi poin + bonus:

**Bonus skor akhir:**
- ✅ Saldo masih tersisa → **+30 poin**
- ✅ Tabungan ≥ Rp50.000 → **+30 poin**
- ✅ Dana darurat ≥ Rp30.000 → **+25 poin**
- ❌ Pengeluaran melebihi 100% pemasukan → **−30 poin**

**Predikat akhir:**

| Predikat | Skor |
|----------|------|
| 💎 **Money Master!** | ≥ 180 poin |
| 🌟 **Kamu Makin Terarah!** | ≥ 110 poin |
| 📖 **Pelajaran Minggu Ini** | < 110 poin |

---

## 📋 Ringkasan Hasil

Di layar akhir, kamu akan melihat rekap lengkap:

- Total pemasukan
- Total pengeluaran
- Total tabungan
- Sisa uang
- Pengeluaran terbesar
- Persentase uang yang digunakan
- **Skor akhir** finansial

---

## 🗂️ Struktur File

```
weekly-money-challenge/
├── index.html   # Struktur halaman, layar mulai, pilihan kesulitan, dan game
├── style.css    # Desain dark mode, animasi, dan tampilan responsif
└── script.js    # Logika game, data kejadian, sistem anggaran, dan skoring
```

---

## 🚀 Cara Menjalankan

Tidak perlu instalasi atau server khusus. Cukup buka langsung di browser:

```
Buka file index.html di browser favoritmu
```

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** — Struktur dan markup halaman
- **CSS3** — Dark mode, grid layout, animasi, dan efek glow
- **Vanilla JavaScript** — Logika permainan, sistem anggaran, dan skoring
- **Google Fonts** — Tipografi menggunakan font *Space Grotesk* dan *DM Mono*
- **Intl.NumberFormat** — Format mata uang Rupiah secara otomatis

---

## 🎨 Desain & Fitur UI

- Tema **dark mode** dengan warna hijau mint, gold, dan coral yang elegan
- Efek **glow** dan **grid perspektif** sebagai background dekoratif
- Animasi mengambang pada ikon koin 🪙 dan dompet 👛 di layar awal
- Progress bar minggu yang bergerak setiap hari
- Slider interaktif untuk mengatur anggaran tiap kategori
- Feedback warna berbeda untuk keputusan bijak ✅ dan keputusan boros ⚠️
- Modal hasil akhir dengan animasi fade-in
- Desain responsif untuk layar mobile hingga desktop

---

> *"Kebutuhan dulu, keinginan kemudian. 💡"*
