# DasarAlgioritmaDanPemograman-Bisdig
 Eclesia Ollevia Putri Maura Natarang (24110310018)
 
NOMOR 1. Manfaat penggunaan fungsi:
Dengan menggunakan fungsi, kita bisa memisahkan bagian program yang melakukan tugas tertentu, misalnya menghitung faktorial. Fungsi bikin kode jadi lebih rapi, mudah dibaca, dan bisa digunakan berulang kali tanpa menulis ulang logikanya.

Cara kerja rekursi untuk menghitung faktorial:
Rekursi adalah teknik di mana fungsi memanggil dirinya sendiri. Untuk menghitung faktorial, kita bisa gunakan rekursi karena pola perhitungannya cocok, yaitu:
* Faktorial dari 1 adalah 1 (basis)
* Faktorial dari n adalah n x faktorial (n-1)
  
## Program Faktorial dengan Fungsi Rekursi
### Deskripsi
Program ini dibuat untuk menghitung nilai faktorial dari suatu bilangan yang dimasukkan oleh pengguna. Perhitungan dilakukan dengan menggunakan *fungsi rekursi*, yaitu fungsi yang memanggil dirinya sendiri hingga mencapai kondisi tertentu (disebut base case).
### Manfaat Penggunaan Fungsi dan Rekursi
Penggunaan fungsi membuat program lebih rapi, terstruktur, dan mudah digunakan kembali.  
Sementara itu, *rekursi* sangat berguna untuk menyelesaikan masalah yang memiliki pola pengulangan ke dalam (seperti faktorial, Fibonacci, dsb), karena kita bisa menyelesaikan masalah besar dengan cara memecahnya jadi masalah yang lebih kecil.
### Cara Kerja Rekursi untuk Faktorial
Misalnya kita ingin menghitung 5! (dibaca: 5 faktorial), maka:
- 5! = 5 × 4!
- 4! = 4 × 3!
- ...
- Sampai akhirnya 1! = 1 (base case)

  NOMOR 2. Penjelasan perulangan dan array (list):
Dalam kasus ini, kita butuh menyimpan 5 nilai siswa. Jadi kita gunakan array (list) untuk menampung nilainya.
Lalu kita pakai perulangan (loop) untuk input nilai siswa satu per satu, dan juga untuk mencari nilai tertinggi dan siswa keberapa yang mendapatkannya.

## Studi Kasus Nilai Siswa
Program ini digunakan untuk:
- Menerima input nilai dari 5 siswa
- Menyimpan nilai-nilai tersebut dalam list
- Mencari nilai tertinggi
- Menampilkan siswa ke berapa yang mendapatkannya
### Penjelasan:
- *Perulangan (loop)* dipakai untuk menginput data 5 kali tanpa harus ngetik 5 baris kode.
- *Array (list)* dipakai buat nyimpan semua nilai dalam satu tempat, biar gampang diolah.
### Contoh Jalankan Program:

NOMOR 3. Penjelasan Soal Nomor 3: Sistem Kasir Sederhana

Langkah-langkah algoritmanya:
	1.	Kasir masukkan harga barang pertama
	2.	Kasir masukkan harga barang kedua
	3.	Kasir masukkan harga barang ketiga
	4.	Komputer menjumlahkan semua harga
	5.	Komputer menampilkan total yang harus dibayar

Penjelasan singkat:
Algoritma ini sangat simpel karena hanya butuh menerima input harga dari tiga barang, lalu dijumlahkan, dan hasilnya ditampilkan ke layar. Ini bisa dikerjakan pakai variabel biasa dan fungsi input() serta print() di Python.

# Studi Kasus Kasir Toko

## Deskripsi
Program ini dibuat untuk membantu seorang kasir toko menghitung total harga dari 3 barang yang dibeli pelanggan. Program menerima input berupa harga masing-masing barang, lalu menjumlahkannya dan menampilkan total yang harus dibayar.

## Langkah-langkah Algoritma
1. Minta pengguna memasukkan harga barang pertama, kedua, dan ketiga.
2. Simpan harga-harga tersebut dalam variabel.
3. Jumlahkan ketiga harga tersebut.
4. Tampilkan hasil total harga ke layar.
## Bahasa Pemrograman
Program ditulis menggunakan bahasa *Python* karena sintaksnya sederhana dan mudah dipahami oleh pemula.
## Contoh Penggunaan

NOMOR 4. Penjelasan Soal Nomor 4: Cek Kelulusan Berdasarkan Rata-rata Nilai

Peran Tipe Data dan Operator:
	•	Tipe data: Kita pakai tipe float supaya bisa menghitung rata-rata dengan angka desimal (misalnya 82.5, 74.3, dll).
	•	Operator:
	•	Operator + untuk menjumlahkan nilai-nilai.
	•	Operator / untuk membagi jumlah nilai jadi rata-rata.
	•	Operator >= untuk membandingkan apakah rata-rata lebih dari atau sama dengan 75 (syarat lulus).

Logika Program:
	1.	Minta pengguna masukkan nilai dari 3 pelajaran.
	2.	Hitung rata-ratanya.
	3.	Cek apakah rata-rata ≥ 75.
	4.	Tampilkan apakah siswa LULUS atau TIDAK LULUS.

 # Studi Kasus Kelulusan Siswa

## Deskripsi
Program ini digunakan untuk menentukan apakah seorang siswa lulus atau tidak berdasarkan rata-rata nilai dari tiga mata pelajaran. Siswa dinyatakan *lulus* jika rata-rata nilai *≥ 75*.

## Penjelasan Tipe Data dan Operator
- *Tipe data* yang digunakan adalah float karena nilai ujian bisa berupa angka desimal (misalnya 76.5).
- *Operator aritmatika* digunakan untuk menjumlahkan dan membagi nilai, yaitu + dan /.
- *Operator pembanding* (>=) digunakan untuk menentukan apakah siswa lulus berdasarkan rata-rata.

## Langkah-langkah Algoritma
1. Minta pengguna memasukkan tiga nilai ujian.
2. Hitung rata-rata dari tiga nilai tersebut.
3. Bandingkan rata-rata dengan angka kelulusan (75).
4. Tampilkan hasil status "Lulus" atau "Tidak Lulus".

## Bahasa Pemrograman
Python

NOMOR 5. Penjelasan Soal Nomor 1: Diskon di Sistem E-Commerce

Penjelasan Struktur Percabangan:

Struktur percabangan (seperti if dalam Python) digunakan untuk mengecek suatu kondisi. Dalam soal ini, kondisinya adalah:
	•	Jika total belanja lebih dari Rp500.000, maka pelanggan dapat diskon 10%.
	•	Kalau belanjanya tidak sampai Rp500.000, maka tidak dapat diskon.

Dengan struktur percabangan, program bisa memutuskan apakah harus menghitung diskon atau tidak, berdasarkan kondisi tersebut.

Langkah Algoritma:
	1.	Minta pengguna masukkan total belanja.
	2.	Cek apakah belanja lebih dari 500.000.
	3.	Jika iya, hitung diskon 10% dan kurangi dari total belanja.
	4.	Jika tidak, tampilkan total seperti biasa.
	5.	Tampilkan total yang harus dibayar

 # Studi Kasus Diskon E-Commerce

## Deskripsi
Program ini dirancang untuk menghitung total pembayaran pelanggan dalam sistem e-commerce. Jika total belanja pelanggan lebih dari Rp500.000, maka akan diberikan diskon sebesar 10%. Jika tidak, pelanggan membayar penuh tanpa diskon.

## Penjelasan Struktur Kontrol Percabangan
- Struktur *percabangan if* digunakan untuk mengevaluasi kondisi apakah total belanja lebih dari Rp500.000.
- Jika kondisi benar, maka program akan menghitung diskon 10% dan menguranginya dari total belanja.
- Jika tidak memenuhi syarat, maka total bayar tetap sama dengan total belanja.

## Langkah-langkah Algoritma
1. Input total belanja dari pengguna.
2. Cek apakah total belanja lebih dari Rp500.000.
3. Jika ya, hitung diskon 10% dan kurangi dari total belanja.
4. Jika tidak, total bayar sama dengan total belanja.
5. Tampilkan total bayar yang harus dibayar pelanggan.

## Bahasa Pemrograman
Python
