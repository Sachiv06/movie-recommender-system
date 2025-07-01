# 🎬 Movie Recommender System

This is a collaborative filtering-based **Movie Recommender System** built using the [MovieLens dataset](https://grouplens.org/datasets/movielens/). It predicts and recommends movies to users based on their past ratings and the preferences of similar users.

---

## 📌 Features

- ✅ Built using user-based collaborative filtering
- ✅ Calculates user similarity using cosine similarity
- ✅ Recommends top-rated movies that similar users have liked
- ✅ Clean and modular code in Jupyter Notebook
- ✅ Easy to extend with Streamlit for a simple UI (future plan)

---

## 🧠 How It Works

This recommender system uses the concept of **collaborative filtering**. It assumes:
> *"Users who agreed in the past will agree in the future."*

### Steps:
1. Load movie and rating data
2. Merge them into a user-movie matrix
3. Calculate similarity between users using cosine similarity
4. Recommend movies liked by similar users that the current user hasn’t watched yet

---

## 📂 Project Structure

movie-recommender-system/
├── dataset/
│ ├── movies.csv
│ └── ratings.csv
├── recommender.ipynb # Main notebook
├── requirements.txt # List of Python packages
└── README.md # Project documentation

