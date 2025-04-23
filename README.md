# SedentaryGuard

📌 Overview
This project introduces a smart health monitoring system that utilizes real-time data from wearable devices and historical health records to proactively predict heart disease risks caused by sedentary lifestyles using machine learning (ML).

🎯 Objective
To transform reactive healthcare into proactive wellness management by:
1) Integrating real-time and historical health data.
2) Applying ML algorithms to predict cardiovascular risks.
3) Providing personalized and real-time health insights.

🛠️ Methodology
A) Data Collection & Processing
  1) Source: Firebase Realtime Database (aggregates data from IoT wearables).
  2) Preprocessing:
     - Data cleaning and imputation
     - Normalization and encoding
     - Feature vector aggregation
B) Machine Learning Models
  1) Algorithms Used:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Gradient-Boosted Trees (GBT)
  2) Evaluation Metrics:
     - Accuracy, Precision, Recall, F1-Score, AUC
  3) Output: Risk scores (0–100) categorized as Low, Medium, or High

📊 Results
1) Pilot Test: 200 participants
2) Findings:
  - Most users fell in the Low-risk category (right-skewed scores).
  - Strong correlation between ensemble methods and logistic regression.
  - Increased user activity and positive feedback on alerts.
  - Better personalization compared to existing systems.
