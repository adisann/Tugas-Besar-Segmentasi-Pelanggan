===========================================
TUGAS BESAR SEGMENTASI PELANGGAN – OLIST
===========================================

Deskripsi:
-----------
Proyek ini bertujuan untuk melakukan segmentasi pelanggan menggunakan pendekatan RFM (Recency, Frequency, Monetary) yang kemudian dikelompokkan menggunakan algoritma clustering (K-Means). Dataset yang digunakan adalah "Brazilian E-Commerce Public Dataset by Olist" yang diunduh dari Kaggle.

Langkah Penggunaan Dataset:
----------------------------
1. Pastikan Anda sudah menginstall pustaka `kagglehub`:
   pip install kagglehub

2. Gunakan kode berikut untuk mengunduh dataset:
   import kagglehub
   path = kagglehub.dataset_download("olistbr/brazilian-ecommerce")
   print("Path to dataset files:", path)

Tools dan Library:
------------------
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- jupyter notebook / google colab

Langkah-langkah Analisis:
--------------------------
1. Menggabungkan file-file data dari dataset Olist.
2. Menghitung skor RFM:
   - Recency = waktu sejak transaksi terakhir
   - Frequency = jumlah transaksi
   - Monetary = total pengeluaran
3. Normalisasi/standarisasi nilai RFM.
4. Menerapkan algoritma K-Means untuk clustering pelanggan.
5. Menentukan jumlah cluster optimal (dengan elbow method atau silhouette score).
6. Interpretasi hasil segmentasi.

Struktur Direktori:
-------------------
data/         -> folder dataset hasil download dari kagglehub
notebooks/    -> file .ipynb (jupyter notebook) untuk analisis
results/      -> hasil visualisasi dan evaluasi cluster
README.txt    -> catatan ini

Catatan Tambahan:
------------------
- Pastikan Anda sudah memiliki API token Kaggle.
- Dataset ini cukup besar, disarankan menggunakan runtime dengan memori mencukupi.

Kontak:
-------
Jonatan Sihombing
I Made Wisnu
Novanditya Rhakahadi

