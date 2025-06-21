# 📚 Book Recommendation System using Machine Learning

A collaborative filtering–based recommender that suggests similar books when given a title. Built using a real-world dataset and deployed with Streamlit for an instant web interface.

---

## ✅ Features

- 🔎 Enter a book title → get 5–10 personalized recommendations  
- 📈 Uses collaborative filtering (KNN on user-item rating matrix)  
- 🏗️ Built from scratch with these components:
  - `book_names.pkl` (metadata)
  - `final_rating.pkl` (processed user-item matrix)
  - `model.pkl` (trained KNN model)
- 🧰 Streamlit web app for real-time interaction

---

## 🧠 Dataset

- Sourced from [Kaggle – Book Recommendation Data](https://www.kaggle.com/datasets/ra4u12/bookrecommendation)  
- Includes `Books.csv`, `Ratings.csv`, and `Users.csv`
- Preprocessing steps convert raw data into `.pkl` files for faster loading

---

## 🔧 Tech Stack

- Python, Pandas, NumPy
- Scikit-learn (KNN algorithm)
- Streamlit for UI
- Pickle for model/data persistence
- Git & GitHub for version control

---

