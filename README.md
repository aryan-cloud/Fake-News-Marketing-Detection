# Fake News & Marketing Detection

# 📰 Fake News & Marketing Detection

This project aims to detect **fake news** and **manipulative marketing content** using advanced machine learning techniques. It utilizes a large real-world dataset and compares the performance of traditional ML models, a transformer-based model, and an ensemble voting approach.

---

## 📊 Project Overview

In today's world of digital misinformation, it’s critical to identify and combat fake news and paid PR propaganda. This project addresses the issue by applying multiple classification models on a labeled dataset of real and fake news articles.

---

## 🧠 Models Compared

- ✅ **BERTweet Transformer Model**
- ✅ **Classical ML Models** (Logistic Regression, Naive Bayes, SVM, Random Forest)
- ✅ **Ensemble Voting Classifier** (Majority voting across the above models)

---

## 📂 Dataset Details

- **Source**: [Fake and Real News Dataset on Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news)
- **Files**:
  - `Fake.csv`: 23,502 articles
  - `True.csv`: 21,417 articles
- **Columns**:
  - `title`: Headline of the article
  - `text`: Full article content
  - `subject`: News category
  - `date`: Publication date

---

## ⚙️ Tech Stack

- Python 3.9+
- Pandas, NumPy, Scikit-learn
- PyTorch, HuggingFace Transformers
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repo:
```bash
git clone https://github.com/your-username/fake-news-marketing-detector.git
cd fake-news-marketing-detector
