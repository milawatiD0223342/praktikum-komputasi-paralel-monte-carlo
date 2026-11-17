# Praktikum Komputasi Paralel – Monte Carlo

## Deskripsi
Praktikum ini menerapkan teknik komputasi paralel menggunakan metode Monte Carlo untuk mengestimasi nilai Pi (π).

## Permasalahan
Perhitungan dengan jumlah sampel yang besar membutuhkan waktu komputasi. Oleh karena itu, digunakan teknik komputasi paralel untuk membagi pekerjaan menjadi dua worker agar proses perhitungan dapat dilakukan secara bersamaan.

## Tools dan Library
- Python
- Google Colab
- NumPy
- Multiprocessing
- Time

## Pengaturan Praktikum
- Total sampel: 20.000.000
- Eksekusi sekuensial: 1 proses
- Eksekusi paralel: 2 workers

## Hasil Praktikum

| Parameter | Hasil |
|---|---|
| Waktu sekuensial | 0,6058 detik |
| Waktu paralel | 0,5244 detik |
| Speedup | 1,16x |
| Efisiensi | 57,8% |

## File Program
File program tersedia pada `KPT.ipynb` dan dapat dibuka menggunakan Google Colab.

## Tujuan
Membandingkan waktu eksekusi sekuensial dan paralel serta mengetahui peningkatan kinerja menggunakan multiprocessing.
