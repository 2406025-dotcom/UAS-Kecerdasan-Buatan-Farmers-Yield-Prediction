# 🌾 UAS Kecerdasan Buatan

## Klasifikasi Tingkat Produktivitas Hasil Panen Petani Menggunakan Algoritma Decision Tree dan K-Nearest Neighbor (KNN)

# 📖 Deskripsi Proyek

Proyek ini merupakan tugas besar Mata Kuliah **Kecerdasan Buatan** Program Studi Teknik Informatika.

Penelitian bertujuan membangun model **Machine Learning** untuk mengklasifikasikan tingkat produktivitas hasil panen petani berdasarkan karakteristik petani serta aktivitas pertanian menggunakan algoritma **Decision Tree** dan **K-Nearest Neighbor (KNN)**.

Seluruh proses penelitian mengikuti metodologi **CRISP-DM (Cross Industry Standard Process for Data Mining)** mulai dari Business Understanding hingga Evaluation.

---

# 👨‍💻 Anggota Kelompok

| Nama                    | NIM     |
| ----------------------- | ------- |
| Muhammad Saepul Hidayat | 2406025 |
| Maulana Muhammad Zaki   | 2406028 |

---

# 📑 Daftar Isi

- Deskripsi Proyek
- Tujuan Penelitian
- Dataset
- Struktur Repository
- Tahapan Penelitian
- Algoritma
- Hasil Model
- Visualisasi
- Tools
- Cara Menjalankan
- Referensi

---

# 🎯 Tujuan Penelitian

Penelitian ini bertujuan untuk:

- Menganalisis faktor-faktor yang memengaruhi produktivitas hasil panen petani.
- Melakukan klasifikasi produktivitas menggunakan algoritma Decision Tree.
- Melakukan klasifikasi produktivitas menggunakan algoritma K-Nearest Neighbor.
- Membandingkan performa kedua algoritma.
- Menentukan model terbaik berdasarkan hasil evaluasi.

---

# 📊 Dataset

Dataset yang digunakan adalah **Farmers Dataset**.

| Informasi      | Keterangan   |
| -------------- | ------------ |
| Jumlah Data    | 1000         |
| Jumlah Atribut | 14           |
| Target         | Productivity |

Variabel target diperoleh dari hasil kategorisasi nilai **Yield_per_Acre_kg** menjadi tiga kelas:

- 🔴 Low
- 🟡 Medium
- 🟢 High

---

# 📂 Struktur Repository

```text
UAS-Kecerdasan-Buatan-Farmers-Yield-Prediction
│
├── README.md
├── Laporan_UAS.md
├── uas_model.ipynb
│
├── Data
│     └── farmers_dataset.csv
│
├── images
│     ├── Distribusi_Variabel_Numerik.png
│     ├── Distribusi_Kelas_Productivity.png
│     ├── Distribusi_Ukuran_Lahan.png
│     ├── Distribusi_Jenis_Tanaman.png
│     ├── Heatmap_Korelasi.png
│     ├── Analisis_Pairplot.png
│     ├── Deteksi_Outlier.png
│     ├── Decision_Tree.png
│     ├── Confusion_Matrix_Decision_Tree.png
│     ├── Confusion_Matrix_KNN.png
│     └── Perbandingan_Performa_Model.png
│
└── Jurnal
      ├── jurnal_1.pdf
      ├── jurnal_2.pdf
      ├── jurnal_3.pdf
      ├── jurnal_4.pdf
      └── jurnal_5.pdf
```

---

# 🔄 Tahapan Penelitian (CRISP-DM)

✅ Business Understanding

- Identifikasi permasalahan
- Penentuan tujuan penelitian

---

✅ Data Understanding

- Jumlah data
- Struktur dataset
- Statistik deskriptif
- Missing Value
- Tipe data

---

✅ Exploratory Data Analysis (EDA)

Melakukan analisis data menggunakan:

- Histogram
- Pie Chart
- Bar Chart
- Pairplot
- Heatmap
- Boxplot
- Analisis Korelasi

---

✅ Data Preparation

Tahapan preprocessing meliputi:

- Missing Value Checking
- Duplicate Checking
- Label Encoding
- Feature Selection
- Standardisasi Data
- Train-Test Split

---

✅ Modeling

Algoritma yang digunakan:

- 🌳 Decision Tree
- 👥 K-Nearest Neighbor (KNN)

Dilanjutkan dengan proses **Hyperparameter Tuning** menggunakan **GridSearchCV**.

---

✅ Evaluation

Model dievaluasi menggunakan:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# 📈 Hasil Evaluasi Model

| Model         |   Accuracy |  Precision |     Recall |   F1-Score |
| ------------- | ---------: | ---------: | ---------: | ---------: |
| Decision Tree |     0.3250 |     0.3246 |     0.3250 |     0.3247 |
| KNN           | **0.3600** | **0.3645** | **0.3600** | **0.3507** |

Berdasarkan hasil evaluasi, algoritma **K-Nearest Neighbor (KNN)** memberikan performa terbaik dibandingkan Decision Tree.

---

# 🖼️ Hasil Visualisasi

## Distribusi Variabel Numerik

![](images/Distribusi_Variabel_Numerik.png)

---

## Distribusi Produktivitas

![](images/Distribusi_Kelas_Productivity.png)

---

## Heatmap Korelasi

![](images/Heatmap_Korelasi.png)

---

## Decision Tree

![](images/Decision_Tree.png)

---

## Perbandingan Performa Model

![](images/Perbandingan_Performa_Model.png)

---

# 🛠️ Tools

### Bahasa Pemrograman

- Python

### Library

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Platform

- Visual Studio Code
- Google Colab
- GitHub

---

# ▶️ Cara Menjalankan

### 1. Clone Repository

```bash
git clone https://github.com/2406025-dotcom/UAS-Kecerdasan-Buatan-Farmers-Yield-Prediction.git
```

### 2. Masuk ke Folder

```bash
cd UAS-Kecerdasan-Buatan-Farmers-Yield-Prediction
```

### 3. Install Library

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Jalankan Notebook

Buka file:

```
uas_model.ipynb
```

menggunakan:

- Google Colab
- Jupyter Notebook
- Visual Studio Code

---

# 📚 Referensi

- Agronomy (2020). _Crop Yield Prediction through Proximal Sensing and Machine Learning Algorithms._
- Informatics (2022). _Machine Learning Applied to Tree Crop Yield Prediction._
- Agriculture (2024). _Crop Recommendation Using Machine Learning._
- Sustainability (2021). _Forecasting Rainfed Agricultural Production._
- Remote Sensing (2025). _Meta-Features Extracted from Use of KNN._

---

# ⭐ Hasil Akhir

Penelitian berhasil membangun model klasifikasi produktivitas petani menggunakan algoritma **Decision Tree** dan **K-Nearest Neighbor (KNN)**. Berdasarkan hasil evaluasi, algoritma **KNN** memberikan performa terbaik dengan **Accuracy sebesar 36,00%**, sehingga dipilih sebagai model terbaik pada penelitian ini.
