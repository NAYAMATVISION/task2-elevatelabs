# Titanic Dataset - Exploratory Data Analysis (EDA)

This project is part of my internship task, where I performed Exploratory Data Analysis (EDA) on the Titanic dataset to understand its structure, uncover patterns, and derive insights using statistics and visualizations.

---

## 📌 Objective
To explore the Titanic dataset using EDA techniques such as:
- Summary statistics
- Visualizations (histograms, boxplots, countplots, violin plots)
- Correlation analysis
- Feature-level inferences

---

## 🧰 Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📁 Dataset
The dataset used is the Titanic dataset from Kaggle:  
🔗 [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 📊 EDA Steps & Graphs

### 1. Summary Statistics
We calculated the mean, median, standard deviation, skewness, and kurtosis for features like Age and Fare to understand their distribution.

### 2. Histograms & Boxplots

#### 🔹 Age
- **Histogram** shows that most passengers are aged 20–40.
- **Boxplot** shows some outliers (passengers over 65).

#### 🔹 Fare
- **Histogram** is right-skewed — many passengers paid low fares, few paid very high.
- **Boxplot** reveals extreme outliers (fares > $100), especially in 1st class.

📷 *Screenshots attached below*
![image](https://github.com/user-attachments/assets/cb0e2cd6-1d2f-496c-9fb0-8eecf4984280)
![image](https://github.com/user-attachments/assets/2bbe3f08-5e66-4d0c-a2e1-a450a2258ea2)



### 3. Correlation Matrix
A heatmap was plotted to show relationships between numerical features.

- **Pclass and Fare** show a strong negative correlation.
- **Survived and Fare** show a moderate positive correlation.

📷 *Screenshot attached*
![image](https://github.com/user-attachments/assets/6ea80e33-ade6-4d28-a06f-e9d9ea062584)


### 4. Visual Pattern Analysis

#### 🔹 Survival vs Gender
- Countplot shows **most females survived**, **most males did not**.
- Conclusion: **Gender strongly influenced survival**.

#### 🔹 Survival vs Passenger Class
- 1st class passengers had the highest survival rate.
- 3rd class passengers had the lowest.

#### 🔹 Age Distribution by Survival (Violin Plot)
- Survivors included more **younger children and adults**.
- Distribution is similar, but survivors had more younger passengers.

📷 *Screenshots attached*
![image](https://github.com/user-attachments/assets/12c3b1c1-9c4f-489f-9a17-787f51a9bf39)
![image](https://github.com/user-attachments/assets/ef687acd-eb3e-4992-bef4-99a0a6a7c6fc)
![image](https://github.com/user-attachments/assets/51ea8d91-f749-4959-86d1-9d0cde04bb3d)

## 🔍 Key Inferences

- **Sex** and **Pclass** are strong predictors of survival.
- **Fare** also influences survival — higher fare, better chances.
- **Cabin** column has too many missing values.
- Some features (like PassengerId, Ticket) are not useful for analysis.

---

## 📤 Submission
All code and visualizations are included in this repo.  
This task was completed as part of the AI/ML Internship and submitted via the provided Google Form.

---

## ✅ Folder Contents
- `titanic_eda.ipynb` — Jupyter Notebook with full analysis
- `README.md` — Project documentation (this file)
