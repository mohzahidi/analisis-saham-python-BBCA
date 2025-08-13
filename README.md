# analisis-saham-python-BBCA
the-gauntlet-project

# Proyek Analisis Harga Saham dengan Python

Proyek ini adalah sebuah skrip Python sederhana yang bertujuan untuk mengunduh data harga saham historis, menghitung indikator teknikal _Simple Moving Average_ (SMA), dan memvisualisasikan hasilnya dalam sebuah grafik yang informatif.

Tujuan utama dari proyek ini adalah untuk mendemonstrasikan kemampuan dasar dalam pengambilan, pengolahan, dan visualisasi data menggunakan library Python populer.

## Hasil Akhir Visualisasi

Berikut adalah contoh output grafik yang dihasilkan oleh skrip untuk saham BBCA.JK. Grafik ini menampilkan harga penutupan harian beserta tren jangka pendek (SMA 20) dan jangka panjang (SMA 50).

<img width="1259" height="710" alt="image" src="https://github.com/user-attachments/assets/962fb844-f305-4f75-a16c-e56d803b0514" />


## Teknologi yang Digunakan

* **Python 3**: Bahasa pemrograman utama yang digunakan.
* **Pandas**: Untuk manipulasi dan analisis data, terutama untuk menghitung SMA.
* **yfinance**: Untuk mengunduh data harga saham historis dari Yahoo Finance.
* **Matplotlib**: Untuk membuat dan menampilkan visualisasi data (grafik).

## Cara Menjalankan

1.  **Pastikan Python dan pip sudah terinstal.**
2.  **Instal library yang dibutuhkan:**
    ```bash
    pip install yfinance pandas matplotlib
    ```
3.  **Jalankan skrip Python:**
    ```bash
    python nama_file_anda.py
    ```
4.  Sebuah jendela akan muncul menampilkan grafik analisis harga saham.
