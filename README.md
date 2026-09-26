# Ruang Nyuci Virtual Photobooth

Website photobooth yang bisa dibuka pelanggan dari HP.

## Fitur
- Kamera depan/belakang
- Countdown 2/3/5 detik
- 1/3/4 foto
- 3 template
- Photostrip otomatis
- Download JPG
- Share dari HP jika browser mendukung
- QR Code otomatis mengikuti URL website
- Foto diproses di perangkat, tidak diupload ke server

## Cara online gratis dengan GitHub Pages
1. Buat akun GitHub.
2. Buat repository baru, misalnya `ruang-nyuci-photobooth`.
3. Upload `index.html`.
4. Buka Settings → Pages.
5. Pilih `Deploy from a branch`, branch `main`, folder `/root`, lalu Save.
6. Tunggu proses publish. GitHub Pages akan memberi alamat `https://USERNAME.github.io/ruang-nyuci-photobooth/`.
7. Buka alamat itu dari HP. QR di halaman otomatis mengarah ke URL tersebut.

Kamera browser membutuhkan konteks aman/HTTPS. GitHub Pages menyediakan hosting website statis dan HTTPS.

## Ganti branding
Cari teks `RUANG NYUCI`, warna `--accent`, dan teks tagline di `index.html`.

## Catatan
Versi ini sengaja dibuat tanpa database/server sehingga foto pelanggan tidak disimpan online.
