# CODSOFT-INTERNSHIP-TASK-2---Movie-Rating-Prediction
🎬 A machine learning project to predict IMDb movie ratings using features like genre, director, and lead actor. Built with Python in Jupyter Notebook as part of the CodSoft Internship Task 2. Explore data preprocessing, feature engineering &amp; regression modeling from scratch!

<p align="center">
  <img src="https://img.icons8.com/external-flatart-icons-flat-flatarticons/64/000000/external-movie-review-cinema-flatart-icons-flat-flatarticons.png" alt="Movie Icon" width="80"/>
</p>

<h1 align="center">🎬 Movie Rating Prediction using Python</h1>
<h3 align="center">CodSoft Internship Task 2</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter" />
  <img src="https://img.shields.io/badge/Internship-CodSoft%20%7C%20ShadowFox-red?style=flat-square" />
</p>

---

## 📚 Table of Contents
- [📌 Project Overview](#-project-overview)
- [📁 Dataset Details](#-dataset-details)
- [🧪 Technologies Used](#-technologies-used)
- [🔧 How It Works](#-how-it-works)
- [📈 Sample Results](#-sample-results)
- [📊 Sample Visualization](#-sample-visualization)
- [🧠 Skills Learned](#-skills-learned)
- [🚀 How to Run](#-how-to-run)
- [👨‍💻 Author](#-author)
- [🤝 Acknowledgements](#-acknowledgements)
- [⭐ Final Note](#-final-note)

---

## 📌 Project Overview

This project is part of the **CodSoft Data Science Internship** and focuses on building a machine learning model that predicts IMDb movie ratings based on attributes like **genre**, **director**, and **lead actor**.

The goal is to develop a predictive regression model using real-world movie data in Python via Jupyter Notebook.

---

## 📁 Dataset Details

- 📄 File: `IMDb Movies India.csv`
- 🎥 Features:  
  - Name  
  - Genre  
  - Director  
  - Actor 1, 2, 3  
  - Rating (Target)  
  - Year, Duration, Votes

- 🧼 Cleaning done:
  - Null value removal
  - Label Encoding of Categorical Data

---

## 🧪 Technologies Used

- **Python** 🐍  
- **Jupyter Notebook** 📓  
- **Pandas** – data manipulation  
- **NumPy** – numerical ops  
- **Matplotlib & Seaborn** – data visualization  
- **scikit-learn** – regression & preprocessing  

---

## 🔧 How It Works

1. Import & load the IMDb dataset  
2. Clean data (drop nulls, remove unused columns)  
3. Apply `LabelEncoder` to transform genres, actors, directors  
4. Use `train_test_split()` from `sklearn`  
5. Fit LinearRegression model  
6. Evaluate with R² Score  
7. Plot top 10 movies by rating

---

## 📈 Sample Results

- ✅ Trained on real Indian movie dataset  
- ✅ Model outputs a predicted rating  
- ✅ R² Score shows how well predictions match real IMDb ratings  
- ✅ Chart of top 10 highest-rated movies generated

---

## 📊 Sample Visualization

```python
# Bar plot of top 10 highest-rated movies
sns.barplot(x='Rating', y='Name', data=top_movies, palette='viridis')
plt.title("🏆 Top 10 Indian Movies by IMDb Rating")
plt.xlabel("Rating")
plt.ylabel("Movie Name")
plt.tight_layout()

Ritesh Paithankar
🎓 Data Science Intern at Shadow Fox (via CodSoft)
📍 India
📫 Email: ritesh@example.com (Replace with your real email)
🔗 LinkedIn Profile (Optional)
🗓️ Internship Task: CodSoft Internship Task 2
