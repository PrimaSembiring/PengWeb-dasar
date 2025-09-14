# Website ITERA sederhana menggunakan HTML

## Tujuan
Membuat halaman website ITERA dengan beranda, berita terbaru, dan kontak menggunakan struktur semantik dan layout responsif.

## Struktur Semantik
- `<main>`: Konten utama
  - `<section id="beranda">`: Halaman utama dengan background dan overlay
  - `<section id="berita">`: Daftar berita dalam grid
- `<footer id="kontak">`: Informasi kontak
- Menu navigasi berupa tabel

## Tantangan & Solusi
- Logo menutupi menu → gunakan `position: absolute` dan `z-index`
- Background beranda agar proporsional → gunakan `background-size: cover` dan flex centering
- Grid berita responsif → gunakan `display: grid` dengan `auto-fit` dan `minmax`
- Teks di atas gambar sulit dibaca → gunakan overlay `rgba(0,0,0,0.5)`

## Hasil Validasi
- Struktur HTML semantik 
- Responsif di berbagai layar 
- Menu interaktif & logo tidak menutupi konten 

## Kesimpulan
Website rapi, simpel, responsif, dan konten dapat diakses dengan baik.
