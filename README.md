# Identifikasi Dataset Machine Learning

## Deskripsi Proyek

Proyek ini membahas identifikasi dan analisis tiga jenis dataset dalam Machine Learning berdasarkan jenis permasalahan klasifikasinya, yaitu Binary Classification, Multiclass Classification, dan Multilabel Classification.

Analisis dilakukan menggunakan Python melalui Jupyter Notebook. Setiap dataset diperiksa secara terpisah berdasarkan struktur data, fitur, target, distribusi kelas, visualisasi, serta penerapan model Machine Learning.

## Dataset yang Digunakan

### 1. GDM Synthetic Dataset
- Jenis: Binary Classification
- Tujuan: Mengidentifikasi data berdasarkan dua kategori target.
- Analisis: Pemeriksaan data, distribusi kelas, visualisasi, pemodelan, dan evaluasi.

### 2. Iris Dataset
- Jenis: Multiclass Classification
- Tujuan: Mengelompokkan bunga Iris ke dalam beberapa kategori spesies.
- Analisis: Pemeriksaan fitur, distribusi spesies, visualisasi, pemodelan, dan evaluasi.

### 3. Multi-Label Research Papers
- Jenis: Multilabel Classification
- Tujuan: Mengidentifikasi kategori artikel penelitian berdasarkan judul dan abstrak.
- Label: Computer Science, Physics, Mathematics, Statistics, Quantitative Biology, dan Quantitative Finance.
- Analisis: Distribusi label, hubungan antarlabel, pengolahan teks, pemodelan, dan evaluasi.

Sumber dataset Multilabel:
https://www.kaggle.com/datasets/shivanandmn/multilabel-classification-dataset

## Metode dan Tahapan Analisis

1. Mengimpor library Python yang dibutuhkan.
2. Membaca ketiga dataset dalam format CSV.
3. Memeriksa struktur, tipe data, dan ukuran dataset.
4. Memeriksa missing value dan data duplikat.
5. Mengidentifikasi fitur dan target.
6. Melakukan visualisasi data.
7. Menerapkan model klasifikasi sesuai jenis dataset.
8. Melakukan evaluasi hasil model.
9. Membandingkan dan menyusun kesimpulan.

## Algoritma dan Evaluasi

Pemodelan dilakukan menggunakan algoritma klasifikasi yang sesuai dengan karakteristik masing-masing dataset.

Evaluasi Binary dan Multiclass menggunakan akurasi serta laporan klasifikasi. Sementara itu, evaluasi Multilabel menggunakan Exact Match Accuracy, Hamming Loss, dan Micro F1-Score.

Pada pemodelan Multilabel, data dibatasi maksimal 5.000 baris secara acak untuk menjaga proses tetap ringan.

## Teknologi yang Digunakan

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Struktur Proyek

```text
Identifikasi_Dataset_Machine_Learning/
│
├── Identifikasi_Dataset_Machine_Learning_Revisi.ipynb
├── gdm_synthetic_data.csv
├── iris.csv
├── train_multilabel.csv
└── README.md
```

## Cara Menjalankan Proyek

1. Clone atau download repository ini.
2. Pastikan Python dan Jupyter Notebook sudah terpasang.
3. Pastikan seluruh file CSV berada dalam folder yang sama dengan notebook.
4. Buka file `Identifikasi_Dataset_Machine_Learning_Revisi.ipynb`.
5. Jalankan seluruh cell menggunakan fitur Run All.

## Kesimpulan

Berdasarkan proses identifikasi, ketiga dataset memiliki karakteristik target yang berbeda. GDM Synthetic termasuk Binary Classification, Iris termasuk Multiclass Classification, dan Multi-Label Research Papers termasuk Multilabel Classification.

Ketiganya merupakan permasalahan Classification karena bertujuan memprediksi kategori atau label, bukan nilai numerik kontinu seperti pada Regression.
