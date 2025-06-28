# 🎬 NextFlick – Movie Recommendation System

**NextFlick** is a personalized movie recommendation system that uses real-world data and three powerful machine learning techniques:

- **Collaborative Filtering**
- **Content-Based Filtering**
- **Hybrid Model** (combination of both)

It suggests top movie picks to a user based on their preferences and the content of movies.

---

## 📁 Dataset

This project uses the [Movies Dataset from Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset), which includes:

- `ratings.csv` — User-movie ratings  
- `movies_metadata.csv` — Movie information and overviews  
- `links.csv` — Mapping between MovieLens IDs and TMDB IDs  

---

## 🧠 Recommendation Techniques

### 1. Collaborative Filtering (SVD)
- Predicts ratings based on similar user behavior.
- Implemented using the **Surprise** library.

### 2. Content-Based Filtering
- Recommends movies based on plot similarity using **TF-IDF** and **cosine similarity**.

### 3. Hybrid Model
- Combines both collaborative and content-based scores for improved accuracy.

---

## ⚙️ Libraries Used

- `pandas`, `matplotlib`, `seaborn`  
- `scikit-learn`, `surprise`  
- `TfidfVectorizer`, `SVD`, `linear_kernel`

---

## ✅ How It Works

- Load and clean the data  
- Train the collaborative model on user ratings  
- Vectorize movie overviews using TF-IDF  
- Generate similarity scores and recommendations  
- Combine both approaches for hybrid recommendations

---

## 📌 Output

The system generates:
- **Top 10 recommendations** for a sample user
- **Bar plots** visualizing predicted ratings and hybrid scores

---
