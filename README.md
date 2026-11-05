Customer Transaction Prediction Using Machine Learning

1. Project Overview

This project aims to predict whether a customer is likely to perform a transaction, irrespective of the transaction amount.

The objective is to identify potential transacting customers using machine learning classification algorithms.

2. Dataset

Approximately 200,000 records

Approximately 200 features

Binary classification problem

3. Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

SHAP

4. Project Workflow

Data loading and understanding

Exploratory Data Analysis (EDA)

Missing value and data quality checks

Outlier detection and analysis

Correlation analysis

Data preprocessing

Model building

Hyperparameter tuning

Model evaluation

Feature importance and SHAP analysis

5. Machine Learning Algorithms

Logistic Regression

Random Forest

Gradient Boosting

XGBoost

6. Model Evaluation

Models were evaluated using:

Accuracy

Confusion Matrix

ROC Curve

ROC-AUC Score

Feature Importance

Final Model Results

Metric

Tuned XGBoost

Accuracy

91.78%

ROC-AUC

0.8827

XGBoost achieved the best ROC-AUC score among the evaluated models and was selected as the final model.

7. Key Learnings

Handling high-dimensional datasets

Exploratory data analysis

Classification model development

Hyperparameter optimization using GridSearchCV and RandomizedSearchCV

Model comparison and evaluation

Model interpretability using SHAP

8. Project Files

PRCP-1003_Customer_Transaction_Prediction (1) (1).ipynb – Jupyter Notebook containing the complete project workflow.

9. Conclusion

This project demonstrates the application of machine learning techniques to identify customers with a likelihood of performing transactions. XGBoost provided the best overall ROC-AUC performance among the evaluated models.
