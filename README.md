# NLP
This project is part of a learning part in Machine learning, NLP, and AI Training 
# NLP Text Classification with TF-IDF and Logistic Regression

This project presents a simple and educational **Natural Language Processing (NLP)** pipeline built with **classical Machine Learning techniques** in Python.

The goal is to demonstrate how raw text can be cleaned, transformed into numerical features, and used to train a supervised model for **text sentiment classification**.

---

## 📌 Project Description

The project uses a small sample dataset of short sentences and classifies them into two categories:

- **Positive (1)**
- **Negative (0)**

It is designed for learning purposes and to illustrate the complete workflow of an NLP classification task, from preprocessing to prediction.

---

## 🧠 Approach and Methodology

The workflow implemented in this project follows these steps:

1. Text normalization (lowercasing)
2. Removal of punctuation
3. Stopword removal using NLTK
4. Feature extraction using **TF-IDF**
5. Use of **unigrams and bigrams** to capture context
6. Model training with **Logistic Regression**
7. Evaluation using standard classification metrics
8. Prediction on new, unseen text

---

## ⚙️ Technologies Used

- Python 3
- NLTK
- scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- VS Code

---

## 📂 Dataset

The dataset is a small, manually created set of sentences related to learning Machine Learning.

Example labels:
- `1` → Positive sentiment
- `0` → Negative sentiment

This dataset is intended **only for demonstration and educational purposes**.

---

## 📊 Model Evaluation

The model performance is evaluated using `classification_report` from `scikit-learn`, which includes:

- Precision
- Recall
- F1-score
- Accuracy

Due to the small dataset size, metrics are illustrative rather than statistically significant.

---

## 🔮 Example Prediction

```text
Input: "This is the first time"
Output: positive
