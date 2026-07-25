# 🤖 Hands-on: Sentiment Analysis using Sentence Transformers

## 📖 Overview

This project demonstrates how to use **Sentence Transformers** to generate meaningful sentence embeddings for **sentiment analysis**. It also compares traditional **Word2Vec embeddings** with **Transformer-based embeddings** to understand how semantic representations improve text classification.

The project uses machine learning techniques to classify movie reviews as **Positive** or **Negative** based on their sentiment.

---

## 🎯 Objective

- Understand the concept of text embeddings.
- Learn how Sentence Transformers generate semantic representations.
- Compare **Word2Vec** and **Sentence Transformer** embeddings.
- Build a sentiment analysis model using machine learning.
- Evaluate the performance of different embedding techniques.

---

## 🛠️ Tools & Technologies

- Python
- Sentence Transformers (`all-MiniLM-L6-v2`)
- Gensim (Word2Vec)
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Dataset

The project uses a **Movie Reviews Dataset** containing text reviews with binary sentiment labels.

| Label | Sentiment |
|-------|-----------|
| 0 | Negative 😞 |
| 1 | Positive 😊 |

---

## ⚙️ Project Workflow

1. Import required libraries.
2. Load and explore the movie review dataset.
3. Clean and preprocess the text.
4. Generate embeddings using:
   - Word2Vec
   - Sentence Transformers (`all-MiniLM-L6-v2`)
5. Train a **Random Forest Classifier**.
6. Evaluate the model using standard classification metrics.
7. Compare the performance of different embedding techniques.

---

## 🏆 Best Approach

- **Embedding Model:** Sentence Transformer (`all-MiniLM-L6-v2`)
- **Classifier:** Random Forest
- Captures semantic meaning more effectively than traditional Word2Vec embeddings.
- Produces better sentiment classification performance by understanding sentence context.

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 📌 Key Learnings

- Sentence Transformers capture the contextual meaning of complete sentences.
- Transformer-based embeddings outperform traditional Word2Vec for sentiment analysis.
- Good text preprocessing improves classification performance.
- Semantic embeddings help machine learning models better understand text.

---

## 🚀 Conclusion

This project demonstrates how **Sentence Transformers** can be used to build an effective sentiment analysis system. By comparing **Word2Vec** and **Sentence Transformer** embeddings, it highlights the advantages of transformer-based models in capturing semantic meaning and improving text classification performance.
