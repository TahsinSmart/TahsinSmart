# 🕌 Tahsin Academic Smart

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)

**Tahsin Academic Smart** adalah sistem portal akademik berbasis web yang dirancang khusus untuk memudahkan interaksi pembelajaran antara Asatidz (Guru) dan Santri (Murid) di lembaga pendidikan Tahsin / Tahfidz. 

Aplikasi ini menggunakan sistem *Realtime Database* dan otentikasi Google yang aman, sehingga data kelas selalu up-to-date tanpa perlu *refresh* halaman.

## ✨ Fitur Utama

Aplikasi ini membagi hak akses menjadi 2 peran utama:

### 👨‍🏫 Fitur Asatidz (Guru)
* **Manajemen Kelas:** Membuat ruang kelas baru dan menghasilkan Kode Kelas unik, atau memulihkan data kelas lama.
* **Presensi Cepat:** Form absensi santri (Hadir, Sakit, Izin, Alpa) yang terintegrasi langsung ke riwayat santri.
* **Studio Paket Ujian:** Pembuat soal dinamis yang mendukung format Pilihan Ganda dan Esai secara bersamaan.
* **Auto-Grading & Penilaian Manual:** Sistem otomatis menghitung skor pilihan ganda ke skala 100. Guru juga dapat memberikan nilai manual dan catatan (*feedback*) pada jawaban esai.
* **Export Ujian ke Word:** Soal yang telah dibuat dapat diunduh menjadi file `.doc` (Microsoft Word) untuk dicetak.
* **Pengumuman Kelas:** Papan buletin untuk membagikan informasi penting kepada seluruh anggota kelas.

### 🎓 Fitur Santri (Murid)
* **Gabung Kelas:** Bergabung ke ruang kelas menggunakan Kode Undangan dari Asatidz.
* **Lembar Ujian Interaktif:** Mengerjakan tugas dan ujian secara online dengan antarmuka yang ramah pengguna.
* **Transparansi Evaluasi:** Melihat hasil koreksi ujian secara detail (mana jawaban yang benar dan salah) beserta catatan dari guru.
* **Riwayat Akademik:** Akses rekapitulasi nilai akhir dan riwayat kehadiran pribadi.

### 🏆 Fitur Global
* **Papan Peringkat (Leaderboard):** Sistem secara otomatis menghitung rata-rata nilai santri dan menampilkan Top Ranking di beranda untuk memotivasi belajar.
* **Login Akun Google:** Akses mudah dan aman menggunakan infrastruktur otentikasi Firebase.

---

## 🛠️ Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan arsitektur *Serverless* (Frontend-only):
* **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (via CDN)
* **Ikon & Tipografi:** FontAwesome 6, Plus Jakarta Sans (Google Fonts)
* **Backend / BaaS:** Firebase (V10 SDK)
    * *Firebase Authentication* (Google Sign-in)
    * *Cloud Firestore* (Realtime Database)

---


**Tips Tambahan untuk GitHub:**
1. Ganti URL `https://github.com/username-kamu/tahsin-smart.git` pada langkah instalasi dengan URL repositori kamu yang sebenarnya.
2. Jika nanti kamu sudah mengambil *screenshot* (tangkapan layar) dari aplikasi saat berjalan, kamu bisa menambahkan bagian `## 📸 Cuplikan Layar (Screenshots)` ke dalam README tersebut agar terlihat lebih profesional!

## 🚀 Cara Menjalankan Secara Lokal (Setup)

Karena aplikasi ini berjalan sepenuhnya di sisi klien (*client-side*), kamu bisa langsung menjalankannya tanpa perlu menginstal Node.js atau paket NPM.

1. **Clone Repositori ini:**
   ```bash
   git clone [https://github.com/username-kamu/tahsin-smart.git]([https://github.com/username-kamu/tahsin-smart.git](https://github.com/TahsinSmart/TahsinSmart)
   cd tahsin-smart
