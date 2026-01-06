# FUTURE_ML_02
Internship Task 2

#Customer Churn Prediction using Machine Learning & Power BI

**📌 Project Overview**
This project focuses on predicting customer churn for Spotify using machine learning models and visualizing insights through an interactive Power BI dashboard.

The goal is to identify customers who are likely to exit and provide actionable insights to support retention strategies.

This project was completed as part of my Machine Learning Internship Task.

**🎯 Objectives**

Perform exploratory data analysis (EDA) on customer data
Build and evaluate churn prediction models
Generate churn probabilities for each customer
Visualize churn patterns and model outputs in Power BI
Deliver business-ready insights through dashboards

**📂 Dataset**

Source: Bank Customer Churn Dataset
File: Churn_Modelling.csv
Target Variable: Exited
1 → Customer exited (churned)
0 → Customer retained

**🛠️ Tools & Technologies**

Python
Pandas, NumPy
Scikit-learn
XGBoost
Matplotlib / Seaborn
Power BI

**🤖 Machine Learning Models Used**

Logistic Regression (baseline)
XGBoost Classifier (final model)

**Why XGBoost?**

Handles non-linear relationships well
Provides churn probabilities
Strong performance on tabular data

**📊 Model Evaluation Metrics**

Accuracy
Precision
Recall
F1-Score
ROC-AUC
Special focus was given to Recall, as missing churned customers is costly in business scenarios.

**📈 Power BI Dashboard Highlights**

The dashboard includes:

-> Overall churn KPIs
-> Churn distribution across customer segments
-> age, willing for premium and analysis
-> Model performance metrics
-> Churn probability distribution
-> High-risk customer identification

**📁 Project Structure**

Customer-Churn-Prediction/
│
├── data/
│   ├── raw/
│   │   └── Churn_Modelling.csv
│   │
│   └── processed/
│       └── Chrun_Pred.csv
│
├── notebooks/
│   └── Customer_churn_prediction.ipynb
│
├── powerbi/
│   └── ML_INTERN_TASK_2.pbix
│
├── README.md
└── requirements.txt

**🚀 How to Run the Project**

1.Clone the repository
2.Install dependencies:
pip install -r requirements.txt
3.Open and run:
Customer_churn_prediction.ipynb
4.Load the generated predictions file into Power BI.

**📌 Business Insights & Recommendations**

Customers who are willing to pay a premium subscription are likely to be retained
Proactive retention strategies should focus on high-risk customer segments identified by the model

**✅ Conclusion**
This dashboard integrates machine learning predictions with business intelligence tools to deliver actionable insights, enabling data-driven customer retention strategies.

**👤 Author**

Uttkarsh Bhardwaj
Machine Learning Intern
