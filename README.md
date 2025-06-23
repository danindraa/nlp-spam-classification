# 📧 NLP Spam Email Classification

Proyek ini mengklasifikasikan email sebagai **spam** atau **non-spam** menggunakan Natural Language Processing (NLP), Machine Learning, dan Deep Learning.

---

## 📂 Dataset

Dataset `emails.csv` berisi **5.731 email** dengan dua kolom:
- `text`: isi email
- `spam`: label (0 = non-spam, 1 = spam)

Disimpan di: `data/emails.csv`

---

## ⚙️ Fitur dan Model

- Preprocessing teks: lowercasing, remove symbols, stopwords, stemming
- Vectorization: BoW, TF-IDF, Word2Vec, GloVe, FastText
- Machine Learning: Logistic Regression, SVM, Random Forest, KNN
- Deep Learning: LSTM, Transformer (Keras)

---

## 🛠️ Cara Menjalankan

1. Clone repo:
```bash
git clone https://github.com/danindraa/nlp-spam-classification.git
cd nlp-spam-classification
