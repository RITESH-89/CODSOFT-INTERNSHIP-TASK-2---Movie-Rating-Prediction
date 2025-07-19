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

## 📌 Project Overview

This project is part of the **CodSoft Data Science Internship** and focuses on building a machine learning model that predicts IMDb movie ratings based on attributes like **genre**, **director**, and **lead actors**.

The aim is to explore real-world datasets and apply Python-based data science techniques to develop a regression model and present meaningful visualizations.

---

## 📁 Dataset Details

- **Filename**: `IMDb Movies India.csv`
- **Columns**:
  - 🎬 Name
  - 🎞️ Genre
  - 🎥 Director
  - 🧑‍🎤 Actor 1, 2, 3
  - ⭐ Rating (Target)
  - 📅 Year
  - 🕒 Duration
  - 🗳️ Votes

- **Cleaning Done**:
  - Removed null values  
  - Label encoded categorical features  
  - Removed unnecessary or duplicate data

---

## 🧪 Technologies Used

- 🐍 Python  
- 📓 Jupyter Notebook  
- 📊 Pandas, NumPy – data manipulation  
- 🎨 Matplotlib, Seaborn – visualizations  
- 🧠 scikit-learn – ML modeling  

---

## 🔧 How It Works

1. Load and explore dataset  
2. Clean data and encode text features  
3. Split data into training and test sets  
4. Apply **Linear Regression**  
5. Evaluate model using R² Score  
6. Visualize top 10 movies by rating

---

## 📈 Sample Results

- ✅ Model trained using IMDb movie dataset  
- ✅ Predicts ratings based on cast, director, genre  
- ✅ Evaluation metric: **R² Score**  
- ✅ Outputs a clean bar chart of top-rated movies  

---

## 📊 Sample Visualization

```python
# Bar plot of top 10 highest-rated movies
sns.barplot(x='Rating', y='Name', data=top_movies, palette='viridis')
plt.title("🏆 Top 10 Indian Movies by IMDb Rating")
plt.xlabel("Rating")
plt.ylabel("Movie Name")
plt.tight_layout()
