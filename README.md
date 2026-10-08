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

## Pseudocode

ALGORITMA ELIMINASI GAUSS

Deklarasi:
    A : matriks koefisien
    B : matriks hasil
    M : matriks augmented
    x : array solusi
    n : jumlah variabel
    i, j, k : integer
    faktor : real

Deskripsi:

Mulai

Input matriks A
Input matriks B

Gabungkan A dan B menjadi matriks augmented [A | B]

Untuk i = 0 sampai n-1:
    Jika M[i][i] = 0:
        Cari baris di bawahnya
        Jika ditemukan:
            Tukarkan baris

    Untuk k = i+1 sampai n-1:
        faktor = M[k][i] / M[i][i]

        Untuk j = i sampai n:
            M[k][j] = M[k][j] - faktor × M[i][j]

Lakukan substitusi mundur:

Untuk i = n-1 turun sampai 0:
    Hitung nilai x[i]

Tampilkan nilai x

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

