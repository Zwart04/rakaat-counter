# 🕋 Rakaat Counter: Solusi Sholat Khusyuk

![Status](https://img.shields.io/badge/version-7.3-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Web-orange)

Aplikasi web pendeteksi rakaat & sujud otomatis menggunakan sensor bayangan kamera depan. **Tanpa instalasi & 100% offline.**

> 🚀 **[Coba Demo Live Disini!](https://zwart04.github.io/rakaat-counter/)**

![Demo Screenshot](https://raw.githubusercontent.com/Zwart04/rakaat-counter/main/demo.png)

> *Catatan:* Gambar di atas hanyalah contoh tampilan. Saat membuka link demo, aplikasi akan meminta akses kamera untuk mendeteksi intensitas cahaya.

---

## ✨ Fitur Utama

| Fitur | Keterangan |
|-------|------------|
| 🎯 **Zero-Touch** | UI terkunci total saat sholat, tidak ada risiko batal karena sentuhan tidak sengaja |
| 📸 **Sensor Cahaya** | Kamera depan mendeteksi bayangan tubuh saat sujud |
| 🗣️ **Panduan Suara** | "Sujud satu", "Rakaat X" — pilihan suara Perempuan / Laki-Laki |
| 💡 **Cek Pencahayaan** | Indikator real-time untuk memastikan cahaya ruangan cukup optimal |
| 🔒 **100% Privat** | Kamera hanya diproses di browser, tidak ada rekaman / upload |
| 📱 **AMOLED Mode** | Desain gelap murni yang hemat baterai dan nyaman di mata |
| 📳 **Getaran** | Vibrate setiap kali sujud / rakaat terdeteksi |

---

## 💡 Tips Penggunaan Maksimal

> ⚠️ **Sangat Disarankan:** Aktifkan **Mode Pesawat (Airplane Mode)** dan **Jangan Ganggu (Do Not Disturb)** pada HP Anda sebelum sholat agar hitungan tidak terganggu oleh panggilan telepon atau notifikasi WhatsApp.

Gunakan di tempat dengan pencahayaan **cukup terang** (bukan silau). Cek level pencahayaan lewat tombol **"Cek Pencahayaan"** di halaman awal.

---

## 🛠️ Cara Pakai (Singkat)

1. Buka [https://zwart04.github.io/rakaat-counter/](https://zwart04.github.io/rakaat-counter/)
2. Izinkan akses kamera saat muncul notifikasi browser
3. Pilih suara pemandu (Perempuan / Laki-Laki)
4. (Opsional) Tekan **Cek Pencahayaan** untuk memastikan cahaya cukup
5. Tekan **MULAI SHOLAT**
6. Letakkan HP di samping sajadah (sejajar posisi kepala saat sujud)
7. Selesai → tekan **RESET** untuk hitungan berikutnya

---

## 🧠 Cara Kerja

Sensor kamera membaca tingkat kecerahan rata-rata (0-255) beberapa kali per detik:
- **Nilai < 25** → terdeteksi sujud (kamera tertutup bayangan)
- **Nilai > 45** → kembali berdiri/duduk
- **2× sujud = 1 rakaat**

Logika ini sepenuhnya di sisi klien (browser), tanpa server.

---

## 🛠️ Teknologi
- HTML5 + CSS3 (Vanilla, no framework)
- JavaScript + Canvas API
- Web Speech API (Text-to-Speech)
- Lucide Icons
- 100% Client-Side (no backend)

---

## 📄 Lisensi
Dilisensikan di bawah **MIT License** — bebas dipakai, dimodifikasi, dan didistribusikan.

---
*🤲 Dibuat dengan niat tulus untuk membantu sesama Muslim beribadah lebih khusyuk.*
