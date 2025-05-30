# Sistem Penyewaan PlayStation 🎮

## Ringkasan 📋
Sistem Penyewaan PlayStation adalah solusi perangkat lunak yang dirancang untuk mengelola bisnis penyewaan unit PlayStation. Sistem ini mencakup pengelolaan transaksi penyewaan, pembelian makanan dan minuman, serta laporan keuangan untuk pemilik. Dengan sistem ini, kasir dapat dengan mudah mengelola ketersediaan unit, memulai dan mengakhiri sesi sewa, memproses pembelian, dan pemilik dapat memantau performa keuangan serta catatan pengeluaran. 🚀

## Fitur Utama 🌟
- **Manajemen Unit**: Melihat unit PlayStation yang tersedia dan sedang digunakan, memilih unit untuk disewa, dan memperbarui statusnya. 🕹️
- **Transaksi Penyewaan**: Memulai dan mengakhiri sesi sewa, menghitung biaya sesi (Rp150 per menit), dan menyimpan detail transaksi. ⏳
- **Transaksi Makanan dan Minuman**: Menampilkan daftar menu, menambahkan item ke keranjang, menghitung total biaya, dan menyimpan transaksi pembelian. 🍔🥤
- **Laporan Keuangan**: Menghitung total pendapatan, pengeluaran, dan laba, membuat laporan keuangan berdasarkan periode tertentu, dan mengelola catatan pengeluaran. 📊
- **Pelacakan Pengeluaran**: Mencatat pengeluaran baru, memvalidasi data, dan melihat riwayat pengeluaran yang diurutkan. 💰

## Persyaratan 🛠️
- **Sistem Operasi**: Sistem apa pun yang mendukung browser web (misalnya, Windows, macOS, Linux).
- **Browser Web**: Browser modern seperti Chrome, Firefox, atau Edge.
- **Dependensi**: Tidak ada dependensi eksternal jika menggunakan versi siap pakai; jika tidak, pastikan lingkungan pengembangan kompatibel (misalnya, Node.js untuk deployment web).

## Cara Instalasi 📥
1. **Clone Repository**:
   ```bash
   git clone https://github.com/username-anda/sistem-penyewaan-playstation.git
   cd sistem-penyewaan-playstation
   ```
2. **Instal Dependensi** (jika diperlukan):
   - Jika menggunakan versi berbasis web, pastikan server lokal (misalnya, Node.js dengan `http-server`) sudah terinstal:
     ```bash
     npm install -g http-server
     ```
3. **Jalankan Aplikasi**:
   - Mulai server:
     ```bash
     http-server
     ```
   - Buka browser dan kunjungi `http://localhost:8080`. 🌐
4. **Versi Siap Pakai**: Unduh rilis terbaru dari [halaman Releases](https://github.com/username-anda/sistem-penyewaan-playstation/releases) dan buka file `index.html` di browser.

## Cara Penggunaan 🎯
- **Antarmuka Kasir**:
  - Gunakan bagian "Lihat Unit Tersedia" atau "Lihat Unit Aktif" untuk memilih unit PlayStation.
  - Mulai sesi sewa dengan memilih unit dan mengonfirmasi waktu mulai. ⏲️
  - Akhiri sesi, hitung biaya, dan simpan transaksi.
  - Tambahkan item makanan/minuman ke keranjang, konfirmasi pembelian, dan simpan transaksi. 🍟
- **Antarmuka Pemilik**:
  - Akses laporan keuangan untuk melihat pendapatan, pengeluaran, dan laba pada periode tertentu. 📈
  - Catat pengeluaran baru dan lihat riwayat pengeluaran yang telah diurutkan. 📜

## Kontribusi 🤝
Kami sangat menyambut kontribusi! Ikuti langkah berikut:
1. Fork repository ini.
2. Buat branch baru (`git checkout -b fitur/fitur-anda`).
3. Commit perubahan Anda (`git commit -m "Tambah fitur baru"`).
4. Push ke branch (`git push origin fitur/fitur-anda`).
5. Buka Pull Request. 🙌

## Lisensi 📜
Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detailnya.

## Kontak 📧
Untuk pertanyaan atau dukungan, silakan buka issue di [repository GitHub](https://github.com/username-anda/sistem-penyewaan-playstation/issues) atau hubungi pengelola di `email.anda@contoh.com`.

## Penghargaan 🌟
- Terima kasih kepada tim xAI yang telah menyediakan bantuan AI Grok dalam pengembangan sistem ini.
- Terinspirasi dari kebutuhan akan manajemen penyewaan yang efisien untuk bisnis kecil.
