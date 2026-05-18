# 📧 Spam Email Detection using Logistic Regression

A Machine Learning project that predicts whether an email/message is **Spam** or **Ham (Not Spam)** using **Logistic Regression** and **Natural Language Processing (NLP)** techniques.

---

# 🚀 Project Overview

This project uses:

- Python
- Scikit-learn
- NLP
- TF-IDF Vectorization
- Logistic Regression

to classify text messages into:

- Spam
- Not Spam

The model learns patterns from words commonly found in spam messages such as:

- free
- win
- urgent
- congratulations

and predicts whether a new message is spam or not.

---

# 🧠 Machine Learning Workflow

```text
Load Dataset
     ↓
Text Cleaning
     ↓
Remove Stopwords
     ↓
TF-IDF Vectorization
     ↓
Train-Test Split
     ↓
Train Logistic Regression Model
     ↓
Prediction
     ↓
Model Evaluation
