## 🎬 Movie Rating Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting IMDb movie ratings using machine learning techniques. The model is trained on movie metadata such as votes, runtime, genre, director, and metascore.

---

## 🎯 Objective
To develop a regression model that accurately predicts movie ratings based on historical IMDb dataset features.

---

## 📊 Dataset
The dataset contains the following features:

- Title  
- Year  
- Rating (Target Variable)  
- Votes  
- Runtime (Minutes)  
- Genre  
- Director  
- Metascore  

---

## 🧹 Data Preprocessing
- Handled missing values using mean/median imputation  
- Removed invalid entries  
- Encoded categorical variables (Genre, Director)  
- Selected relevant features for modeling  

---

## 📈 Exploratory Data Analysis (EDA)

Key visualizations performed:

- 📊 Rating distribution (Histogram)  
- 📈 Votes vs Rating (Scatter Plot)  
- 📊 Genre distribution (Bar Chart)  
- 🌡️ Correlation Heatmap  

---

## 🤖 Models Used

### 1. Linear Regression
- Baseline model  
- Captures linear relationships  

### 2. Random Forest Regressor
- Handles non-linear relationships  
- Ensemble learning method  

---

## 📊 Model Performance

| Model | MSE | RMSE | R² Score |
|------|-----|------|---------|
| Linear Regression | 0.449 | 0.670 | **0.531** |
| Random Forest | 0.451 | 0.671 | 0.530 |

---

## 🧠 Key Insights
- Feature engineering significantly improved performance  
- Linear Regression performed slightly better than Random Forest  
- Data shows a mostly linear relationship with ratings  


python main.py
