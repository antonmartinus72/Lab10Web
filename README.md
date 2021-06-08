

# PRAKTIKUM PEMROGRAMAN WEB

## Praktikum Pertemuan 10

Praktikum dilakukan dengan modul praktikum yang sudah disediakan.

- File praktikum terdapat pada folder **lab10_php_oop**.


## 1. Mobil.php

Class digunakan untuk mendeklarasikan sebuah variabel yang berupa objek. Di dalam class ini akan di isi oleh properti, method dan lain-lain seperti contoh di bawah ini.

![enter image description here](https://github.com/antonmartinus72/Lab10Web/raw/main/Screenshoot/1_code_a.jpg)

Kode di atas mempunyai class "`Mobil`" dengan properti `$warna`, `$merk` dan `$harga`. Lalu memiliki method dengan magic method `__construct()`, dimana method ini berperan sebagai method **parent** dalam konsep **inheritance** pada Object Oriented Programming.

Selanjutnya di ada method `gantiWarna` dan `tampilWarna` yang berperan sebagai child method yang mempunyai nilai spesifik.

![enter image description here](https://github.com/antonmartinus72/Lab10Web/raw/main/Screenshoot/1_code_b.jpg)

Untuk dapat menjadi sebuah objek, objek harus dibuat terlebih dahulu. Selanjutnya adalah instansiasi method untuk mendapatkan hasil seperti di bawah ini.

![enter image description here](https://github.com/antonmartinus72/Lab10Web/raw/main/Screenshoot/1.jpg)

Pada output di atas, mobil pertama yang mengacu pada objek dengan variabel `$a` memiliki mobil dengan warna biru sebagai warna default yang dimiliki method **parent**. 
Lalu warna mobil diganti warna merah menggunakan fitur **contructor** untuk mendefinisikan warna baru saat instansiasi objek.

Untuk mobil kedua (`$b`) sama seperti warna merah, warna langsung diganti dengan warna hijau dengan menggunakan method child `gantiWarna` lalu ditampilkan dengan method child `tampilWarna`.

## 2. Form Input

Membuat form input sederhana menggunakan metode oop pada bahasa php.

Pada gambar dibawah ini terdapat method `__construct` yang berisi aksi pada form, `displayForm()` yang membentuk form html dan `addField()` yang berfungsi untuk menambah baris input.

![enter image description here](https://github.com/antonmartinus72/Lab10Web/raw/main/Screenshoot/2_form.jpg)

Kode diatas tidak dapat ditampilkan pada browser, maka dari itu terdapat file berbeda dengan kode seprti dibawah ini yang memanggil file dengan kode di atas lalu membuat objek dan instansiasi objek sehingga membentuk sebuah tabel input.

![enter image description here](https://github.com/antonmartinus72/Lab10Web/raw/main/Screenshoot/2_form-input.jpg)

Hasilnya akan terlihat seperti di bawah ini :

![enter image description here](https://github.com/antonmartinus72/Lab10Web/raw/main/Screenshoot/2.jpg)

## Sekian & Terimakasih.