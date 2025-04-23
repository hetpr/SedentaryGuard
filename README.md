# 💓 SedentaryGuard

A smart health monitoring system for **real-time prediction of heart disease risk** induced by **sedentary lifestyles**, powered by **machine learning** and **wearable data integration**.

---

## 📌 Overview

This project introduces a smart health monitoring system that utilizes **real-time data from wearable devices** and **historical health records** to proactively predict **heart disease risks** using ML.

---

## 🎯 Objective

Transform **reactive healthcare** into **proactive wellness management** by:

1. Integrating real-time and historical health data.
2. Applying ML algorithms to predict cardiovascular risks.
3. Providing personalized and real-time health insights.

---

## 🛠️ Methodology

### 🗃️ A) Data Collection & Processing

- **Source:** Firebase Realtime Database (aggregates data from IoT wearables)
- **Preprocessing:**
  - Data cleaning and imputation
  - Normalization and encoding
  - Feature vector aggregation

### 🤖 B) Machine Learning Models

1. **Algorithms Used:**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Gradient-Boosted Trees (GBT)

2. **Evaluation Metrics:**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - AUC

3. **Output:**
   - Risk Score (0–100)
   - Categorized as: **Low**, **Medium**, **High**

---

## 📊 Results

- **Pilot Test:** 200 participants
- **Findings:**
  - Majority fell in the **Low-risk** category (right-skewed distribution)
  - High correlation (up to 0.96) between ensemble methods and logistic regression
  - Users reported:
    - Increased physical activity
    - Positive feedback on real-time alerts
    - Better personalization than existing solutions
