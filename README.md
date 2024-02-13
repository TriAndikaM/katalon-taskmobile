# katalon-taskmobile

# Test Case: Pencarian Produk

## Deskripsi
Memastikan pengguna dapat menemukan produk yang mereka cari dengan menggunakan fitur pencarian, dan bahwa sistem merespons dengan benar terhadap permintaan pencarian.
## Prasyarat
- User sudah login ke aplikasi.
- User berada pada halaman beranda aplikasi.
- Terdapat produk yang tersedia untuk dicari di database atau katalog produk.
## Langkah-langkah Uji
1. User klik tombol pencarian pada navigation bar dilambangkan dengan icon kaca pembesar.
2. User memasukkan kata kunci atau deskripsi produk yang ingin dicari ke dalam kotak pencarian.
3. User klik icon kaca pembesar.
## Hasil yang Diharapkan
- Sistem harus menampilkan hasil pencarian yang relevan dengan kata kunci yang dimasukkan oleh pengguna.
- Jika tidak ada produk yang sesuai dengan kata kunci, sistem harus tidak menampilkan produk apapun pada halaman.
## Hasil Aktual
- Sistem menampilkan hasil pencarian yang relevan dengan kata kunci yang dimasukkan oleh pengguna.
- Jika tidak ada produk yang sesuai dengan kata kunci, sistem tidak menampilkan produk apapun pada halaman.
## Status
Sukses

# Test Case: Checkout Keranjang

## Deskripsi
Memastikan bahwa pengguna dapat menyelesaikan proses pembelian produk dengan lancar.
## Prasyarat
- User telah berhasil login atau mengakses website e-commerce.
- Keranjang belanja telah diisi dengan produk yang ingin dibeli.
## Langkah-langkah Uji
1. User klik menu Category.
2. User klik kategori produk yang diinginkan.
3. User memilih produk yang diinginkan.
4. User menekan tombol "Add To Cart".
5. User memasukkan jumlah barang yang ingin ditambahkan.
6. User Klik Add.
7. User Klik icon keranjang pada navigation bar.
8. User mengakses halaman keranjang belanja di website e-commerce.
9. User klik tombol Checkout.
10. User mengisi informasi dengan valid.
11. User klik proses checkout.
12. User klik pilihan “yes” pada pesan yang muncul.
## Hasil yang Diharapkan
User harus menerima konfirmasi atau pesan sukses yang menegaskan bahwa pembayaran mereka telah berhasil diproses setelah menyelesaikan proses pembayaran.
## Hasil Aktual
User menerima konfirmasi atau pesan sukses yang menegaskan bahwa pembayaran mereka telah berhasil diproses setelah menyelesaikan proses pembayaran.
## Status
Sukses

## Test Case: Mengubah Data User

### Deskripsi
Memastikan bahwa user dapat mempersonalisasikan data seperti nama, email, nomor telepon, dan alamat.
### Prasyarat
- User sudah memiliki akun terdaftar pada aplikasi.
- User sudah login pada aplikasi.
### Langkah-langkah Uji
1. User klik menu Profile.
2. User klik tombol Edit disamping informasi akun user.
3. User memilih kolom data yang ingin diubah.
4. User memasukkan data baru atau menyunting data sesuai kebutuhan.
5. User klik tombol Ok.
### Hasil yang Diharapkan
- Sistem harus menerima perubahan data akun user tanpa kesalahan dan menyimpannya dengan benar.
- Setelah perubahan disimpan, sistem harus menampilkan data akun yang diperbarui dengan benar di halaman profil atau pengaturan akun.
### Hasil Aktual
- Sistem berhasil menyimpan perubahan data akun user dengan benar.
- User menerima konfirmasi atau pesan sukses yang menegaskan bahwa perubahan telah disimpan.
### Status
Lolos

## Test Case: Mengakses Informasi Bantuan

### Deskripsi
Memastikan user dapat dengan sukses meminta bantuan melalui fitur bantuan (help) di aplikasi e-commerce mobile.
### Prasyarat
User telah masuk ke akunnya di aplikasi e-commerce mobile.
### Langkah-langkah Uji
1. User menavigasi ke bagian bantuan atau bantuan pengguna yang tersedia.
2. User menekan tombol Help di dalam aplikasi.
3. User memilih kategori atau jenis bantuan yang dibutuhkan (seperti, cara pemesanan, pembayaran, pengiriman, dan informasi lainnya).
4. User menekan tombol informasi bantuan (How to order, payment, shipping, profile, contact us) yang disesuaikan.
### Hasil yang Diharapkan
Sistem harus menampilkan informasi bantuan yang dibutuhkan.
### Hasil Aktual
Sistem menampilkan informasi bantuan yang dibutuhkan.
### Status
Lolos
