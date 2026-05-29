# Task---3-InternSpark-Internship
# Customer Churn Prediction – Fairness, Bias and Explainability Analysis

## Project Overview

This project analyzes fairness, bias, and explainability of a Customer Churn Prediction Machine Learning model using SHAP and feature importance techniques.

The goal is to understand how the model makes predictions and identify any possible bias across sensitive customer groups.

---

## Technologies Used

* Python
* Scikit-learn
* SHAP
* Matplotlib
* Seaborn
* Pandas

---

## Objectives

* Compute feature importance
* Explain predictions using SHAP
* Analyze bias across sensitive groups
* Propose mitigation strategies

---

## Explainability Techniques Used

### Feature Importance

Feature importance scores were calculated to identify the most influential variables affecting customer churn.

Important Features:

* Contract Type
* Monthly Charges
* Tenure

---

### SHAP Analysis

SHAP (SHapley Additive exPlanations) was used to:

* Explain individual predictions
* Understand feature impact
* Visualize model behavior

Plots Included:

* SHAP Summary Plot
* SHAP Force Plot
* Feature Importance Plot

---

## Bias and Fairness Analysis

Sensitive attributes analyzed:

* Gender
* Senior Citizen

The model performance was compared across these groups to check whether predictions were unfairly biased.

---

## Mitigation Recommendations

* Balance dataset across demographic groups
* Remove highly biased features if necessary
* Use fairness-aware algorithms
* Monitor model predictions regularly

---

## Results

The Random Forest model achieved strong predictive performance while maintaining acceptable fairness across customer groups.

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

---

## Conclusion

This project demonstrates the importance of model explainability and fairness in Machine Learning systems. SHAP analysis helped interpret model decisions and identify opportunities for reducing bias.
