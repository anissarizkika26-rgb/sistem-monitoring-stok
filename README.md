# Proyek Sistem Monitoring Stok dan Penjualan Kantin Kampus
Identitas Mahasiswa
- Nama: Annisa Rizkika
- NIM: C2583207005
- Kelas: PTI 3B
- Mata kuliah: Algoritma dan Pemrograman Lanjutan
- Nama proyek: Sistem Monitoring Stok dan Penjualan Kantin Kampus
# DESKRIPSI PROYEK
Program ini merupakan aplikasi console berbasis bahasa C untuk membantu pengelola kantin kampus mengelola produk, harga, stok, transaksi penjualan, pencarian produk, pengurutan, dan laporan penjualan. Data disimpan di dalam array selama program berjalan, sehingga tidak menggunakan database atau file eksternal.
# Daftar Fitur
1. Menampilkan daftar nama produk, harga, stok, dan jumlah terjual.
2. Menambahkan produk baru dengan kapasitas maksimal 50 produk.
3. Mengubah harga dan stok produk.
4. Melakukan transaksi yang berisi beberapa jenis produk.
5. Memeriksa ketersediaan stok sebelum transaksi dikonfirmasi.
6. Menambahkan stok produk.
7. Mencari produk berdasarkan nama.
8. Mengurutkan produk berdasarkan harga termurah atau jumlah terjual terbanyak.
9. Menampilkan laporan total unit, total pendapatan, dan produk terlaris.
10. Menampilkan produk yang stoknya kurang dari 5.
11. Memvalidasi input yang salah atau tidak sesuai.
# Penerapan Array
# Program menggunakan:
- char namaProduk[50][100] sebagai array karakter dua dimensi untuk menyimpan maksimal 50 nama produk.
- long long harga[50] sebagai array satu dimensi untuk menyimpan harga.
- int stok[50] sebagai array satu dimensi untuk menyimpan stok.
- int jumlahTerjual[50] sebagai array satu dimensi untuk menyimpan jumlah produk yang sudah terjual.
Indeks yang sama pada setiap array menunjukkan satu produk yang sama. Variabel jumlahProduk digunakan untuk mencatat jumlah data produk yang aktif. Data awal terdiri dari lima produk.
 Cara Menjalankan Program

Pastikan komputer sudah memiliki compiler bahasa C, seperti GCC.

###  Langkah 1: Menyiapkan File

Simpan kode program dengan nama:

`main.c`

### Langkah 2: Melakukan Kompilasi

Buka terminal pada folder tempat file disimpan, kemudian jalankan:

```bash
gcc main.c -o kantin
```

### Langkah 3: Menjalankan Program

Untuk Windows:

```bash
kantin.exe
```

Untuk Linux:

```bash
./kantin
```

Setelah program dijalankan, menu utama akan muncul dan pengguna dapat memilih fitur yang ingin digunakan.

ke 1
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173106" src="https://github.com/user-attachments/assets/de555ec3-1c33-49a9-8499-e5fcf62c502f" />

ke 2
<img width="1920" height="1080" alt="Screenshot 2026-11-17 174434" src="https://github.com/user-attachments/assets/f8ee10ae-a8df-4f4b-8fc2-11517873adff" />


ke 3
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173231" src="https://github.com/user-attachments/assets/ac7a227b-f5fb-4ea4-97b9-e3567b9b04af" />

ke 4
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173451" src="https://github.com/user-attachments/assets/555c718d-809b-4fcc-bf84-8c095ba452e7" />


ke 5
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173736" src="https://github.com/user-attachments/assets/a5d4cf05-a2fd-4176-a5bf-d99a2aa2dec1" />

ke 6
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173827" src="https://github.com/user-attachments/assets/2dae7bc1-156f-421f-8ca5-9cb33028c70f" />

ke 7
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173924" src="https://github.com/user-attachments/assets/eaf94014-a24a-40ed-b9c4-c05572227ba7" />

ke 8
<img width="1920" height="1080" alt="Screenshot 2026-11-17 174009" src="https://github.com/user-attachments/assets/2ed0e17e-e98a-4f4b-89d2-f4d6a425a93b" />







