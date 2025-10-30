# 📝 Persian Product Review Recommendation Classifier (Hazm + Word2Vec)

This project builds a **Persian product review classifier** using **Hazm** for text preprocessing, **Word2Vec** for word embeddings, and **Logistic Regression** for classification.  

The model predicts whether a customer review is:

- ✅ recommended  
- ❌ not recommended  
- 🤷 no idea  

---

### 📊 Dataset Labels

| Label | Meaning |
|-------|--------|
| 1 | recommended 👍 |
| 0 | not_recommended 👎 |
| 2 | no_idea 🤷 |

---

### 🧠 NLP Pipeline

1️⃣ Preprocess Persian text using **Hazm**:  
- Normalization  
- Tokenization  
- Stopword removal  
- Stemming  
- Removing digits & punctuation  

2️⃣ Train **Word2Vec** on preprocessed text  
3️⃣ Convert each sentence → average word vector  
4️⃣ Train **Logistic Regression**  
5️⃣ Predict review class with `predict_recommendation()`  

---

### 🛠️ Technologies Used

| Purpose | Library |
|--------|--------|
| Text Preprocessing | **Hazm** |
| Word Embeddings | **Word2Vec (Gensim)** |
| Classification | **scikit-learn (Logistic Regression)** |
| Data Handling | pandas, numpy |
| Language | Python 3.x |

---
