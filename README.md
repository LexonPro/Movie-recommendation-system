# 🎬 Movie Recommendation System

A Machine Learning project that recommends movies based on content similarity using NLP and cosine similarity.

---

## 📌 Project Overview

This project analyzes movie metadata and recommends similar movies based on genres, cast, keywords, and overview.

The system uses Natural Language Processing techniques and cosine similarity to find related movies.

---

## 🚀 Technologies Used

- Python
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)
- CountVectorizer
- Cosine Similarity
- Jupyter Notebook

---

## 📂 Dataset

Dataset used: **TMDB 5000 Movie Dataset**

Files:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

---

## ⚙️ How the System Works

1. Load movie datasets  
2. Clean and preprocess text data  
3. Combine important features into tags  
4. Convert text to vectors using **CountVectorizer**  
5. Calculate similarity using **Cosine Similarity**  
6. Recommend top 5 similar movies  

---

## 🧠 Example

```python
recommend("Avatar")
