Fitur Utama
🛒 Point of Sale (POS): Transaksi kasir realtime dengan pencatatan stok otomatis.
📊 Dashboard & Laporan Keuangan: Laba/Rugi (P&L), Pendapatan, dan Beban.
📦 Manajemen Inventori: Tracking stok bahan baku dan barang jadi.
🚚 Supply Chain: Pencatatan pembelian bahan baku dan pengeluaran operasional lain (listrik, dll).
📱 WhatsApp Order Manager: Mencatat pesanan manual dari WA dan memudahkan balasan pelanggan.
🧾 Thermal Print: Cetak struk langsung dari browser (format 58mm).
👥 Multi-Role: Login terpisah untuk Owner (Akses Penuh) dan Kasir (Terbatas).
Cara Instalasi
Langkah 1: Persiapan File
Buat folder baru di komputer Anda, beri nama UMKM-Apps.
Di dalam folder tersebut, buat file baru bernama index.html.
Copy seluruh kode HTML yang diberikan sebelumnya dan paste ke dalam index.html.
Langkah 2: Menjalankan Aplikasi
Klik Kanan pada file index.html.
Pilih Open With > Google Chrome (atau browser lainnya).
Aplikasi akan terbuka di browser.
Langkah 3: Login
Aplikasi dimulai dengan halaman Login. Gunakan PIN default:

Owner (Akses Penuh): 1234
Kasir (Kasir Saja): 0000
Panduan Penggunaan
1. Transaksi Penjualan (Kasir/POS)
Buka menu Kasir (POS).
Klik produk yang diinginkan untuk memasukkannya ke keranjang.
Jumlah akan muncul otomatis di bagian kanan (Total Belanja).
Klik tombol Bayar.
Masukkan jumlah uang tunai yang diterima.
Klik Selesai & Cetak untuk menyimpan transaksi dan mencetak struk (jika printer terhubung).
2. Mengatur Stok Bahan Baku (Supply Chain)
(Hanya akses Owner)

Buka menu Supply & Beban.
Bagian atas: Belanja Bahan Baku.
Pilih nama bahan (misal: Gula Cair), isi jumlah (Qty), dan harga per unit.
Klik Simpan Stok.
Stok di inventori akan bertambah.
Pengeluaran akan tercatat di laporan keuangan.
3. Mencatat Pengeluaran Lain (Non-Inventori)
(Hanya akses Owner)

Buka menu Supply & Beban.
Bagian bawah: Catat Pengeluaran Lain.
Isi nama pengeluaran (misal: Listrik Bulan Ini) dan biaya.
Klik Catat Beban.
Ini tidak mengubah stok barang, tapi mengurangi Laba Bersih.
4. Menangani Order WhatsApp
Fitur ini memudahkan Anda mencatat pesanan dari chat WA.

Saat customer chat ke WA Anda, buka menu Order WhatsApp.
Isi form:
Nama Customer.
Nomor HP (WA) customer.
Estimasi Total harga.
Detail pesanan (copy dari chat).
Klik Simpan ke Dashboard.
Order akan muncul di tabel bawah.
Jika sudah siap diantar/proses, klik tombol Proses di tabel tersebut.
Klik tombol Balas WA (Hijau) untuk langsung membuka WA ke customer dengan pesan konfirmasi otomatis.
5. Membaca Laporan Keuangan
(Hanya akses Owner)

Buka menu Laporan Keuangan.
Anda akan melihat:
Pendapatan (Total Penjualan).
HPP (Harga Pokok Penjualan).
Laba Kotor.
Beban (Pembelian & Pengeluaran Lain).
Laba Bersih (Uang bersih milik Anda).
Reset Data
Jika ingin menghapus semua data dan memulai dari awal (Reset Pabrik):

Saat sedang login di aplikasi.
Klik tombol menu Karyawan (di sidebar paling bawah).
Di dalam halaman Karyawan, klik tombol "Reset Semua Data (Factory Reset)".
Catatan: Data disimpan di browser (LocalStorage). Jika Anda menghapus history/cache browser, data juga akan hilang.

Dukungan Teknis
Jika struk tidak tercetak, pastikan printer thermal Anda terhubung dan pengaturan browser di set ke "Latar Belakang dan Grafik".
Aplikasi ini optimal dijalankan di layar Desktop (PC/Laptop) tetapi tetap responsif di HP.