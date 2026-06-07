Customer Churn Retention Prediction
Project Overview
Customer churn is one of the biggest challenges faced by telecom companies. This project predicts whether a customer is likely to leave the company and provides personalized retention recommendations to reduce customer churn.
The project uses Machine Learning techniques to analyze customer behavior, identify churn risks, and suggest actions that can help retain valuable customers.
Business Problem
Customer acquisition is significantly more expensive than customer retention.
The goal of this project is to:
Predict customer churn
Identify high-risk customers
Generate retention recommendations
Help business teams improve customer loyalty
Support decision-making through Power BI dashboards
Dataset
Dataset: Telecom Customer Churn Dataset
Features Included
Customer Demographics
Age
Gender
Marital Status
Number of Dependents
Number of Referrals
Contract Type
Internet Service
Monthly Charges
Total Charges
Revenue
Tech Support
Streaming Services
Customer Status
Churn Category
Churn Reason
Technologies Used
Programming Language
Python
Libraries
Python
pandas
numpy
matplotlib
seaborn
scikit-learn
Visualization
Power BI
Version Control
Git
GitHub
Project Workflow
1. Data Collection
Loaded Telecom Customer Churn dataset using Pandas.
2. Data Cleaning
Performed:
Missing value handling
Duplicate checking
Data type correction
Null value treatment
3. Exploratory Data Analysis (EDA)
Analyzed:
Customer churn distribution
Contract impact on churn
Internet service influence
Revenue patterns
Customer behavior
4. Feature Engineering
Created model-ready dataset by:
Handling categorical variables
One-Hot Encoding
Feature selection
5. Model Building
Used:
Python
Random Forest Classifier
Train-Test Split
Python
80% Training Data
20% Testing Data
Model Performance
Accuracy
Plain text
82.47%
Classification Report
Metric
Churn Class
Precision
0.67
Recall
0.64
F1 Score
0.66
Confusion Matrix
Plain text
[[946  89]
 [158 216]]
Feature Importance
Top factors affecting churn:
Tenure in Months
Number of Referrals
Total Revenue
Total Charges
Contract Type
Monthly Charges
Internet Type
Age
Number of Dependents
Premium Tech Support
Retention Recommendation Engine
The system generates business recommendations based on churn probability.
Rules
Churn Probability
Recommendation
> 80%
Offer 20% Discount
> 60%
Provide Premium Tech Support
> 40%
Offer Loyalty Reward
≤ 40%
No Action Needed
Output Files
1. Customer Recommendations
Plain text
customer_retention_recommendations.csv
Contains:
Actual Churn
Predicted Churn
Churn Probability
Recommendation
2. Power BI Dataset
Plain text
powerbi_customer_retention.csv
Used for dashboard creation.
Power BI Dashboard Features
Executive Dashboard
KPIs:
Total Customers
Churn Customers
Churn Rate
Revenue Impact
Retention Rate
Visualizations
Monthly Churn Analysis
Contract Type vs Churn
Revenue Loss Analysis
Customer Segment Analysis
Recommendation Distribution
Geographic Customer Distribution
Business Impact
This solution helps organizations:
Identify high-risk customers
Reduce customer churn
Increase customer retention
Improve revenue stability
Optimize retention campaigns
Future Improvements
XGBoost Model
LightGBM Model
Customer Lifetime Value Prediction
Uplift Modeling
Real-Time Prediction API
Streamlit Dashboard
AI-Powered Retention Agent
Project Structure
Plain text
Customer-Churn-Retention-Prediction/
│
├── notebook/
│   └── Churn.ipynb
│
├── customer_retention_recommendations.csv
├── powerbi_customer_retention.csv
├── requirements.txt
├── README.md
│
└── data/
    └── telecom_customer_churn.csv
Author
Jitendra Kumar
MCA Student | Data Science & Machine Learning Enthusiast
GitHub: https://github.com/Jitendra18sh⁠�
LinkedIn: https://www.linkedin.com/in/jitendra-kumar-130b25347
License
This project is licensed under the MIT License.
