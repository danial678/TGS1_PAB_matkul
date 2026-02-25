## Deskripsi Aplikasi
Aplikasi terdiri dari tiga bagian utama, yaitu halaman daftar produk, halaman keranjang belanja, dan fitur checkout. Sistem dirancang untuk menampilkan produk, mengelola item yang dipilih pengguna, serta menghitung total pembayaran secara otomatis.

### 1. Halaman Products
Halaman ini menampilkan daftar produk dalam bentuk grid menggunakan komponen Card.
Informasi yang ditampilkan pada setiap produk:
Gambar produk
Nama produk
Harga dalam format Rupiah
Tombol Add untuk menambahkan produk ke keranjang

Di bagian kanan atas terdapat icon keranjang yang menampilkan jumlah item dalam bentuk badge. Ketika tombol Add ditekan, produk akan langsung masuk ke keranjang dan jumlah item pada badge akan bertambah secara otomatis.

Daftar produk yang tersedia:

Laptop Gaming – Rp 15.000.000

Smartphone Pro – Rp 8.000.000

Wireless Headphones – Rp 1.500.000

Smart Watch – Rp 3.000.000

Camera DSLR – Rp 12.000.000

Tablet Pro – Rp 7.000.000

2. Halaman Shopping Cart

Halaman ini menampilkan semua produk yang telah ditambahkan ke dalam keranjang.

Fitur yang tersedia pada halaman ini:

Menampilkan gambar, nama, dan harga produk

Tombol untuk menambah jumlah item

Tombol untuk mengurangi jumlah item

Tombol hapus untuk menghapus produk dari keranjang

Perhitungan subtotal per produk (harga dikalikan jumlah)

Total keseluruhan belanja di bagian bawah

Tombol Checkout

Setiap perubahan jumlah item akan langsung memperbarui subtotal dan total pembayaran secara real-time.

3. Fitur Checkout

Ketika tombol Checkout ditekan, sistem akan menampilkan dialog konfirmasi yang berisi:

Total pembayaran

Jumlah item yang dibeli

Tombol Cancel untuk membatalkan transaksi

Tombol Confirm untuk menyelesaikan transaksi

Fitur ini bertujuan untuk memastikan pengguna melakukan konfirmasi sebelum proses pembelian diselesaikan.

Implementasi Teknis

Beberapa komponen Flutter yang digunakan dalam aplikasi ini antara lain:

GridView untuk menampilkan daftar produk

Card untuk tampilan item produk

State management untuk mengelola data keranjang

Perhitungan total harga secara dinamis

AlertDialog untuk konfirmasi checkout

Pembaruan tampilan secara real-time berdasarkan perubahan state
