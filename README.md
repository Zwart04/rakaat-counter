# 🕋 Rakaat Counter: Solusi Cerdas Agar Sholat Lebih Khusyuk

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Platform](https://img.shields.io/badge/Platform-Web-orange)

Pernahkah Anda merasa ragu sudah rakaat ke berapa saat sedang sholat sendirian? **Rakaat Counter** adalah aplikasi web ringan yang dirancang khusus untuk membantu Anda mengingat jumlah rakaat dan sujud secara otomatis tanpa perlu menyentuh layar HP.

> 🚀 **[Coba Demo Live Disini!](https://zwart04.github.io/rakaat-counter/)**

![Cara Penggunaan](https://raw.githubusercontent.com/Zwart04/rakaat-counter/main/demo.png)

> *Catatan:* Gambar di atas hanyalah contoh tampilan. Saat Anda membuka link demo di atas, aplikasi akan meminta akses kamera dan menampilkan antarmuka sebenarnya.

---

## 💡 Mengapa Menggunakan Rakaat Counter?

Banyak aplikasi penghitung rakaat mengharuskan kita menekan layar, yang terkadang justru memecah konsentrasi atau berisiko membatalkan gerakan sholat. Aplikasi ini menggunakan pendekatan berbeda: **Sensor Cahaya via Kamera Depan.**

### ✨ Fitur Unggulan:
- **Zero-Touch Interface**: Menghitung otomatis saat Anda sujud (sensor mendeteksi bayangan tubuh).
- **Audio Feedback**: Suara pemandu "Sujud satu", "Sujud dua", dan "Rakaat X" untuk memastikan hitungan benar.
- **Pilihan Gender Suara**: Tersedia opsi suara Laki-laki atau Perempuan sesuai preferensi.
- **AMOLED Dark Mode**: Hemat baterai dan nyaman di mata saat kondisi minim cahaya.
- **Privacy First**: Tidak ada video yang direkam atau dikirim ke server. Semua pemrosesan terjadi 100% di browser Anda.

---

## 🛠 Cara Kerja & Penggunaan

1. **Akses**: Buka [Link Demo](https://zwart04.github.io/rakaat-counter/) atau file `index.html`.
2. **Izin**: Izinkan akses kamera (hanya digunakan sebagai sensor intensitas cahaya).
3. **Setup**: Pilih jenis suara dan tekan **Mulai Sholat**.
4. **Posisi**: Letakkan HP di bawah dagu/area sujud (posisi landscape atau portrait).
5. **Sholat**: Setiap kali Anda sujud dan tubuh menutupi kamera, sensor akan mendeteksi perubahan cahaya dan menambah hitungan.

---

## 🏗 Teknologi yang Digunakan
- **HTML5 & CSS3**: UI modern dengan Tailwind-style utility.
- **Vanilla JavaScript**: Logika deteksi cahaya menggunakan `Canvas API`.
- **Web Speech API**: Untuk *voice feedback* yang jernih.
- **No Backend Required**: Murni aplikasi sisi klien (Client-side).

---

## 🤝 Kontribusi
Aplikasi ini bersifat **Open Source**. Kami sangat terbuka bagi siapa saja yang ingin:
- Menambahkan fitur baru (misal: statistik sholat).
- Memperbaiki algoritma deteksi cahaya.
- Menambahkan dukungan bahasa atau suara baru.

---

## 📄 Lisensi
Proyek ini dilisensikan di bawah **MIT License**. Bebas digunakan untuk keperluan pribadi maupun dikembangkan lebih lanjut.

---
*Dibuat dengan ❤️ untuk membantu sesama Muslim beribadah lebih baik.*
