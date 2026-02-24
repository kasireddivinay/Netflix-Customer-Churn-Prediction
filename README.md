# 🎬 Netflix Customer Churn Prediction

## 📌 Project Overview

Customer churn is a critical challenge in subscription-based businesses like Netflix.  
This project develops a Machine Learning model to predict customers who are likely to cancel their subscription.

By identifying high-risk customers early, Netflix can take proactive retention measures and reduce revenue loss.

---

## 🧠 Business Objective

The goal of this project is to:

- Predict whether a customer will churn
- Identify key factors influencing churn
- Provide actionable business insights
- Improve customer retention strategy

---

## 📊 Dataset Description

The dataset includes:

- Customer Demographics
- Subscription Details
- Monthly Charges
- Tenure
- Payment Method
- Viewing Behavior
- Churn Status (Target Variable)

Target Variable:
- `1` → Customer churned
- `0` → Customer retained

---

## 🔄 Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering & Encoding
4. Train-Test Split (Stratified)
5. Model Training (Gradient Boosting Classifier)
6. Model Evaluation
7. Feature Importance Analysis
8. Model Saving

---

## 🤖 Model Used

### Gradient Boosting Classifier

Why this model?

- Handles non-linear relationships
- Performs well on structured data
- Reduces bias & variance
- High predictive performance

---

## 📈 Model Performance

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

### 🔥 ROC-AUC Score: 0.9979479261253406

The model demonstrates strong ability to distinguish between churned and non-churned customers.

---

## 🔍 Key Insights from Analysis

- Customers with low tenure are more likely to churn.
- Higher monthly charges increase churn probability.
- Contract type significantly impacts retention.
- Engagement patterns strongly influence churn behavior.

These insights help design targeted retention strategies.

---

## 💡 Business Recommendations

Based on model findings:

- Offer loyalty discounts to low-tenure customers.
- Provide incentives for long-term subscription plans.
- Identify high-risk churn segments for targeted campaigns.
- Improve engagement for inactive users.

---

## 🚀 How to Run the Project

Clone the repository:git clone https://github.com/kasireddivinay/Netflix-Customer-Churn-Prediction.git

cd Netflix-Customer-Churn-Prediction


Install dependencies:


Run Jupyter Notebook:

Open:notebooks/churn_prediction.ipynb



---

## 🔮 Future Improvements

- Hyperparameter tuning
- Model comparison (XGBoost, Random Forest)
- SHAP Explainability
- Deployment using FastAPI or Streamlit
- Real-time churn prediction API

---

## 👨‍💻 Author

Vinay Kasireddi  
AI & Machine Learning Enthusiast
