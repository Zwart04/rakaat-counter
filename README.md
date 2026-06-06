# Penghitung Rakaat Sholat Pintar (Web App)

Aplikasi web sederhana yang memanfaatkan kamera depan HP sebagai sensor bayangan (kegelapan) untuk menghitung rakaat sholat secara otomatis tanpa perlu disentuh.

## 🌟 Fitur
- **Deteksi Tanpa Sentuh:** Cukup letakkan HP di samping sejadah atau di tempat sujud. Saat badan/bayangan menutupi kamera depan, aplikasi akan menghitungnya sebagai sujud.
- **Perhitungan Otomatis:** Otomatis menghitung 2x Sujud = 1 Rakaat.
- **Suara Pemandu (TTS):** Mengeluarkan suara "Sujud satu" dan "Rakaat dua" (bisa dimatikan).
- **Pilihan Gender Suara:** Tersedia opsi suara pemandu Perempuan (default) dan Laki-laki.
- **Anti Sentuh (Pocket/Head-safe):** Layar saat sholat dinonaktifkan sentuhannya agar dahi atau sentuhan tak sengaja tidak merusak hitungan.
- **WakeLock API:** Mencegah layar HP mati otomatis saat sholat berlangsung.

## 🚀 Cara Penggunaan
Karena ini adalah file HTML murni berbasis JavaScript, Anda bisa menjalankannya langsung di browser.

### Opsi 1: Menjalankan Langsung (Local)
1. Buka file `index.html` menggunakan browser di HP Anda (Sangat disarankan menggunakan **Google Chrome**).
2. Izinkan akses **Kamera** jika diminta.
3. Atur preferensi suara di layar awal.
4. Klik **Mulai Sholat**.
5. Letakkan HP di atas sajadah, dan lakukan sholat seperti biasa.

### Opsi 2: Host di Server Lokal (Termux/Linux)
Jika browser menolak akses kamera melalui protokol `file:///`:
```bash
python -m http.server 8080
```
Lalu buka `http://localhost:8080` di browser.

## 🔒 Privasi
Aplikasi ini berjalan 100% secara lokal di perangkat Anda (Client-side). Kamera hanya digunakan untuk membaca intensitas cahaya pixel secara *real-time* dan tidak pernah direkam, disimpan, maupun dikirim ke server manapun.
