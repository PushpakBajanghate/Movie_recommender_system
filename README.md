# Movie_recommender_system

# 🎬 Movie Recommender System

An AI/ML-based Movie Recommendation System that suggests similar movies based on user input using content-based filtering and cosine similarity.
This project demonstrates practical machine learning, feature engineering, and deployment using Streamlit.

---

## 🚀 Project Overview

This project recommends **5 similar movies** when a user selects a movie from the list.

The recommendation engine analyzes movie metadata such as:

* Genres
* Keywords
* Cast
* Crew
* Movie overview

and calculates similarity between movies using NLP techniques.

---

## 🧠 How It Works

### 1️⃣ Data Processing

* Cleaned movie datasets
* Combined multiple features into a single **tags** column
* Applied text preprocessing

### 2️⃣ Feature Engineering

* Converted text data into vectors using:

  * CountVectorizer / TF-IDF (depending on version)
* Generated feature vectors for each movie

### 3️⃣ Similarity Calculation

* Used **Cosine Similarity** to measure movie closeness
* Stored similarity matrix using Pickle for fast loading

### 4️⃣ Recommendation Engine

* User selects a movie
* System finds most similar movies
* Returns top 5 recommendations

---

## 🖥️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit (UI)
* Pickle (model storage)

---

## 📁 Project Structure

```
movie-recommender-system/
│
├── app.py                # Streamlit UI
├── recommender.py        # Recommendation logic
│
├── model/
│   ├── movies.pkl
│   └── similarity.pkl
│
├── notebooks/
│   └── movie_recommender.ipynb
│
└── README.md
```

---

## ▶️ How to Run the Project

### 1. Clone Repository

```bash
git clone <your-repo-link>
cd movie-recommender-system
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Streamlit App

```bash
streamlit run app.py
```

---

## 🎯 Features

✔ Movie recommendation based on similarity
✔ Fast response using precomputed similarity matrix
✔ Interactive Streamlit UI
✔ Clean project structure (industry-style)

---

## 🔥 Future Improvements

* Movie posters integration (TMDB API)
* Clickable movie links
* Hybrid recommendation system
* User-based personalization
* GenAI-based explanation (“Why this movie?”)

---

## 📌 Learning Outcomes

* NLP feature engineering
* Recommendation systems basics
* Cosine similarity implementation
* Model serialization using Pickle
* Building ML apps with Streamlit

---

## 👨‍💻 Author

**Pushpak Bajanghate**
Data Science Student | Machine Learning Enthusiast
