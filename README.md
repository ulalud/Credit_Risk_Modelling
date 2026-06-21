# Credit Risk Default Prediction

This project develops and compares several approaches for predicting loan default risk using borrower financial and credit history data.

## Models

* Logistic Regression
* Gradient Boosting Classifier
* XGBoost
* Hierarchical Bayesian Logistic Regression (PyMC)

## Key Tasks

* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Leakage Detection
* Model Calibration
* Model Comparison using ROC-AUC and PR-AUC

## Main Findings

* Potential leakage was identified in underwriting-related variables.
* Removing leakage-prone features reduced model performance but improved realism.
* Feature engineering significantly improved tree-based models.
* Logistic Regression remained a strong and interpretable baseline.
* Hierarchical Bayesian modelling captured differences in default risk across acquisition channels.

## Technologies

Python, Pandas, Scikit-Learn, XGBoost, PyMC, NumPy, Matplotlib

## Evaluation Metrics

* ROC-AUC
* Precision-Recall AUC
* Precision
* Recall
* F1 Score
