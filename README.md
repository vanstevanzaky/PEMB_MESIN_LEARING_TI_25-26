# 🤖 Pembelajaran Mesin - TI 3A (2025/2026)

<div align="center">

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

**Repository untuk tugas dan praktikum mata kuliah Pembelajaran Mesin**  
*Jurusan Teknologi Informasi - Politeknik Negeri Malang*

[📚 Tentang](#-tentang) •
[🎯 Topik Pembelajaran](#-topik-pembelajaran) •
[📂 Struktur Repository](#-struktur-repository) •
[🚀 Cara Penggunaan](#-cara-penggunaan) •
[📖 Referensi](#-referensi)

</div>

---

## 📚 Tentang

Selamat datang di repository **Pembelajaran Mesin**! 🎉

Pada mata kuliah ini, kita akan belajar bagaimana sebuah mesin dapat meniru kecerdasan kognitif yang dimiliki oleh manusia untuk menyelesaikan permasalahan sehari-hari. Anda tidak hanya akan belajar bagaimana cara membuat "*mesin cerdas*", namun juga belajar mengenai **etika penggunaan teknologi kecerdasan buatan**.

### 🎓 Tujuan Pembelajaran

- ✅ Memahami konsep dasar Artificial Intelligence, Machine Learning, dan Deep Learning
- ✅ Menguasai teknik preprocessing dan ekstraksi fitur data
- ✅ Mampu membangun model Regresi, Klasifikasi, dan Clustering
- ✅ Dapat mengevaluasi dan melakukan deployment model ML
- ✅ Memahami etika dan tantangan dalam pengembangan AI

---

## 🎯 Topik Pembelajaran

Repository ini mencakup materi praktikum untuk 9 topik utama:

| Minggu | Topik | Deskripsi | Status |
|--------|-------|-----------|--------|
| **1** | 🌟 **Pengenalan ML** | Konsep AI, ML, DL, GenAI dan tipe-tipe pembelajaran | ✅ |
| **2** | 🔍 **Ekstraksi Fitur** | Feature extraction dan feature engineering | ✅ |
| **3** | 🧹 **Preprocessing Data** | Data cleaning, normalization, handling missing values | ✅ |
| **5** | 🎨 **Klasterisasi (1)** | K-Means, DBSCAN, Hierarchical Clustering | ✅ |
| **6** | 🎨 **Klasterisasi (2)** | Lanjutan clustering dan evaluasi | ✅ |
| **7** | 🎨 **Klasterisasi (3)** | Advanced clustering techniques | ✅ |
| **9** | 📈 **Regresi** | Linear Regression, Polynomial Regression | ✅ |
| **10** | 🎯 **Klasifikasi (1)** | Decision Tree, Random Forest, KNN | ✅ |
| **11** | 🎯 **Klasifikasi (2)** | SVM, Logistic Regression, Neural Networks | ✅ |

### 📝 Tugas & Kuis

- 📋 **Kuis 1**: EDA & Preprocessing
- 📋 **UTS**: Ujian Tengah Semester

---

## 📂 Struktur Repository

```
📦 PEMB_MESIN_LEARING_TI_25-26
┣ 📓 Week2_Ekstraksi-Fitur.ipynb
┣ 📓 Week3_Preprocessing-Data.ipynb
┣ 📓 Week5_Klasterisasi.ipynb
┣ 📓 Week6.ipynb
┣ 📓 Week7_Klasterisasi(3).ipynb
┣ 📓 Week9_Regresi.ipynb
┣ 📓 Week10_klasifikasi.ipynb
┣ 📓 Week11_klasifikasi_2.ipynb
┣ 📋 Kuis1_ML_EDA_Preprocessing_V3.ipynb
┣ 📋 UTS_Stevan Zaky S_28_TI-3A.ipynb
┗ 📄 README.md
```

---

## 🚀 Cara Penggunaan

### Prerequisites

Pastikan Anda telah menginstall:
- 🐍 Python 3.8+
- 📊 Jupyter Notebook / JupyterLab
- 📚 Library ML: numpy, pandas, scikit-learn, matplotlib, seaborn

### Instalasi

```bash
# Clone repository
git clone https://github.com/vanstevanzaky/PEMB_MESIN_LEARING_TI_25-26.git

# Masuk ke direktori
cd PEMB_MESIN_LEARING_TI_25-26

# Install dependencies (jika ada requirements.txt)
pip install -r requirements.txt

# Jalankan Jupyter Notebook
jupyter notebook
```

### Menjalankan Notebook

1. Buka file `.ipynb` yang ingin dipelajari
2. Jalankan cell secara berurutan dari atas ke bawah
3. Pastikan semua library telah terinstall dengan benar

---

## 🧠 Konsep Penting

### AI vs ML vs DL vs GenAI

```
┌─────────────────────────────────────────┐
│        Artificial Intelligence          │
│  ┌───────────────────────────────────┐  │
│  │      Machine Learning             │  │
│  │  ┌─────────────────────────────┐  │  │
│  │  │    Deep Learning            │  │  │
│  │  │  ┌───────────────────────┐  │  │  │
│  │  │  │  Generative AI        │  │  │  │
│  │  │  └───────────────────────┘  │  │  │
│  │  └─────────────────────────────┘  │  │
│  └───────────────────────────────────┘  │
└─────────────────────────────────────────┘
```

### Tipe Pembelajaran Mesin

| Tipe | Karakteristik | Contoh Algoritma |
|------|---------------|------------------|
| **Supervised Learning** | Menggunakan labeled data | Linear Regression, SVM, Decision Tree |
| **Unsupervised Learning** | Menggunakan unlabeled data | K-Means, DBSCAN, PCA |
| **Semi-supervised Learning** | Kombinasi labeled & unlabeled | Pseudo-labeling |
| **Reinforcement Learning** | Belajar dari reward/penalty | Q-Learning, Deep Q-Network |

---

## 🌟 Highlights

### ✨ Yang Dipelajari

- 🔬 **Exploratory Data Analysis (EDA)** - Memahami karakteristik data
- 🧪 **Feature Engineering** - Menciptakan fitur yang informatif
- 🎯 **Model Building** - Membangun model ML yang akurat
- 📊 **Model Evaluation** - Mengevaluasi performa model
- 🚀 **Best Practices** - Implementasi etika AI yang bertanggung jawab

### 🛠️ Tools & Libraries

- **NumPy** - Komputasi numerik
- **Pandas** - Manipulasi dan analisis data
- **Scikit-learn** - Algoritma ML dan preprocessing
- **Matplotlib & Seaborn** - Visualisasi data
- **Jupyter Notebook** - Interactive development environment

---

## ⚖️ Etika AI yang Bertanggung Jawab

Dalam pengembangan model ML, kita berpegang pada 6 prinsip Microsoft Responsible AI:

1. ⚖️ **Fairness** - Memperlakukan semua orang sama
2. 🛡️ **Reliability & Safety** - Bekerja reliabel dan aman
3. 🔒 **Privacy & Security** - Menghormati privasi pengguna
4. 🌍 **Inclusiveness** - Memfasilitasi semua kalangan
5. 🔍 **Transparency** - Dapat dipahami (Explainable AI)
6. 👥 **Accountability** - Manusia bertanggung jawab atas AI

---

## 📖 Referensi

- 📘 Géron, A. (2019). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*
- 🌐 [IBM - What is AI?](https://www.ibm.com/think/topics/artificial-intelligence)
- 🌐 [Microsoft - Responsible AI](https://www.microsoft.com/en-us/ai/principles-and-approach)
- 📚 Modul Praktikum Pembelajaran Mesin - JTI POLINEMA

---

## 👨‍🎓 Informasi Mahasiswa

**Nama**: Stevan Zaky S  
**NIM**: 2341720101  
**Kelas**: TI-3A  
**Prodi**: D4 Teknik Informatika  
**Institusi**: Politeknik Negeri Malang

---

## 📝 Lisensi

Repository ini dibuat untuk keperluan pembelajaran mata kuliah Pembelajaran Mesin.

---

<div align="center">

**⭐ Jangan lupa berikan star jika repository ini bermanfaat! ⭐**

*Made with ❤️ for Machine Learning Course*

**Tim Pengajar Pembelajaran Mesin**  
**Jurusan Teknologi Informasi - POLINEMA**  
**© 2025**

</div>