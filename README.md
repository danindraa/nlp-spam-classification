![Python](https://img.shields.io/badge/Python-3.10-blue)
![License](https://img.shields.io/github/license/danindraa/nlp-spam-classification)
![Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow)


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
nlp-spam-classification/

│

├── data/

│ └── emails.csv

│

├── notebooks/

│ ├── 1_preprocessing_vectorization.ipynb

│ ├── 2_ml_models.ipynb

│ ├── 3_lstm_model.ipynb

│ └── 4_transformer_model.ipynb

│

├── .gitignore

├── LICENSE

├── README.md

└── requirements.txt

## 💻 Cara Menjalankan

1. Clone repositori:

bash
git clone https://github.com/danindraa/nlp-spam-classification.git
cd nlp-spam-classification

2. Install dependensi

pip install -r requirements.txt

3. Jalankan notebook

Buka folder notebooks/, lalu jalankan file .ipynb satu per satu sesuai urutan:

1_preprocessing_vectorization.ipynb

2_ml_models.ipynb

3_lstm_model.ipynb

4_transformer_model.ipynb
