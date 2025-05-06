# Telco Customer Churn Prediction

This project applies machine learning techniques to predict whether a customer will churn (leave the service) based on customer demographics and service usage data.

## 📊 Overview

The notebook explores the **Telco Customer Churn** dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and builds predictive models to predict if a customer is likely to churn or not.

Key steps:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering
- Model training with Logistic Regression and Random Forest (including hyperparameter tuning)
- Model evaluation using F1-score

## 📁 Files

- `Customer Churn Prediction.ipynb`: Jupyter Notebook with code and analysis
- `telco-customer-churn.csv`: Dataset downloaded from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 🛠️ Libraries & Tools

- Python 3
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 📈 Results

- Top features influencing churn: Contract type, tenure, MonthlyCharges
- Best-performing model: Random Forest with f1-score of 0.736, improvement over baseline Logistic Regression model with f1-score of 0.718


## 🔗 Dataset Source

Kaggle: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
