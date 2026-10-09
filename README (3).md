# Destinasi Wisata Teres

Website statis sederhana tentang destinasi wisata di Indonesia, dibuat dengan HTML dan CSS murni (tanpa framework dan tanpa JavaScript). Proyek ini berawal dari tugas kuliah Sistem Informasi, lalu saya rapikan strukturnya agar lebih bersih dan mudah dibaca.

## Halaman

| Halaman | Isi |
| --- | --- |
| `index.html` | Beranda: tabel daftar destinasi (lokasi, rating, harga tiket) dan kartu destinasi bergambar dengan tautan "Baca Lebih Lanjut" |
| `datapengunjung.html` | Tabel data pengunjung beserta tempat yang dituju dan tiket yang dibayar |
| `input.html` | Form input data pengunjung (teks, angka, tanggal, dropdown, radio button) |

## Destinasi yang ditampilkan

Raja Ampat, Danau Toba, Dieng, Pantai Kuta, Candi Borobudur, dan Kebun Raya Bogor.

## Yang dipelajari di proyek ini

- Struktur dokumen HTML: `<head>`, `<body>`, tabel (`<thead>` dan `<tbody>`), dan form dengan `<label>` yang terhubung ke kolom input
- Layout kartu responsif dengan CSS Flexbox
- Styling tabel, tombol, dan form, termasuk efek `:hover`
- Gambar latar dengan `background-size: cover`

## Struktur folder

```
.
├── index.html
├── datapengunjung.html
├── input.html
├── style.css
└── img/
    ├── bogor.jpeg
    ├── candi.jpeg
    ├── danau.jpg
    ├── laut.jpg
    ├── pantai.jpg
    ├── pantaikuta.jpg
    └── pegunungan.jpg
```

## Cara menjalankan

1. Unduh atau clone repositori ini.
2. Buka `index.html` di browser. Tidak perlu instalasi apa pun.

## Catatan

- Form pada `input.html` hanya demo tampilan. Belum ada backend, jadi tombol **Simpan** tidak menyimpan data.
- Data pengunjung dan harga tiket pada halaman ini adalah contoh, bukan data sebenarnya.

## Pembuat

Ester Belen Wijaya, mahasiswa S1 Sistem Informasi, Universitas Bandar Lampung.
