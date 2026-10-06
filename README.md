# InventoryHub - Full-Stack Integration Project

InventoryHub adalah aplikasi manajemen inventaris berbasis *full-stack* yang dikembangkan sebagai proyek akhir integrasi sistem. Proyek ini mengintegrasikan komunikasi antara komponen *front-end* dan *back-end*, menangani pemrosesan data API berformat JSON secara aman, serta menerapkan pengoptimalan kinerja demi menciptakan pengalaman pengguna yang responsif.

---

## 🚀 Fitur Utama
- **Integrasi Full-Stack yang Mulus:** Menghubungkan antarmuka pengguna berbasis komponen web dengan layanan peladen (*back-end*) menggunakan protokol HTTP secara asinkron.
- **Manajemen Data JSON:** Melakukan deserialisasi dan pemetaan data JSON secara akurat ke dalam model objek aplikasi.
- **Penanganan Kesalahan & Debugging:** Menggunakan *try-catch*, pembatalan permintaan menggunakan `CancellationTokenSource`, serta strategi cadangan (*fallback strategy*) untuk menjaga keandalan aplikasi.
- **Pengoptimalan Kinerja:** Menerapkan *caching*, paginasi data untuk kumpulan data besar, serta manajemen *state* yang konsisten.

---

## 🛠️ Teknologi yang Digunakan
- **Front-End & Back-End:** .NET / C# (Blazor / Minimal API)
- **Kontrol Versi:** Git & GitHub
- **Asisten Pengembangan:** Microsoft Copilot

---

## 🤖 Pemanfaatan Microsoft Copilot dalam Pengembangan
Dalam proses pembuatan proyek ini, Microsoft Copilot digunakan sebagai asisten AI untuk mempercepat dan meningkatkan kualitas kode pada setiap tahapan berikut:
1. **Pembuatan Kode Integrasi:** Membantu menyusun struktur awal komunikasi HTTP antara *front-end* dan peladen *back-end*.
2. **Debugging & Penyelesaian Masalah:** Menganalisis log kesalahan, mendeteksi potensi *race conditions*, dan menerapkan `CancellationToken` untuk mencegah ketidakkonsistenan data akibat klik ganda tombol aksi.
3. **Struktur JSON:** Membantu memetakan skema respons JSON agar sesuai dengan properti model data objek .NET.
4. **Pengoptimalan Kinerja:** Memberikan rekomendasi praktik terbaik seperti penanganan *asynchronous programming* (`async`/`await`) dan manajemen *state* yang efisien.

---

## ⚙️ Cara Menjalankan Proyek
1. Clone repositori ini ke komputer lokal Anda:
   ```bash
   git clone [https://github.com/username/inventory-hub-fullstack.git](https://github.com/username/inventory-hub-fullstack.git)
