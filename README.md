# Supermarket Sales

## Dataset
Dataset yang digunakan adalah [Supermarket Sales](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)

## Problem Statement
Pertumbuhan supermarket di kota-kota yang padat penduduknya semakin meningkat dan persaingan pasar juga tinggi. Dalam konteks ini, dataset yang diberikan berisi catatan penjualan historis dari perusahaan supermarket yang tercatat di 3 cabang yang berbeda selama 3 bulan. Data ini dapat digunakan untuk menganalisis tren penjualan, perilaku pelanggan, dan tujuan bisnis yang berhubungan dengan perusahaan supermarket tersebut.

## Objective
1. Memahami profil pelanggan berdasarkan jenis pelanggan, jenis kelamin, dan kategori produk yang dibeli.
2. Menganalisis tren penjualan di masing-masing cabang supermarket.
3. Menentukan faktor-faktor yang berpengaruh terhadap rating pengalaman berbelanja pelanggan.

## Goals
1. Menganalisis kategori produk yang paling diminati oleh pelanggan.
2 Mengidentifikasi cabang supermarket dengan penjualan tertinggi dan terendah.
3. Menentukan jenis pelanggan yang memberikan rating pengalaman berbelanja tertinggi.

## Business Metrics

1. Segmentasi Pelanggan

  Mengukur jumlah pelanggan berdasarkan jenis pelanggan dan jenis kelamin dari setiap produk. Hal ini akan membantu dalam memahami profil pelanggan secara lebih terperinci dan mengidentifikasi segmentasi pelanggan yang berbeda.

2. Total penjualan per cabang supermarket.

  Mengukur total nilai penjualan yang dihasilkan oleh masing-masing cabang supermarket beserta total customer.

3. Rating rata-rata pengalaman berbelanja.

  Mengukur rata-rata rating yang diberikan oleh pelanggan terhadap pengalaman berbelanja di supermarket termasuk persentase kontribusi penjualan yang berasal dari setiap kategori produk.
  
## Data Exploration
1. Memahami struktur data: 

  Mengidentifikasi jenis data (numerik, kategorikal, teks, dll.), ukuran dataset, dan atribut yang tersedia.

2. Pemeriksaan missing value: 

  Mengidentifikasi adanya missing value dalam dataset dan memahami sejauh mana keberadaan missing value dapat mempengaruhi analisis.

3. Handling data duplikat: 

  Mengidentifikasi dan menghapus data duplikat dalam dataset.

4. Analisis statistik deskriptif: 

  Mengeksplorasi statistik deskriptif seperti mean, median, modus, deviasi standar, dan rangkuman lainnya untuk memahami distribusi dan tren dalam data.

5. Analisis kategori: 

  Mengeksplorasi distribusi dan frekuensi kategori dalam variabel kategorikal, serta melakukan analisis kategori lintas untuk memahami pola hubungan antara variabel kategorikal.

6. Visualisasi data: 

  Membuat visualisasi grafik seperti histogram, scatter plot, box plot, atau diagram lainnya untuk memvisualisasikan distribusi, korelasi, outliers, atau pola lain dalam data.

7. Identifikasi outlier: 

  Mendeteksi dan mengevaluasi outlier atau nilai ekstrim dalam data yang dapat mempengaruhi hasil analisis.

8. Korelasi dan hubungan:

  Menganalisis hubungan antara variabel dengan menggunakan metode seperti korelasi Pearson atau visualisasi matriks korelasi untuk memahami pola hubungan dalam data.

9. Analisis tren dan pola: 

  Menganalisis tren, pola, atau perubahan dalam data seiring waktu atau pada interval tertentu.

10. Melakukan asumsi dan hipotesis: 

  Mengidentifikasi asumsi dan hipotesis awal yang mungkin diuji selama analisis lebih lanjut.

## Inference From Analysis
1. Dataset yang digunakan memiliki jumlah baris 1000 dan 17 kolom
2. Tidak terdapat nilai yang hilang (missing values) dalam dataset
3. Tidak ada duplikat dalam dataset
4. Variabel "gross margin percentage" memiliki distribusi yang hampir konstan dengan nilai rata-rata sekitar 4.76%. Hal ini menunjukkan bahwa marjin kotor supermarket cenderung tetap pada persentase yang relatif stabil.
5. Terdapat beberapa outlier pada kolom "Tax 5%", "Total", "cogs", dan "gross income".
6. Tidak ada korelasi yang signifikan antara variabel "Rating" dengan variabel numerik lainnya. Ini menunjukkan bahwa penilaian pelanggan terhadap pengalaman belanja mereka tidak secara langsung terkait dengan variabel-variabel numerik lainnya dalam dataset.
7. Jumlah pelanggan terbagi hampir secara merata antara pelanggan dengan kartu anggota dan pelanggan biasa.
    - Member: 501
    - Normal: 499
8. Terdapat perbedaan jumlah pelanggan berdasarkan jenis kelamin dalam setiap kategori produk. Pada umumnya, jumlah pelanggan wanita lebih banyak daripada pelanggan pria.
9. Kategori produk "Electronic accessories" dan "Sports and travel" menarik lebih banyak perhatian pelanggan pria, sedangkan kategori produk "Health and beauty" dan "Home and lifestyle" cenderung menarik lebih banyak perhatian pelanggan wanita.
10. Jumlah pelanggan terbagi hampir secara merata antara pelanggan dengan jenis kelamin pria dan wanita
    - Female: 501
    - Male: 499
11. Branch dengan total penjualan tertinggi adalah Branch C, diikuti oleh Branch A dan Branch B.
12. Branch dengan jumlah pelanggan tertinggi adalah Branch A, diikuti oleh Branch B dan Branch C.
13. Dari skala rating yang digunakan yaitu 0 hingga 10, kategori produk "Food and beverages" memiliki rating tertinggi
14. Dari skala rating yang digunakan yaitu 0 hingga 10, Jenis pelanggan "Normal" memiliki rating tertinggi
15. Dari skala rating yang digunakan yaitu 0 hingga 10,Jenis kelamin "Male" memiliki rating tertinggi
