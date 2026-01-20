# Customer Churn Prediction (Machine Learning & Power BI)
**Internship Task 2 | ID: FUTURE_ML_02**

## 📌 Project Overview
This project focuses on predicting customer churn for **Spotify** using machine learning models and visualizing insights through an interactive Power BI dashboard.

The goal is to identify users who are likely to cancel their subscriptions and provide actionable insights to support retention strategies. This project was completed as a Machine Learning Internship Task.

## 🎯 Objectives
* **EDA:** Perform exploratory data analysis on customer data.
* **Modeling:** Build and evaluate churn prediction models.
* **Probabilities:** Generate churn probabilities for each user.
* **Visualization:** Visualize churn patterns and model outputs in Power BI. 
* **Insights:** Deliver business-ready insights through dashboards.

## 📂 Dataset
* **Context:** Spotify Customer Data
* **File:** `Churn_Modelling.csv`
* **Target Variable:** `Exited`
    * `1` → Customer exited (cancelled subscription)
    * `0` → Customer retained

## 🛠️ Tools & Technologies
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
* **Visualization:** Microsoft Power BI

## 🤖 Machine Learning Models
1.  **Logistic Regression** (Baseline Model)
2.  **XGBoost Classifier** (Final Model)

### Why XGBoost?
* Handles non-linear relationships efficiently.
* Provides accurate churn probabilities.
* Demonstrates strong performance on tabular user data.

## 📊 Model Evaluation
Key metrics used for evaluation:
* Accuracy
* Precision
* **Recall** (Primary Focus: Missing a churned user is costly in subscription business models)
* F1-Score
* ROC-AUC

## 📈 Power BI Dashboard Highlights
The dashboard provides a comprehensive view of customer retention:
* **Overall KPIs:** Total users, churn rate, and active subscribers.
* **Demographic Analysis:** Churn distribution by age and geography.
* **Subscription Analysis:** Insights on users willing to upgrade to Premium.
* **Risk Assessment:** Identification of high-risk user segments based on model probabilities.

## ✅Conclusion
This dashboard integrates machine learning predictions with buisness intelligence tools to deliver actionable insights , enabling data-driven customer retention strategies.

## Author
**Uttkarsh Bhardwaj**
