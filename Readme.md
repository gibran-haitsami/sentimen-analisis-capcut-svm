# Analisis Sentimen Ulasan Aplikasi CapCut (SVM)

Repositori ini memuat dataset publik yang digunakan dalam penelitian Skripsi berjudul **"[Masukkan Judul Skripsi Anda]"**. Penelitian ini bertujuan mengklasifikasikan sentimen pengguna aplikasi CapCut di Google Play Store ke dalam kelas Positif dan Negatif menggunakan algoritma Support Vector Machine (SVM).

## 📂 Struktur Dataset
Terdapat dua file utama dalam repositori ini:

### 1. `raw_data_capcut_3000.csv` (Dataset Mentah)
Merupakan data asli hasil *web scraping* dari Google Play Store tanpa modifikasi.
- **Tanggal Scraping:** 01 Desember 2025
- **Jumlah Data:** 3.000 baris
- **Atribut:**
  - `userName`: Nama pengguna
  - `content`: Isi ulasan (teks asli)
  - `score`: Rating bintang (1-5)
  - `at`: Tanggal dan waktu ulasan

### 2. `clean_data_preprocessed.csv` (Dataset Bersih)
Merupakan data yang telah melalui tahapan *Preprocessing* (Cleaning, Case Folding, Normalisasi, Stopword Removal, Stemming) dan *Labeling*.
- **Jumlah Data:** [Masukkan jumlah data akhir setelah cleaning]
- **Atribut Tambahan:**
  - `text_clean`: Teks hasil preprocessing
  - `label`: Label sentimen (1 = Positif, 0 = Negatif)

## 🛠️ Metode
- **Teknik Pengumpulan Data:** Web Scraping menggunakan library `google-play-scraper`.
- **Algoritma Klasifikasi:** Support Vector Machine (SVM) dengan Kernel Linear.
- **Penanganan Imbalanced Data:** SMOTE.

## 👤 Penulis
[Nama Lengkap Anda]
[Nama Universitas]
