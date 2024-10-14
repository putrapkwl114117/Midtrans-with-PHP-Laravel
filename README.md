Website ini adalah aplikasi toko online yang dibangun menggunakan Laravel dan Livewire dengan integrasi Midtrans untuk sistem pembayaran. Website ini dirancang untuk memfasilitasi proses pembelian dan checkout secara efisien, namun untuk bagian antar muka pengguna masih sangat sederhana dikarenakan website ini bertujuan untuk pembelajaran dan latihan semata.

Menyediakan overview dari aktivitas terkini, seperti jumlah pesanan, produk terbaru, dan statistik penjualan. Komponen: Statistik: Grafis dan chart untuk menampilkan data penjualan dan aktivitas pengguna. Notifikasi: Sistem pemberitahuan untuk peringatan dan update penting.

![image](https://github.com/user-attachments/assets/de68f503-24e5-4ad4-90b2-4e596eab043b)


Menambah, mengedit, dan menghapus produk dari toko. Komponen: Formulir Produk: Input untuk nama produk, deskripsi, harga, kategori, dan gambar. Daftar Produk: Tabel untuk menampilkan semua produk yang ada di toko.

![image](https://github.com/user-attachments/assets/8b907de1-6893-44e1-9784-fd69ae689e4d)
![image](https://github.com/user-attachments/assets/567fdda1-1421-4ed9-b202-425287c42372)


Mengatur kategori produk untuk memudahkan pencarian dan pengelompokan. Komponen: Formulir Kategori: Input untuk nama kategori dan deskripsi. Daftar Kategori: Tabel untuk menampilkan kategori yang ada.

Mengelola akun pengguna dan hak akses. Komponen: Daftar Pengguna: Tabel untuk menampilkan informasi pengguna. Detail Pengguna: Formulir untuk melihat dan mengedit informasi pengguna.

Melihat dan mengelola pesanan yang masuk. Komponen: Daftar Pesanan: Tabel untuk menampilkan status pesanan, informasi pelanggan, dan total harga. Detail Pesanan: Formulir untuk melihat rincian pesanan dan status pengiriman.

![image](https://github.com/user-attachments/assets/f8eba5bc-7aba-47fe-acbf-e9113b9df361)

![image](https://github.com/user-attachments/assets/4bbe1ac5-3236-469a-9212-6c8e909b68da)

Versi yang digunakan dalam proyek ini adalah Laravel (sebutkan versi spesifik jika ada). Fungsi: Framework PHP utama yang digunakan untuk pengembangan aplikasi web.
3.2. Livewire Fungsi: Komponen interaktif dalam Laravel yang memungkinkan pembuatan UI yang dinamis tanpa menulis JavaScript secara langsung. Instalasi: composer require livewire/livewire

Sistem pembayaran online yang terintegrasi untuk memproses transaksi. Paket: midtrans/midtrans-php Konfigurasi: MIDTRANS_CLIENTKEY dan MIDTRANS_SERVERKEY untuk autentikasi. MIDTRANS_IS_PRODUCTION, MIDTRANS_IS_SANITIZED, dan MIDTRANS_IS_3DS untuk pengaturan mode dan keamanan transaksi.

Paket Lainnya Fruitcake/laravel-cors: Dihapus karena sudah usang. Swiftmailer/swiftmailer: Dihapus karena sudah usang, diganti dengan symfony/mailer. Fzaninotto/faker: Dihapus karena sudah usang. PHPUnit/php-token-stream: Dihapus karena sudah usang.

Dependencies dan Configuration Composer: 
Digunakan untuk mengelola dependensi PHP. Artisan: Tool command-line Laravel untuk berbagai tugas pengelolaan aplikasi. .env: File konfigurasi lingkungan untuk mengatur variabel seperti database dan kunci API.

MySQL dengan konfigurasi di .env. Cache dan Session: 
Disimpan dalam file untuk pengaturan lokal. Mail: Konfigurasi SMTP untuk pengiriman email menggunakan Mailtrap (untuk pengembangan).

Pengembangan dan Deployment Git: Versi kontrol untuk mengelola kode sumber. GitHub: Platform untuk hosting repository dan kolaborasi tim.

Penutup Website ini dirancang untuk memberikan pengalaman pengguna yang optimal dengan fitur-fitur yang mendukung administrasi toko, manajemen produk, dan pemrosesan pembayaran. Pastikan untuk memperbarui kunci API dan konfigurasi sesuai kebutuhan saat memindahkan aplikasi ke lingkungan produksi.



