# 📨 NLP Spam Classification

Proyek ini bertujuan untuk mengklasifikasi email sebagai spam atau non-spam menggunakan teknik Natural Language Processing (NLP), Machine Learning, dan Deep Learning.

## 📁 Dataset
- Dataset: `emails.csv`
- Jumlah data: 5.731 email
- Kolom: `text` (isi email), `label` (1 = spam, 0 = ham)
- Sumber: Kaggle

## 🔍 Tahapan Proyek

### 1. Preprocessing & Vektorisasi
- Cleaning: lowercase, hapus karakter non-alfabet, stopword removal, stemming
- Tokenisasi teks
- Vektorisasi:
  - Bag of Words
  - TF-IDF
  - Word2Vec
  - GloVe
  - FastText

### 2. Machine Learning
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbor (KNN)
- KMeans Clustering (unsupervised)

### 3. Deep Learning
- **LSTM Model**: menggunakan layer embedding dan LSTM
- **Transformer Model**: menggunakan Multi-Head Attention, Layer Normalization, dan Dense layer

### 4. Evaluasi
- Metode evaluasi:
  - Classification report (presisi, recall, f1-score)
  - Akurasi model
  - Distribusi cluster untuk unsupervised

## 📂 Struktur Folder

