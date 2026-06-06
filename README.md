# Penghitung Rakaat Sholat Pintar (Web App)

Aplikasi web **tanpa instalasi** yang memanfaatkan kamera depan HP sebagai sensor kegelapan untuk menghitung rakaat sholat secara otomatis. Didesain agar **tidak menyentuh layar**, sehingga tidak mengganggu gerakan sujud atau ruku.

---

## ✨ Fitur Utama
- **Deteksi Tanpa Sentuh** – Hanya mengandalkan bayangan tubuh saat sujud.
- **Hitung Otomatis** – 2 × sujud = 1 rakaat.
- **Panduan Suara** – "Sujud satu" dan "Rakaat dua" (pilihan gender suara perempuan/laki‑laki).
- **Pengaturan Suara** – Aktif/mati hanya di layar awal, tidak mengganggu saat sholat.
- **Wake‑Lock** – Mencegah layar mati otomatis.
- **Anti‑sentuh** – Semua elemen UI non‑interaktif saat sholat.
- **Privasi 100 % lokal** – Kamera hanya diproses di perangkat, tidak ada rekaman atau pengiriman data.

---

## 📺 Demo Langsung
Anda dapat melihat aplikasi ini secara langsung di **GitHub Pages**:

> 👉 **[Demo Live – https://zwart04.github.io/rakaat-counter/](https://zwart04.github.io/rakaat-counter/)**

![Demo Screenshot](https://raw.githubusercontent.com/Zwart04/rakaat-counter/main/demo.png)

> *Catatan:* Gambar di atas hanyalah contoh tampilan. Saat Anda membuka link di atas, aplikasi akan meminta akses kamera dan menampilkan antarmuka sebenarnya.

---

## 🛠️ Cara Menggunakan (Langkah‑per‑Langkah)
1. **Buka halaman** `index.html` pada browser (atau langsung ke demo live di atas).
2. **Izinkan akses kamera** ketika diminta.
3. **Pilih suara** (Perempuan / Laki‑laki) dan aktifkan/ non‑aktifkan suara via tombol pada layar **Setup**.
4. Tekan **"Mulai Sholat"**.
5. Letakkan HP **di samping sajadah** (atau di tempat sujud) sehingga badan menutupi kamera saat sujud.
6. Setiap sujud terdeteksi, angka **Sujud** akan bertambah, dan pada sujud ke‑2 aplikasi akan mengumumkan **Rakaat berikutnya**.
7. Setelah selesai, tekan **Reset** untuk mengulang hitungan.

---

## 🔧 Instalasi Lokal (Jika Browser Tidak Menerima `file://`)
```bash
# Jalankan server HTTP sederhana di Termux / Linux
python -m http.server 8080
```
Kemudian buka: `http://localhost:8080` di browser HP Anda.

---

## 🔐 Privasi
- Semua pemrosesan video **hanya di sisi klien** (browser).
- Tidak ada rekaman atau penyimpanan gambar/video.
- Hanya data intensitas cahaya yang dihitung secara real‑time.

---

## 🤝 Kontribusi
Jika ingin menambah fitur atau memperbaiki bug:
1. Fork repository ini.
2. Buat branch baru (`git checkout -b nama_fitur`).
3. Push ke fork Anda dan buat Pull Request.

---

## 📄 Lisensi
Dilisensikan di bawah **MIT License** – bebas pakai, modifikasi, dan distribusi.
