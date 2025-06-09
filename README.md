# 📊 Proyek Analisis Data: Klasifikasi & Clustering

## 🧠 Deskripsi Proyek

Proyek ini terdiri dari dua bagian utama:
1. **Klasifikasi** data pelanggan untuk memprediksi ketertarikan terhadap produk.
2. **Clustering** data untuk mengelompokkan pelanggan berdasarkan karakteristik demografis dan perilaku.

Dataset yang digunakan merupakan bagian dari tugas akhir program **Bangkit Machine Learning Path**.

---

## 📂 Struktur Proyek

├── [Klasifikasi]Submission_Akhir_BMLP_Muhamamd_Faris_Kurniawan.ipynb

├── [Clustering]_Submission_Akhir_BMLP_Muhammad_Faris_Kurniawan.ipynb

├── dataset_inisiasi.csv

├── dataset_clustering.csv


---

## ⚙️ Tools & Library

- Python 3.9
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Yellowbrick

---

## 📌 1. Klasifikasi

### 🎯 Tujuan
Memprediksi apakah pelanggan akan membeli produk (`purchased = 1`) berdasarkan fitur-fitur berikut:
- Age
- Estimated Salary
- Gender (yang sudah diubah ke numerik)

### 🔍 Langkah-Langkah
- **Preprocessing:** Encoding kolom Gender, scaling fitur numerik
- **Modeling:** Logistic Regression, Decision Tree, dan Random Forest
- **Evaluasi:** Akurasi, confusion matrix, classification report, dan ROC-AUC

### ✅ Hasil
Model terbaik menunjukkan akurasi lebih dari 90%, dengan performa ROC-AUC yang baik dalam membedakan kelas target.

---

## 📌 2. Clustering

### 🎯 Tujuan
Mengelompokkan pelanggan berdasarkan:
- Age
- Annual Income
- Spending Score

### 🔍 Langkah-Langkah
- **EDA:** Visualisasi distribusi dan korelasi antar fitur
- **Normalisasi:** Menggunakan `StandardScaler`
- **Modeling:** K-Means clustering
- **Evaluasi:** Elbow Method, Silhouette Score
- **Visualisasi:** Scatter plot hasil clustering (2D & 3D)

### ✅ Hasil
Didapatkan jumlah cluster optimal (3-5 cluster) dengan karakteristik:
- Cluster dengan pengeluaran tinggi, penghasilan sedang
- Cluster dengan penghasilan tinggi, pengeluaran rendah
- Cluster yang merupakan target pasar potensial

---

## 📈 Visualisasi

Notebook menyertakan berbagai visualisasi, antara lain:
- Confusion Matrix
- ROC Curve
- Cluster Visualization
- Elbow Curve
- Silhouette Analysis

---

## 📚 Insight Bisnis

- **Klasifikasi:** Dapat digunakan untuk prediksi prospek pelanggan terhadap produk.
- **Clustering:** Membantu membangun segmentasi pelanggan untuk strategi pemasaran yang lebih efektif.

---

## 🚀 Cara Menjalankan Proyek

1. Pastikan environment Python 3.9 sudah siap.
2. Install dependensi dengan:
   ```bash
   pip install -r requirements.txt
