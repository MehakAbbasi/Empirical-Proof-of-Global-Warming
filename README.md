# 🌍 Empirical Proof of Global Warming

An end-to-end Data Science project investigating the relationship between global temperature change, greenhouse gas emissions, GDP, and population using historical data from **1961–2020**.

## 📌 Project Overview

This project combines climate, greenhouse gas, economic, and demographic datasets to investigate measurable patterns associated with global warming.

A complete Data Science pipeline was implemented:

**Data Collection → Data Cleaning → EDA → Statistical Analysis → Machine Learning → Model Evaluation → Prediction**

The final integrated dataset contains **2,001 observations**.

## 🔍 Key Questions

- Does CO₂ emissions correlate with temperature change?
- How are GDP and population related to emissions?
- Which regions and time periods show stronger warming patterns?
- Which ML model best predicts temperature change?

## 🤖 Machine Learning

Three regression models were compared:

- Linear Regression
- Bayesian Ridge Regression
- Random Forest Regressor

**Random Forest performed best**, achieving approximately:

- **R²: 0.45**
- **MSE: 0.229**

Hyperparameter tuning was also performed to find a suitable tree depth.

## 📊 Analysis

The project includes:

- Exploratory Data Analysis
- Correlation analysis
- Temperature trend analysis
- Regional & decade-wise warming analysis
- GDP and emissions analysis
- Model comparison
- Random Forest feature importance

### Feature Importance

The Random Forest model ranked:

1. GDP
2. Population
3. N₂O Emissions
4. CO₂ Emissions
5. CH₄ Emissions

## 🛠️ Technologies

**Python | Pandas | NumPy | Matplotlib | Scikit-learn | Machine Learning**

## 📁 Project Structure

```text
Empirical-Proof-of-Global-Warming/
│
├── data/
├── images/
├── report/
│   └── Final-Report.pdf
├── requirements.txt
└── README.md
