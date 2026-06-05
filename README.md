# House Price Prediction Using Linear Regression

## Project Overview

This project predicts residential property prices using Linear Regression and follows a complete Data Science workflow including data cleaning, exploratory data analysis, feature selection, model development, and performance evaluation.

The objective is to identify key factors influencing housing prices and build a predictive model capable of estimating property values accurately.

---

## Dataset

Source: Kaggle House Prices Dataset

- Records: 1460
- Features: 81
- Target Variable: SalePrice

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

### Data Cleaning

- Missing value analysis
- Removal of highly incomplete features
- Missing value imputation

### Exploratory Data Analysis

- House price distribution analysis
- Correlation analysis
- Scatter plots
- Heatmap visualization

### Feature Selection

Selected Features:

- OverallQual
- GrLivArea
- GarageCars
- GarageArea
- TotalBsmtSF
- YearBuilt

### Model Development

A Linear Regression model was trained using selected housing characteristics.

### Model Evaluation

| Metric | Value |
|----------|----------|
| MAE | 25,171 |
| RMSE | 39,693 |
| R² Score | 0.795 |

---

## Key Findings

- Overall quality is the strongest predictor of house prices.
- Larger living areas generally increase property values.
- Garage capacity and basement area positively influence housing prices.
- Newer properties tend to command higher market values.

---

## Future Improvements

- Random Forest Regression
- XGBoost Regression
- Hyperparameter Tuning
- Feature Engineering
- Streamlit Deployment

---

## Author

Prathamesh

B.Sc. Data Science Student
