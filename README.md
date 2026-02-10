### 📊 Customer Campaign Response Prediction using Machine Learning (iFood Dataset)
📌 Project Overview

This project applies machine learning to analyze customer behavior and predict marketing campaign responses using the iFood marketing dataset.
The goal is to help businesses optimize marketing strategies, improve customer targeting, and increase return on investment (ROI) through data-driven decision-making.

The project covers the full data science lifecycle: data exploration, feature engineering, model training, evaluation, and deployment readiness.

🎯 Business Objective

Marketing campaigns are costly when poorly targeted. This project aims to:

Predict which customers are most likely to respond to a campaign

Identify high-value customer segments

Reduce marketing waste by focusing on high-probability responders

Enable real-time predictions via API deployment (FastAPI-ready)

📂 Dataset Description

Source: iFood Marketing Dataset

Size: 2,205 customers

Features: 39 variables

Key Feature Categories:

Demographics: Income, Age, Education, Marital Status

Household Info: Kidhome, Teenhome

Customer Engagement: Recency, Customer_Days

Spending Behavior: Wine, Meat, Fish, Fruits, Regular Products

Campaign History: AcceptedCmp1–5, Response

🔍 Exploratory Data Analysis (EDA)

Key findings from the analysis include:

Average income: ~51,622

Average recency: ~49 days since last purchase

193 customers identified as at-risk (inactive for over 90 days)

Highest spending categories:

Regular Products

Wines

Meat Products

Campaign acceptance increases strongly with income

Very high-income customers accepted ~74% of campaigns

🧠 Feature Engineering

Created total spending metrics across product categories

Grouped customers into income segments

Encoded categorical variables using one-hot encoding

Scaled numerical features using StandardScaler

🤖 Model Development
Model Used: Logistic Regression

Logistic Regression was selected because it:

Is well-suited for binary classification

Provides interpretable results for business stakeholders

Performs efficiently on structured marketing data

Model Pipeline:

Data preprocessing (encoding & scaling)

Train-test split (80% train, 20% test)

Model training

Prediction & evaluation

📈 Model Performance

Accuracy: 88%

Strong performance on non-responders

Generated response probabilities for every customer to support ranking and targeting

💡 Business Recommendations

Based on insights and model outputs:

🎯 Focus premium campaigns on high-income, high-probability customers

🔁 Re-engage inactive customers using discounts or reminders

🛒 Prioritize promotions for top-performing product categories

⚙️ Use prediction probabilities to optimize campaign allocation

🚀 Deploy the model using FastAPI for real-time predictions

🛠️ Tech Stack

Programming: Python

Libraries: Pandas, NumPy, Scikit-learn, Joblib

Modeling: Logistic Regression

Deployment: FastAPI (API-ready artifacts)
