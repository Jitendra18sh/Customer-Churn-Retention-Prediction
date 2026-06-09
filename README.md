Customer Churn Retention Prediction

Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. This project uses Machine Learning to predict customers who are likely to leave a telecom service and provides retention recommendations to reduce churn.

The project includes:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Customer Churn Prediction using Machine Learning
- Feature Importance Analysis
- Customer Retention Recommendations
- Power BI Dashboard for Business Insights

---

Business Problem

Customer acquisition is expensive compared to customer retention. Identifying customers who are likely to churn allows businesses to take proactive actions such as discounts, loyalty rewards, and premium support to improve retention.

---

Dataset Information

The dataset contains telecom customer information including:

- Demographics
- Contract Details
- Internet Services
- Billing Information
- Revenue Metrics
- Customer Status

Target Variable:

- Churn (0 = Stay, 1 = Leave)

---

Project Workflow

1. Data Preprocessing

- Handling missing values
- Encoding categorical variables
- Feature selection
- Data preparation for model training

2. Model Development

Machine Learning Algorithms:

- Random Forest Classifier

3. Model Evaluation

Metrics Used:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1 Score

Model Accuracy:

82.47%

4. Feature Importance Analysis

Top factors influencing churn:

1. Tenure in Months
2. Number of Referrals
3. Total Revenue
4. Total Charges
5. Contract Type
6. Monthly Charges
7. Long Distance Charges

5. Retention Recommendation Engine

Based on churn probability:

Churn Probability| Recommendation
> 80%| Offer 20% Discount
> 60%| Provide Premium Tech Support
> 40%| Offer Loyalty Reward
<= 40%| No Action Needed

---

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- Git & GitHub

---

Project Structure

Customer-Churn-Retention-Prediction/
│
├── data/
│   └── telecom_customer_churn.csv
│
├── notebook/
│   └── Churn.ipynb
│
├── customer_retention_recommendations.csv
├── powerbi_customer_retention.csv
├── requirements.txt
└── README.md

---

Business Impact

This solution helps organizations:

- Identify high-risk customers
- Reduce customer churn
- Increase customer retention
- Improve customer lifetime value
- Optimize retention campaigns

---

Future Improvements

- XGBoost and LightGBM implementation
- Hyperparameter tuning
- Real-time prediction API using FastAPI
- Automated retention campaign system
- Advanced Power BI dashboard

---

Author

Jitendra Kumar

MCA Student | Data Science & Machine Learning Enthusiast

GitHub: https://github.com/Jitendra18sh

LinkedIn:https://www.linkedin.com/in/jitendra-kumar-130b25347
