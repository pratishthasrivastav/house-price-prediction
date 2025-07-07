# 🏠 House Price Prediction using Regression

This project predicts residential house prices in King County, USA using multiple regression techniques including Linear Regression, Polynomial Regression, and Ridge Regression.

## 📊 Dataset

- Source: [Kaggle - House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)
- 21,613 entries and 21 features
- Target variable: `price`

## 🔍 Steps Covered

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Linear Regression
- Polynomial Regression (Degree 2)
- Ridge Regression (α = 0.1)
- Combined Polynomial + Ridge with Pipeline
- Model evaluation using R² Score

## 🧪 Model Comparison

| Model                          | R² Score (Test) |
|-------------------------------|------------------|
| Linear Regression              | ~0.49            |
| Multiple Linear Regression     | ~0.72            |
| Polynomial Regression (d=2)    | ~0.84            |
| Ridge Regression (α=0.1)       | ~0.75            |
| Poly + Ridge Regression (α=0.1)| ~0.83            |

## ✅ Final Model

- **Model**: Polynomial + Ridge Regression (α = 0.1)
- **R² Score**: ~0.83
- Trained using pipeline with polynomial transformation and regularization

## 📁 Files

- `house.ipynb`: Full notebook with code, EDA, and models

## 📣 Author

Pratishtha Srivastava


