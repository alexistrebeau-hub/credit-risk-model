# Credit Risk Modeling Project

## Overview
This project builds a machine learning model to predict loan default risk using borrower financial and demographic data.

The objective is to simulate how financial institutions evaluate lending risk and identify key drivers of default.

---

## Dataset
German Credit Dataset (UCI / Kaggle)

- 1,000 borrowers
- Financial & demographic variables
- Binary default outcome (Good / Bad credit)

---

## Methodology
- Data cleaning and preprocessing
- One-hot encoding of categorical variables
- Feature scaling
- Logistic Regression modeling
- ROC Curve evaluation
- Threshold optimization using Youden's J statistic
- Odds ratio interpretation

---

## Model Performance
- ROC-AUC: **0.63**
- Optimized classification threshold improved detection of risky borrowers while maintaining approval balance.

---

## Key Risk Drivers

### Default Risk Increasing Factors
- Education loans (+85% default odds)
- Low savings balances (+60%)
- Longer loan duration (+59%)
- Rental housing status (+25%)

### Risk Reducing Factors
- Rich savings balances (-47%)
- Home ownership (-27%)
- Consumer purchase loans (-36%)

---

## Visualizations

### ROC Curve
![ROC Curve](images/roc_curve.png)

### Risk Drivers
![Risk Drivers](images/risk_drivers_odds.png)

---

## Tools Used
Python • Pandas • Scikit-Learn • Matplotlib • VS Code

---

## Author
Alexis Trebeau  
UNC Chapel Hill — Statistics & Data Science

