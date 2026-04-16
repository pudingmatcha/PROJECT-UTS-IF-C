# LAPORAN UTS STRUKTUR DATA
## Nama Anggota :
 1. Malvaraina Nursalim (2501010084)
 2. Pande Putu Vidya Reswara (2501010064)
 3. Kadek Satya Giri Sardhula (2501010088) 
## 1. Rumusan Masalah dan Solusi
### 1)Rumusan Masalah 1 :
Bagaimana sistem dapat mengatasi keterbatasan kapasitas antrean agar tidak terjadi overflow (antrean penuh) dan underflow (antrean kosong)?

Solusi : 
Sistem menyediakan metode is_full() dan is_empty() sebagai mekanisme validasi sebelum melakukan operasi utama. Jika antrean penuh, sistem akan menolak penambahan data dan memberikan notifikasi kepada pengguna. Sebaliknya, jika antrean kosong, sistem juga mencegah proses pengambilan data. Pendekatan ini memastikan integritas data tetap terjaga dan mencegah error saat program dijalankan.
### 2)Rumusan Masalah 2 :
Bagaimana meningkatkan efisiensi penggunaan memori dalam implementasi antrean menggunakan array?

Solusi : 
Program menerapkan konsep circular queue dengan operasi modulo (% kapasitas) pada indeks depan dan belakang. Hal ini memungkinkan penggunaan kembali slot array yang telah kosong akibat proses dequeue(), sehingga tidak terjadi pemborosan memori seperti pada linear queue biasa. Dengan cara ini, sistem tetap efisien meskipun menggunakan struktur array dengan ukuran tetap.

### 3)Rumusan Masalah 3 :
Bagaimana sistem dapat memberikan informasi posisi dan kondisi antrean secara real-time kepada pengguna?

Solusi : 
Sistem menyediakan fungsi display() untuk menampilkan seluruh isi antrean dan peek() untuk melihat pembeli yang berada di posisi terdepan. Dengan adanya fitur ini, pengguna dapat mengetahui kondisi antrean secara langsung tanpa harus memproses seluruh data secara manual, sehingga meningkatkan transparansi dan kemudahan penggunaan sistem.


