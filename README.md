# Submission BMLP - Septian Hadi Nugroho

Repositori ini berisi kode sumber dan model untuk proyek submission akhir **Belajar Machine Learning Pemula (BMLP)**. Proyek ini mencakup dua tugas utama pembelajaran mesin: **Clustering (Unsupervised Learning)** dan **Klasifikasi (Supervised Learning)**.

**Pembuat:** Septian Hadi Nugroho

## 📂 Struktur File

Berikut adalah penjelasan mengenai file-file yang terdapat dalam repositori ini:

### 1\. Jupyter Notebooks (Kode Utama)

  * **`[Clustering]_Submission_Akhir_BMLP_Septian Hadi Nugroho.ipynb`**
    Notebook ini berisi seluruh proses untuk tugas Clustering. Mulai dari pemuatan data, *Exploratory Data Analysis* (EDA), *preprocessing*, reduksi dimensi (PCA), hingga pemodelan dan evaluasi clustering.
  * **`[Klasifikasi]_Submission_Akhir_BMLP_Septian Hadi Nugroho.ipynb`**
    Notebook ini berisi seluruh proses untuk tugas Klasifikasi. Mencakup pembersihan data, visualisasi, pelatihan model (Decision Tree & Random Forest), *hyperparameter tuning*, dan evaluasi model.

### 2\. Dataset

  * **`data_clustering.csv`**: Dataset mentah yang digunakan untuk proses analisis clustering.
  * **`data_clustering_inverse.csv`**: Dataset hasil pemrosesan (kemungkinan hasil *inverse transform* dari penskalaan data) untuk keperluan interpretasi.

### 3\. Model Tersimpan (Saved Models)

File-file berekstensi `.h5` ini adalah model yang telah dilatih dan disimpan agar dapat digunakan kembali tanpa perlu melatih ulang:

  * **`PCA_model_clustering.h5`**: Model PCA untuk reduksi dimensi pada data clustering.
  * **`model_clustering.h5`**: Model final hasil algoritma clustering.
  * **`decision_tree_model.h5`**: Model klasifikasi menggunakan algoritma Decision Tree.
  * **`explore_RandomForest_classification.h5`**: Model hasil eksplorasi menggunakan Random Forest.
  * **`tuning_classification.h5`**: Model klasifikasi terbaik setelah proses *hyperparameter tuning*.

## 🚀 Gambaran Proyek

### A. Clustering

Pada bagian ini, tujuan utamanya adalah mengelompokkan data ke dalam beberapa klaster berdasarkan karakteristik yang mirip.

  * **Metode:** Menggunakan PCA untuk reduksi fitur dan algoritma Clustering (seperti K-Means atau Hierarchical Clustering).
  * **Output:** Label klaster untuk setiap data point.

### B. Klasifikasi

Pada bagian ini, tujuan utamanya adalah memprediksi label atau kategori target.

  * **Algoritma:** Decision Tree dan Random Forest.
  * **Proses:** Termasuk pencarian parameter terbaik (*tuning*) untuk meningkatkan akurasi model.

## 🛠️ Cara Menjalankan

1.  **Clone repositori ini:**
    ```bash
    git clone https://github.com/septianhadinugroho/bmlp_septian-hadi-nugroho.git
    ```
2.  **Pastikan environment Python Anda memiliki library berikut:**
      * Pandas
      * NumPy
      * Matplotlib / Seaborn
      * Scikit-Learn
      * TensorFlow/Keras (jika format .h5 menggunakan library ini) atau H5py
3.  **Buka Jupyter Notebook:**
    Jalankan perintah `jupyter notebook` di terminal/cmd, lalu buka salah satu file `.ipynb` yang ingin dijalankan.

-----

*Dibuat sebagai syarat kelulusan kelas Belajar Machine Learning Pemula.*
