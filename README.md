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

## 👨‍💻 Author

<p align="left">
  <img src="https://img.shields.io/badge/Author-Ritesh%20Paithankar-blueviolet?style=for-the-badge&logo=github" />
</p>

**Ritesh Paithankar**  
🎓 Data Science Intern at **Shadow Fox** (via **CodSoft**)  
📍 India  
📫 Email: riteshpaithankar00@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/ritesh-paithankar-4b43a828a)  
🗓️ Task: **CodSoft Internship Task 2**

---

## 🤝 Acknowledgements

🙏 Huge thanks to **CodSoft** for this opportunity  
🎯 Special mention to **Shadow Fox** for mentoring support  
❤️ Gratitude to the open-source Python and data science community  

---

## ⭐ Final Note

This project reflects my beginner-to-intermediate journey into **data science and machine learning** using Python.

If you find this helpful or inspiring, feel free to ⭐ star the repo and connect with me on [LinkedIn](https://www.linkedin.com/in/ritesh-paithankar-4b43a828a)!


## 📊 Sample Visualization

<img width="1260" height="743" alt="Screenshot 2025-07-19 184611" src="https://github.com/user-attachments/assets/40975e4f-1d3b-418b-b6b1-7fd56d6387cd" />
<img width="883" height="692" alt="Screenshot 2025-07-19 184512" src="https://github.com/user-attachments/assets/fff18742-9237-4124-8c06-11e5cdf42173" />
<img width="288" height="315" alt="Screenshot 2025-07-19 184440" src="https://github.com/user-attachments/assets/699d826f-ca72-4fd7-9593-ecec0a623367" />
<img width="637" height="241" alt="Screenshot 2025-07-19 184431" src="https://github.com/user-attachments/assets/b8af8dc7-9adc-48cb-ba46-8ab0a0a6b2c1" />
<img width="246" height="233" alt="Screenshot 2025-07-19 184311" src="https://github.com/user-attachments/assets/313041eb-7070-4848-b54d-e5b7fa2a78c0" />
<img width="528" height="365" alt="Screenshot 2025-07-19 184303" src="https://github.com/user-attachments/assets/ec94cc0b-173a-47fd-b5d4-34505302b9b7" />
<img width="1338" height="218" alt="Screenshot 2025-07-19 184248" src="https://github.com/user-attachments/assets/d24ca531-c4f0-41f3-bbc8-3cb897bd762a" />
<img width="932" height="204" alt="Screenshot 2025-07-19 184239" src="https://github.com/user-attachments/assets/0b71280d-fc0f-42ae-a9ab-e68fa3a20fa1" />

```python
# Bar plot of top 10 highest-rated movies
sns.barplot(x='Rating', y='Name', data=top_movies, palette='viridis')
plt.title("🏆 Top 10 Indian Movies by IMDb Rating")
plt.xlabel("Rating")
plt.ylabel("Movie Name")
plt.tight_layout()
plt.show()
