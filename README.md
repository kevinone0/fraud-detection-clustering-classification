# 🤖 Submission Akhir BMLP — Rifqi Zaghlul

> Proyek akhir kursus **Belajar Machine Learning untuk Pemula (BMLP)** di Dicoding, mencakup dua task utama: **Klasifikasi** dan **Clustering**.

---

## 📁 Struktur Proyek

```
├── _Klasifikasi__Submission_Akhir_BMLP_Rifqi_Zaghlul.ipynb
├── _Clustering__Submission_Akhir_BMLP_Rifqi_Zaghlul.ipynb
├── data_clustering.csv
└── README.md
```

---

## 📌 Overview

| Task | Metode | File |
|------|--------|------|
| Klasifikasi | Supervised Learning | `_Klasifikasi__Submission_Akhir_BMLP_Rifqi_Zaghlul.ipynb` |
| Clustering | Unsupervised Learning | `_Clustering__Submission_Akhir_BMLP_Rifqi_Zaghlul.ipynb` |

---

## 🔵 1. Klasifikasi

### Deskripsi
Notebook ini menerapkan algoritma **klasifikasi** untuk memprediksi label/kelas dari suatu data menggunakan pendekatan *supervised learning*.

### Alur Kerja
1. **Import Library** — Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
2. **Load & Eksplorasi Data** — Melihat shape, info, statistik deskriptif, dan distribusi data
3. **Preprocessing**
   - Handling missing values
   - Encoding fitur kategorikal
   - Feature scaling / normalisasi
4. **Split Data** — Train/test split
5. **Pelatihan Model** — Membangun model klasifikasi
6. **Evaluasi Model** — Accuracy, Precision, Recall, F1-Score, Confusion Matrix
7. **Kesimpulan**

---

## 🟢 2. Clustering

### Deskripsi
Notebook ini menerapkan algoritma **clustering** untuk mengelompokkan data tanpa label menggunakan pendekatan *unsupervised learning*.

### Dataset
Dataset yang digunakan: `data_clustering.csv`

### Alur Kerja
1. **Import Library** — Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
2. **Load & Eksplorasi Data** — Analisis distribusi dan karakteristik data
3. **Preprocessing**
   - Handling missing values
   - Feature scaling / normalisasi
4. **Penentuan Jumlah Cluster** — Elbow Method / Silhouette Score
5. **Pelatihan Model** — K-Means Clustering (atau algoritma lain)
6. **Visualisasi Cluster** — Plot 2D hasil pengelompokan
7. **Analisis & Interpretasi** — Karakteristik tiap cluster
8. **Kesimpulan**

---

## 🛠️ Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

Atau jalankan semua dependencies sekaligus:

```bash
pip install -r requirements.txt
```

### Versi utama yang digunakan:
- Python >= 3.8
- pandas >= 1.3
- scikit-learn >= 1.0
- matplotlib >= 3.4
- seaborn >= 0.11

---

## 🚀 Cara Menjalankan

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/username/nama-repo.git
   cd nama-repo
   ```

2. **Install dependencies:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. **Jalankan Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. Buka notebook sesuai task yang ingin dijalankan.

---

## 📊 Hasil

### Klasifikasi
- Model berhasil dilatih dan dievaluasi menggunakan metrik standar klasifikasi.
- Detail hasil evaluasi tersedia di dalam notebook.

### Clustering
- Data berhasil dikelompokkan ke dalam beberapa cluster yang bermakna.
- Visualisasi hasil clustering tersedia di dalam notebook.

---

## 👤 Author

**Rifqi Zaghlul**

- 📚 Kursus: Belajar Machine Learning untuk Pemula — Dicoding
- 🏅 Submission: Proyek Akhir

---

## 📝 Lisensi

Proyek ini dibuat untuk keperluan pembelajaran dalam rangka submission kursus Dicoding BMLP.
