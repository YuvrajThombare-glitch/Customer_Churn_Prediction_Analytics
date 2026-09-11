# Customer Churn Prediction & Analytics

## Project Overview

This project focuses on predicting customer churn using Machine Learning classification algorithms.

The project uses customer data containing 7,043 records and 21 features. The target variable is `Churn`, which indicates whether a customer is likely to leave the service.

## Objectives

- Analyze customer churn patterns
- Perform data cleaning and exploratory data analysis
- Prepare data for Machine Learning
- Train classification models
- Compare model performance
- Select the best-performing model

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

### 1. Logistic Regression

- Accuracy: 82.19%
- ROC-AUC: 0.8625

### 2. Random Forest

- Accuracy: 78.50%
- ROC-AUC: 0.8368

## Model Comparison

| Model | Accuracy | ROC-AUC |
|---|---:|---:|
| Logistic Regression | 82.19% | 0.8625 |
| Random Forest | 78.50% | 0.8368 |

## Final Model

Based on the evaluation results, **Logistic Regression** performed better than Random Forest.

Therefore, Logistic Regression was selected as the final model for customer churn prediction.

## Conclusion

This project demonstrates how Machine Learning can be used to predict customer churn and help businesses identify customers who may be likely to leave.

The insights from this analysis can support customer retention strategies.

## Project File

`Customer_Churn_Prediction_Analytics.ipynb`
