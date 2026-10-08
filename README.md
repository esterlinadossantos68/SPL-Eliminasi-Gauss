# Program Penyelesaian SPL Metode Eliminasi Gauss

## 1. Deskripsi

Program ini digunakan untuk menyelesaikan Sistem Persamaan Linear (SPL)
menggunakan metode Eliminasi Gauss dengan bahasa pemrograman Python.

## 2. Tujuan

Menyelesaikan SPL dengan melakukan eliminasi terhadap elemen-elemen
di bawah pivot hingga membentuk matriks segitiga atas, kemudian
menentukan nilai variabel menggunakan substitusi mundur.

## 3. Algoritma Deskriptif

1. Mulai.
2. Masukkan matriks koefisien A dan matriks hasil B.
3. Bentuk matriks augmented [A | B].
4. Tentukan elemen pivot.
5. Jika pivot bernilai nol, lakukan pertukaran baris.
6. Eliminasi elemen di bawah pivot hingga bernilai nol.
7. Ulangi proses sampai terbentuk matriks segitiga atas.
8. Lakukan substitusi mundur.
9. Tampilkan nilai setiap variabel.
10. Selesai.

## 4. Pseudocode

ALGORITMA ELIMINASI GAUSS

Input A dan B
Gabungkan A dan B menjadi matriks augmented [A | B]

Untuk setiap pivot:
    Jika pivot = 0:
        Tukar baris
    Untuk setiap baris di bawah pivot:
        Hitung faktor
        Kurangi baris dengan faktor × baris pivot

Lakukan substitusi mundur

Tampilkan solusi

Selesai

## 5. Contoh SPL

2x + y - z = 8

-3x - y + 2z = -11

-2x + y + 2z = -3

## 6. Hasil

x1 = 2
x2 = 3
x3 = -1

## 7. Kesimpulan

Metode Eliminasi Gauss dapat digunakan untuk menyelesaikan
Sistem Persamaan Linear dengan mengubah matriks augmented
menjadi bentuk segitiga atas dan dilanjutkan dengan substitusi
mundur.
