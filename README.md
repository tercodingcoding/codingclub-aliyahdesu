# codingclub-aliyahdesu

Aliyahdesu Commision

## Desain Teknis

Website ini akan memiliki fitur untuk memesan commission untuk gambar. Berikut adalah desain teknisnya:

### 1. Arsitektur

- **Frontend**: Menggunakan HTML, CSS, dan JavaScript untuk membangun antarmuka pengguna.
- **Backend**: Menggunakan PHP untuk menangani permintaan dari frontend.
- **Database**: Menggunakan MYSQL untuk menyimpan data pengguna dan pesanan commission.

### 2. Fitur Utama

- **Halaman Utama**: Menampilkan informasi tentang layanan commission dan contoh karya.

  Belum fix:
- **Formulir Pemesanan**: Pengguna dapat mengisi formulir untuk memesan commission, termasuk detail seperti jenis gambar, deskripsi, dan preferensi lainnya.
- **Halaman Galeri**: Menampilkan galeri karya yang telah selesai.
- **Halaman Profil Pengguna**: Pengguna dapat melihat dan mengelola pesanan mereka.
- **Sistem Pembayaran**: Integrasi dengan gateway pembayaran untuk memproses pembayaran.

### 3. Alur Kerja

1. Pengguna mengunjungi halaman utama dan melihat informasi tentang layanan commission.
2. Pengguna mengisi formulir pemesanan dengan detail yang diperlukan.
3. Sistem menyimpan data pemesanan di database dan mengirimkan notifikasi ke admin.
4. Admin meninjau dan mengonfirmasi pesanan.
5. Pengguna melakukan pembayaran melalui sistem pembayaran yang terintegrasi.
6. Setelah pembayaran dikonfirmasi, admin mulai mengerjakan commission.
7. Setelah commission selesai, hasilnya diunggah ke halaman profil pengguna dan galeri.

### 4. Teknologi yang Digunakan

- **Frontend**: HTML, JavaScript, Tailwind.
- **Backend**: PHP
- **Database**: MySql

### 5. Keamanan

- Validasi input pada formulir pemesanan.

### 6. Pengujian

- Pengujian unit untuk komponen frontend dan backend.
- Pengujian integrasi untuk memastikan alur kerja end-to-end berfungsi dengan baik.
- Pengujian keamanan untuk mengidentifikasi dan memperbaiki kerentanan.

### 7. Deployment

- TBD
