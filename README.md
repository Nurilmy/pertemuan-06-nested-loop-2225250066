# Pertemuan 06 Nested Loop Python

Nama: Nuril Ilmy
NIM: 2225250066
Kelas: ...

## Tujuan

Menggunakan nested loop, pola, akumulasi, dan pencacahan.

## Cara Menjalankan

python3 tugas/tabel_perkalian_dan_statistik.py

## Algoritma Tugas 3

1. Baca dan validasi n.
2. Set total_semua = 0 dan count_genap = 0.
3. Ulangi i dari 1 sampai n.
4. Set total_baris = 0 untuk baris i.
5. Ulangi j dari 1 sampai n.
6. Hitung hasil = i * j.
7. Tambahkan hasil ke total_baris dan total_semua.
8. Jika hasil genap, tambah count_genap.
9. Setelah loop dalam selesai, tampilkan total_baris.
10. Setelah kedua loop selesai, tampilkan total_semua dan count_genap.

## Hasil Pengujian

| n | Jumlah pasangan | Total semua | Banyak hasil genap |
|---|---:|---:|---:|
| 1 | 1 | 1 | 0 |
| 2 | 4 | 9 | 3 |
| 3 | 9 | 36 | 5 |

## Analisis Efisiensi

Untuk input n, badan loop dalam berjalan sebanyak n × n atau n² kali.

## Refleksi

Kesalahan yang perlu diperhatikan pada nested loop adalah lokasi inisialisasi akumulator dan counter serta indentasi. total_baris direset pada setiap baris, sedangkan total_semua dan count_genap diinisialisasi sebelum nested loop.