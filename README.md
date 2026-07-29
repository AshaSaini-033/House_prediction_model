# 🏠 House Price Prediction using Machine Learning

## 📌 Overview

This project predicts California house prices using machine learning techniques. The complete ML workflow is implemented, including data preprocessing, exploratory data analysis (EDA), feature engineering, model comparison, hyperparameter tuning, and prediction generation.

The project follows an end-to-end machine learning pipeline similar to real-world Data Science projects.

---

## 🎯 Problem Statement

Develop a regression model capable of predicting the median house value based on demographic, geographical, and housing-related features.

---

## 📂 Dataset

Dataset: California Housing Dataset

Features include:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

Target Variable:

- Median House Value

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📊 Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Checked missing values
- Analyzed numerical features
- Analyzed categorical features
- Distribution analysis
- Correlation analysis
- Outlier detection
- Data visualization

---

### 2. Data Preprocessing

Implemented a preprocessing pipeline using **Scikit-Learn Pipeline** and **ColumnTransformer**.

Numerical Features:

- Median Imputation
- Standard Scaling

Categorical Features:

- Most Frequent Imputation
- One-Hot Encoding

---

### 3. Model Training

The following regression models were trained and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- Gradient Boosting Regressor

---

### 4. Model Evaluation

Performance was evaluated using:

- Cross Validation (K=5)
- Root Mean Squared Error (RMSE)
- R² Score

---

### 5. Hyperparameter Tuning

Used GridSearchCV to optimize the Gradient Boosting model.

Optimized parameters include:

- Learning Rate
- Number of Estimators
- Maximum Depth

---

### 6. Prediction System

Built a prediction pipeline capable of predicting house prices from new user inputs while automatically applying all preprocessing steps.

---

## 📈 Results

- Compared five regression algorithms.
- Improved prediction accuracy through hyperparameter tuning.
- Built a reusable preprocessing pipeline.
- Developed a complete end-to-end prediction workflow.

---

## 📁 Project Structure

```
House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── README.md
├── requirements.txt
├── model.pkl
├── pipeline.pkl
├── dataset.csv
└── images/
```

---

## 🚀 Future Improvements

- Feature Engineering
- XGBoost
- LightGBM
- Streamlit Deployment
- Flask API
- Docker Deployment

---

## 📚 Key Machine Learning Concepts

- Regression
- Data Cleaning
- Feature Engineering
- Pipelines
- ColumnTransformer
- Cross Validation
- Hyperparameter Tuning
- Model Selection
- RMSE
- R² Score

---

## 👨‍💻 Author

Asha Saini
