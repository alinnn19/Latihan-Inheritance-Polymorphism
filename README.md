# 🔎 Latihan Inheritance & Polymorphis 🔎
## Deskripsi
Repositori ini berisi program Java sederhana untuk mendemonstrasikan konsep Pewarisan (Inheritance) dan Perubahan Bentuk (Polymorphism) menggunakan studi kasus objek geometri (Bentuk).

## Struktur Class 
Program ini memiliki 5 class yang terbagi menjadi beberapa file:
- Bentuk (Superclass Utama)
- BujurSangkar (Subclass dari Bentuk)
- Lingkaran (Subclass dari Bentuk)
- Silinder (Subclass dari Lingkaran / Cucu dari Bentuk)
- BentukMain (Main Class untuk menjalankan program)

##  Konsep OOP yang Digunakan
Inheritance: Menggunakan kata kunci `extends` untuk mewarisi sifat properti `warna` dari class `Bentuk` ke subclass lainnya.
Polymorphism (Method Overriding):Menggunakan anotasi `@Override` pada method `printInfo()` di setiap subclass untuk menampilkan informasi yang spesifik sesuai karakteristik bentuknya masing-masing.

## Library 
Program ini tidak menggunakan library tambahan

## Hasil 
