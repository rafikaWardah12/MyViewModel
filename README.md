# MyViewModel
Project MyViewModel merupakan applikasi sederhana untuk menghitung perkalian dari panjang, lebar dan tinggi. ViewModel diterapkan pada project ini supaya menghindari data yang kehapus saat ada rotate device. Bahasa kotlin digunakan untuk membuat MyViewModel.

## Implementasi
1. Membuat kelas ViewModel untuk menampung logika dan data sementara
2. Mengimplementasikan ViewModel ke dalam Activity

## What I Learn
1. ViewModelProvider menggunakan parameter this dikarenakan inisialisasi dilakukan di Activity
2. Input .get( ) di isi dengan kelas ViewMOdel yang dihubungkan dengan Activity
3. Metode *calculate* = melakukan perkalian dari input lebar, panjang, tinggi
4. Metode *result* = mendapatkan hasilnya namun setiap perubahannya tidak dapat otomatis terganti. Diperlukan metode displayResult( ) = memperbarui nilai *result*. Cara kedua yaitu dengan LiveData
   
