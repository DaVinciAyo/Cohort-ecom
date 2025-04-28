# Customer Churn Prediction

Customer churn prediction is the task of identifying customers who are likely to stop using a service or buying a product.
Understanding churn helps businesses act early to retain valuable customers.

In this project, we aim to:
Predict customer churn based on customer behavior data.
Build models that accurately classify customers as "Active" or "Churned."
Provide a simple, interactive tool where business teams can input customer data and get instant churn predictions.

# What We Intend to Achieve
Early Detection:
Identify at-risk customers before they leave.

Retention Strategy:
Allow businesses to target at-risk customers with personalized offers or support.

Business Insights:
Show which factors (like low purchase frequency or declining basket size) are strong indicators of churn.

Ease of Use:
Build a fast, no-code tool using Gradio that anyone in the company can use without technical skills.

Scalability:
Create a reusable pipeline where models can be retrained easily with new customer data.
This project builds a machine learning model to predict customer churn.
It uses a Random Forest Classifier and XGBoost Classifier for training, evaluation, and deployment.

# Features
Trained Random Forest and XGBoost models
Evaluation with confusion matrix and classification report
Automatic saving of evaluation results as images
Gradio web app for live churn prediction
Easy-to-use interface with real-time input fields

# Project Structure
models/ — Pretrained machine learning models
evaluations/ — Confusion matrices and classification reports
app.py — Gradio app for deployment
train.py — Model training and evaluation scripts

# Usage
Input values like Recency, Frequency, Monetary, CustomerLifetime, AvgBasketSize, and TotalTransactions.

Click submit to predict if a customer is likely to churn.

Get immediate feedback: "Active" or "Churned."

# Technologies
Python
Scikit-learn
XGBoost
Gradio
Seaborn
Matplotlib
NumPy
