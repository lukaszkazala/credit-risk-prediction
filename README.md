# Credit Risk Prediction

## Project Overview

This project aims to predict whether a customer will default on a loan using machine learning techniques.

The workflow includes:

* Data Cleaning
* Missing Value Treatment
* Outlier Detection
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Correlation Analysis
* Model Training
* Model Evaluation

---

## Dataset

The dataset contains information about customers, including:

* Age
* Income
* Employment Length
* Loan Amount
* Interest Rate
* Credit History Length

Target variable:

* `loan_status`

  * 0 = Repaid
  * 1 = Default

---

## Models Used

### Logistic Regression

* Accuracy: 83%
* ROC-AUC: 0.844

### Random Forest

* Accuracy: 88%
* ROC-AUC: 0.890

### XGBoost

* Accuracy: 87%
* ROC-AUC: 0.885

---

## Final Model

Random Forest was selected as the final model because it achieved the best performance on the independent test set.

Final Test Results:

* Accuracy: 88%
* Recall: 63%
* F1-score: 0.70
* ROC-AUC: 0.890

---

## Key Findings

Feature importance analysis showed that:

* Loan Interest Rate
* Loan Percent Income
* Customer Income

were the most important predictors of loan default.

---

## Technologies

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Matplotlib
* Seaborn

---

## Repository Structure

```text
credit-risk-prediction/
├── data/
├── images/
├── notebooks/
│   └── credit_risk_analysis.ipynb
├── README.md
└── .gitignore
```


