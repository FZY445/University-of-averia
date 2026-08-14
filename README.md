# University of Averiá — V5.0.0

Ini adalah paket siap-upload untuk GitHub Pages.

## Isi
- `index.html` — website V5.0.0
- `assets/` — 10 foto yang kamu kirim, sudah diberi nama agar mudah dipakai

## Logo
Tetap masukkan `logo.png` milik project lama kamu di folder yang sama dengan `index.html` jika ingin mempertahankan logo UÁ versi sebelumnya. V5 saat ini memakai monogram `UÁ` di navbar supaya paket tetap mandiri.

## Fitur V5
- UI lebih iOS-like: glassmorphism, blur, rounded cards, micro-interactions, floating/pulse animation.
- Generator berita fiksi: kategori positif, negatif, netral.
- Berita baru dijadwalkan acak setiap 5–30 menit.
- Sebagian berita memakai foto yang kamu kirim dan gambar dipilih berbeda-beda.
- Number generator untuk current students, approved, dan applicants.
- Angka berubah otomatis saat halaman aktif dan state disimpan di localStorage.
- Saat halaman dibuka kembali, simulasi mencoba mengejar sebagian perubahan berdasarkan waktu yang berlalu.
- Top 10 mahasiswa unggulan + Best of Three.
- Fakultas dan deskripsi UÁ.

## Catatan penting tentang "24/7"
GitHub Pages adalah hosting statis. JavaScript hanya bisa benar-benar menjalankan timer ketika halaman dibuka/diakses. Jadi V5 mensimulasikan kontinuitas dengan `localStorage` + catch-up ketika halaman dibuka kembali. Untuk generator yang benar-benar berjalan 24/7 walaupun tidak ada browser yang membuka situs, diperlukan backend/cron/serverless job.
