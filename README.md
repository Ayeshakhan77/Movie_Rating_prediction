# Movie Rating Prediction

## Introduction

The **Movie Rating Prediction** project is a machine learning-based application developed to predict IMDb movie ratings using historical movie metadata. The main objective of this project is to analyze different movie-related features and estimate the expected rating of a film. This project demonstrates how predictive analytics can be applied in the entertainment industry using supervised machine learning techniques.

---

## Project Overview

This project uses movie information from the IMDb dataset to predict ratings by training regression models on historical data. The system compares multiple machine learning algorithms to determine which model performs better for rating prediction.

### Main Objectives

- Predict movie ratings accurately  
- Analyze important movie features  
- Compare machine learning models  
- Evaluate model performance  
- Visualize prediction results  

---

## Dataset Description

The dataset contains movie records collected from the IMDb movies dataset. Each row represents a single movie and its attributes.

### Dataset Features

| Column Name | Description |
|-------------|-------------|
| `Title` | Movie title |
| `Year` | Release year |
| `Genre` | Movie category |
| `Runtime` | Duration in minutes |
| `Votes` | Total user votes |
| `Director` | Movie director |
| `Metascore` | Critic score |
| `Rating` | IMDb rating (target variable) |

### Dataset Characteristics

- Structured tabular dataset  
- Mixed numerical and categorical features  
- Suitable for regression analysis  
- Real-world entertainment dataset  

---

## Methodology

The project follows a complete machine learning pipeline.

### 1. Data Collection

The IMDb dataset is imported into a Pandas DataFrame for processing.

### 2. Data Preprocessing

The preprocessing steps include:

- Handling missing values  
- Removing invalid records  
- Encoding categorical features  
- Selecting relevant variables  
- Splitting training and testing data  

### 3. Exploratory Data Analysis

Data analysis is performed to understand:

- Rating distribution  
- Feature relationships  
- Correlation between variables  
- Important predictive factors  

### 4. Model Training

The following models are used:

- `Linear Regression`
- `Random Forest Regressor`

### 5. Model Evaluation

The models are evaluated using:

- Mean Squared Error (`MSE`)
- Root Mean Squared Error (`RMSE`)
- R² Score  

---

## Results

The models successfully predicted movie ratings based on historical movie features. The comparison showed that the linear model performed slightly better than the ensemble model for this dataset.

### Predicted vs Actual Ratings

![Movie Rating Prediction Result](images/movie_rating_prediction.png)

### Performance Summary

| Model | MSE | RMSE | R² Score |
|-------|-----|------|---------|
| `Linear Regression` | `0.449` | `0.670` | `0.531` |
| `Random Forest` | `0.451` | `0.671` | `0.530` |

### Key Findings

- Votes strongly influence rating prediction  
- Feature engineering improved performance  
- Linear relationships exist in the dataset  
- Machine learning can estimate movie ratings effectively  

---

## Conclusion

This project demonstrates how machine learning can be used to predict movie ratings from historical IMDb data. By analyzing movie metadata and comparing different regression models, the project highlights the practical use of predictive analytics in entertainment data. It also provides a strong foundation for more advanced recommendation and rating systems.

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/Ayeshakhan77/Movie_Rating_prediction.git
```

### Navigate to the Project Folder

```bash
cd Movie_Rating_prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open the Project File

```bash
Movie_prediction.ipynb
```

---

## Technologies Used

- `Python`
- `Pandas`
- `NumPy`
- `Matplotlib`
- `Scikit-learn`
- `Jupyter Notebook`

---

## Future Improvements

Possible future improvements include:

- Adding advanced regression models  
- Improving feature engineering  
- Using deep learning methods  
- Deploying a web-based prediction app  

---
