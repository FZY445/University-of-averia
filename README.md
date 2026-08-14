# University of Averiá — V6.0.0

## OPERATION V6.0.0 — Fix the Bug

Perbaikan utama:
- Memperbaiki bug JavaScript V5 yang membuat gambar/berita gagal dirender.
- Seluruh gambar dan logo berada di folder `assets/` dan dipanggil dengan path relatif yang aman untuk GitHub Pages.
- Mengembalikan identitas visual UÁ: merah tua kerajaan, hijau tua kerajaan, emas, ivory, serif elegan + glassmorphism iOS.
- Animasi dibuat smooth dan playful tetapi tetap elegan.
- Kategori internal berita tetap disimpan di sistem dan **tidak ditampilkan sebagai tulisan Positif/Negatif/Netral di halaman**.
- Berita baru dijadwalkan acak setiap 5–30 menit.
- Angka mahasiswa/pendaftar berubah otomatis dan disimpan di `localStorage`.
- Logo UÁ dan seluruh foto sudah disertakan.

## Upload ke GitHub

Upload **isi folder ini** ke root repository (bukan folder pembungkusnya):

```text
index.html
assets/
  averia-logo.png
  campus-gothic.jpg
  campus-lake.jpg
  campus-walkway.jpg
  grand-library.jpg
  historic-courtyard.jpg
  incident-fire.jpg
  library-books.jpg
  library-study.jpg
  student-cafe.jpg
  student-life-pub.jpg
```

Pastikan `index.html` dan folder `assets` berada pada level yang sama.

Semua berita di situs adalah simulasi/fiksi UÁ dan bukan sumber berita nyata.
