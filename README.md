# Medical Insurance Cost Prediction using Machine Learning

End-to-end machine learning project built using **Python and Scikit-learn** to predict medical insurance charges from demographic and lifestyle data.

This project demonstrates the complete machine learning workflow: **data cleaning → exploratory analysis → feature engineering → regression modeling → hyperparameter tuning → residual analysis → model persistence**.

---

## Project Overview

The project uses a **Medical Insurance** dataset to answer key predictive and analytical questions such as:

- How can medical insurance charges be predicted from customer information?
- Which factors contribute most to higher insurance costs?
- How do age and BMI influence medical expenses?
- What is the impact of smoking on insurance charges?
- Which regression model performs best on this dataset?

---

## Tech Stack

| **Category** | **Tools** |
|---|---|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Model Persistence | Joblib |
| Environment | Google Colab |

---

## Key Features

### Data Cleaning & Preparation

- Checked for missing values
- Identified duplicate records
- Converted categorical variables into numerical form
- Standardized numerical features using StandardScaler

### Exploratory Data Analysis

- Feature distribution analysis
- Box plots for outlier inspection
- Scatter plots for relationship analysis
- Correlation heatmap
- Business insight extraction

### Regression Modeling

- Linear Regression
- Ridge Regression
- Lasso Regression
- Hyperparameter tuning with GridSearchCV

### Model Evaluation

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score
- Residual analysis

### Model Persistence

- Saved the final trained model
- Saved the fitted scaler
- Verified model loading and prediction

---

## EDA Preview

### Distribution Analysis

- Age distribution
- BMI distribution
- Insurance charges distribution

### Relationship Analysis

- Age vs Charges
- BMI vs Charges
- Smoker vs Charges

### Correlation Heatmap

Feature correlation analysis to identify the most influential variables.

---

## Project Structure

```text
medical-insurance-cost-prediction/

├── data/                       # Dataset files
└── medicao-insurance-cost-prediction.ipynb
└── README.md
