# Phase3_Project
# Business Understanding 

## Problem Definition Context

Customer churn is a problem faced by SyriaTel, as retaining existing customers is far more cost-effective than acquiring new ones. By analyzing customer data, the company can identify usage patterns and service behaviors that predict which customers are likely to leave, enabling proactive retention efforts.

# Stakeholder

The main stakeholders are SyriaTel’s management, marketing, and customer service teams. Predictive insights will help these teams to anticipate churn, improve service quality, and target high-risk customers with personalized retention campaigns.

# Problem Statement

The goal is to develop a classification model that predicts whether a customer will churn based on factors such as service usage, plan type, and customer service interactions.
This model will:

1. Identify the most influential drivers of churn.
2. Predict high-risk customers early.
3. Support data-driven retention strategies.
   
# Scope and Evaluation
The analysis includes:
1. Exploratory Data Analysis (EDA).
2. Feature engineering and preprocessing.
3. Model training using classification algorithms.
4. Evaluation using accuracy, precision, recall, F1-score, and primarily ROC-AUC to measure model performance.

# Data Understanding and Analysis
Source of Data
The analysis used over 3,000 SyriaTel customer records, syriatel_churn.csv.

# Key Findings from Data
Customers who called customer service frequently were more likely to churn— often due to unresolved issues.

# Decision Tree Insights
The Decision Tree model visually mapped how SyriaTel customers
decide (or are predicted) to stay or leave.

# Model Performance -Decision Tree
Overall accuracy: 92% — the model correctly predicts
customer behavior 9 out of 10 times.
Churn recall: 64% — it successfully identifies 2 out of every 3
customers likely to leave.
This is a strong starting point for proactive customer retention

# Business Recommendations
1. Focus retention campaigns on customers with:
High daytime charges
Frequent customer service calls
International plans
No voicemail plans
2. Enhance customer service quality:
Customers who reach out multiple times are at high risk —
prioritize fast, effective issue resolution
3. Personalize offers:
Use model predictions to offer targeted discounts or loyalty
benefits before customers leave.
4. Continue improving the model:
Use more recent data
Add factors like payment delays or network issues
Explore advanced models like Random Forest or XGBoost for
higher recall

# Conclusion
The churn prediction model provides actionable insights to help
SyriaTel:
Reduce customer turnover
Save acquisition costs
Improve customer satisfaction
Enhance long-term profitability
With this tool, SyriaTel can predict who is at risk — and take action
before it’s too late.
