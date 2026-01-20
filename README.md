# FraudX: Financial Fraud Detection

Samsung Innovation Campus | Capstone Project

📌 Overview

FraudX is an advanced machine learning project designed to detect fraudulent credit card transactions.
By leveraging state-of-the-art algorithms, the project provides a smart and adaptive solution to identify suspicious activities, minimize financial losses, and enhance customer trust in financial institutions.

🎯 Project Objectives

Accurate Fraud Detection:
Build a predictive model capable of identifying suspicious transactions with high precision.

Cost Optimization:
Balance False Positives and False Negatives by optimizing decision thresholds to reduce financial impact.

Enhanced Security:
Provide a scalable and reliable tool to support financial institutions in improving risk management.

🛠️ Tools & Technologies

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, XGBoost

Environment: Google Colab

Interface: Gradio (interactive prototype)

📊 Dataset & Preprocessing

Source: Credit Card Fraud Detection Dataset 2023 (Kaggle)

Size: 568,630 transactions

Features:

28 anonymized features (V1–V28)

Transaction Amount

Data Processing Steps

Removed non-predictive columns (e.g., id)

Standardized numerical features to improve model stability

Addressed class imbalance (a common challenge in fraud detection datasets)

🤖 Model Selection & Training

Two primary models were evaluated:

1️⃣ Logistic Regression

Used as a baseline model

Provided performance benchmarks for comparison

2️⃣ XGBoost (Main Model)

Selected for its ability to capture non-linear patterns and complex feature interactions

Optimized using GridSearchCV for hyperparameter tuning

Applied Early Stopping to prevent overfitting

📈 Results & Evaluation

Models were evaluated using metrics suitable for imbalanced datasets:

PR-AUC

ROC-AUC

F1-Score

✅ The project successfully identified the optimal decision threshold (t*), maximizing fraud detection while minimizing unnecessary transaction blocks.

🖥️ Interactive Prototype (Gradio)

A web-based interactive interface built with Gradio, allowing users to:

Manual Entry:
Input values for V1–V28 and Amount manually

Auto-load Transactions:
Select a transaction from the test dataset using a slider

Real-time Analysis:
Display fraud probability and final classification
(Fraud or Legitimate) based on the optimized threshold

🚀 Future Improvements

Model Expansion:
Experiment with alternative algorithms such as LightGBM and CatBoost

Real-time Deployment:
Test and deploy the model in live production environments with low-latency requirements


👥 Team Members

Samaha Alhaddad
Ghaida Alhazzaa
Rahaf Al-Zahrani
Leen Althunyan
Rahaf Almuslat
Amal Almutairi
