# Bank Customer Churn Prediction

This project predicts customer churn using machine learning and visualizes insights via a Power BI dashboard.

## Dataset
- Source: [https://www.kaggle.com/datasets/shubhammeshram579/bank-customer-churn-prediction]
- Total Customers: 10,000
- Features: Age, Balance, Tenure, Credit Score, Gender, etc.

## Exploratory Data Analysis
- Checked churn distribution by age, tenure, credit score
- Identified key patterns using Power BI

## Models Trained
| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 82.9%    | 59.9%     | 21.2%  | 31.4%    |
| Decision Tree      | 80.1%    | 48.6%     | 53.3%  | 51.0%    |
| Random Forest      | **87.0%**| **77.4%** | 46.1%  | **57.8%**|

**Random Forest performed the best overall.**

## Power BI Dashboard
- Included metrics: Churn Rate, Avg. Balance, Avg. Tenure
- Visuals: Churn by Age, Tenure, Credit Score Group, Gender



