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

## Key Insights from Customer Churn Dashboard
1.	Mid-Age Customers Are Most Likely to Churn
The churn rate peaks around the age group of 40–50, indicating that customers in their mid-career stage are more likely to exit the service.
2.	Churn Rate is Higher in Early Tenure
Customers in their first 2–3 years are more likely to churn, suggesting the need for stronger onboarding and engagement strategies early in the customer journey.
3.	Credit Scores Between 600–700 Show Higher Churn
A noticeable churn spike is seen among customers with credit scores in the 600–700 range, indicating a potential risk group that could benefit from targeted financial support or loyalty programs.
4.	Female Customers Have a Slightly Higher Churn Rate
Although the gender difference isn't drastic, female customers show higher churn — which may warrant further investigation into user experience or service satisfaction by demographic





