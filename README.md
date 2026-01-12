# 🏠 House Price Prediction (Regression)

This project predicts house sale prices using the [Kaggle dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
It demonstrates an end-to-end data science workflow including data cleaning,
exploratory data analysis, feature engineering, regression modeling, cross-
validation, and prediction on unseen test data.

## 📌 Objective
Build a regression model to predict `SalePrice` based on housing features such
as size, quality, and construction details.

## 📊 Dataset
- Source: Kaggle – House Prices: Advanced Regression Techniques
- Train data: Includes features + `SalePrice`
- Test data: Includes features only (used for final prediction)

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels

## 🤖 Models Used
- Ordinary Least Squares (OLS) Regression
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor

## 📐 Evaluation
- RMSE (primary metric)
- MAE

## 🏆 Final Model
**Lasso Regression**  
Chosen due to its best performance and built-in feature selection, achieving
the lowest RMSE among tested models.

## 📁 Output
- Predictions generated on unseen test data
- Submission-ready CSV with columns: `Id`, `SalePrice`

## ▶️ How to Run
1. Clone the repository  
2. Run notebook file in your editor
