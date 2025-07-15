# TUGAS-FIRDA-YASTRI-PERTEMUAN-14
**Panduan Instalasi dan Konfigurasi**

 A. Persyaratan Sistem
Untuk menjalankan aplikasi ini, pengguna harus memiliki:

- Python versi 3.7 atau lebih baru.
- Sistem operasi Windows / Linux / MacOS.
- Text editor (opsional): seperti VS Code, Notepad++, atau terminal bawaan.

B. Langkah-langkah Instalasi
Download / Salin file Python:
- Pastikan kamu memiliki file inventaris.py yang merupakan program utama.
- Simpan dalam satu folder khusus
  
Folder ini akan berisi:
- inventaris.py (kode utama)
- data_inventaris.json (otomatis dibuat saat pertama kali program dijalankan)
- Folder backups/ (otomatis dibuat saat kamu melakukan backup)

Jalankan Aplikasi
- Buka terminal atau command prompt, arahkan ke folder tempat file berada, lalu ketik:

bash
python inventaris.py
Konfigurasi Otomatis

- Program akan membuat file data jika belum ada (data_inventaris.json)
- Saat pertama kali melakukan backup, program akan otomatis membuat folder backups.
  

**Tutorial Penggunaan Aplikasi**

Saat program dijalankan, kamu akan melihat tampilan menu utama berikut:

Menu:
1. Tambah Barang
2. Hapus Barang
3. Tampilkan Semua
4. Cari Barang
5. Laporan
6. Backup Data
7. Simpan & Keluar
   
Berikut adalah penjelasan detail fungsi setiap menu:

1. Tambah Barang
   
Fungsi: Menambahkan barang baru ke dalam inventaris.

Langkah:

-Masukkan kode barang (harus unik)

-Masukkan nama barang

-Masukkan stok barang (dalam angka)

Catatan:
Jika kode barang sudah pernah ditambahkan sebelumnya, maka akan ditolak.


2. Hapus Barang
   
Fungsi: Menghapus barang berdasarkan kode.

Langkah:

-Masukkan kode barang yang ingin dihapus.

-Jika ditemukan, barang akan dihapus.


3. Tampilkan Semua
   
Fungsi: Menampilkan semua barang dalam sistem inventaris.

Hasil:
Menampilkan daftar barang lengkap dengan kode, nama, dan stok.


4. Cari Barang
   
Fungsi: Mencari barang berdasarkan kode.

Langkah:

-Masukkan kode barang.

-Jika ditemukan, informasi barang akan ditampilkan.


5. Laporan
   
Fungsi: Menampilkan laporan lengkap dari semua data.

Hasil:

-Tabel berisi semua barang.

-Jumlah total item dan total stok keseluruhan.


6. Backup Data
   
Fungsi: Menyimpan salinan data inventaris saat ini ke file backup.

Hasil:

-File JSON baru disimpan ke folder backups/.

-Nama file berisi waktu dan tanggal backup.


7. Simpan & Keluar
   
Fungsi: Menyimpan semua perubahan ke file data_inventaris.json.

Program akan berhenti setelah menyimpan data.



**FAQ dan Troubleshooting Guide**

Masalah / Pertanyaan Dan Solusi

Aplikasi tidak bisa dibuka	: Pastikan Python terinstal dengan benar. Jalankan python --version untuk cek.

File data_inventaris.json hilang	: Program akan otomatis membuat file saat pertama dijalankan.

Stok tidak bisa diinput	: Hanya menerima angka. Jangan input huruf atau simbol.

Backup tidak muncul	: Gunakan menu “6. Backup Data” untuk membuat backup.

Barang tidak bisa diedit	: Hapus barang lama, lalu tambah ulang dengan data baru.

Data hilang setelah keluar	: Pastikan memilih “7. Simpan & Keluar” sebelum menutup program.

Backup tidak tersimpan	: Periksa apakah program punya izin menulis di direktori tersebut.

Folder backup tidak ada	: Akan otomatis dibuat saat backup pertama kali dilakukan.
