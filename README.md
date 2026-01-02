# 🩺 Predicting Diabetes Using Machine Learning

EDA | Feature Engineering | Statistical Testing | ML Modeling

# 📌 Project Details

* Project Name: Predicting Diabetes Using Machine Learning

* Project Type: Exploratory Data Analysis & Machine Learning

* Contribution: Individual

* Domain: Healthcare Analytics

# 👤 Author

  Tauseef Alam

# 🧠 Project Overview

Diabetes is a chronic health condition that poses a major challenge to global healthcare systems. Early identification of high-risk individuals can significantly reduce complications and improve quality of life.

This project analyzes a large-scale Diabetes Prediction Dataset (100,000 records) to:

* Identify key risk factors contributing to diabetes

* Build a high-accuracy machine learning model to predict diabetes occurrence

The solution combines EDA, statistical hypothesis testing, feature engineering, and supervised machine learning, delivering both predictive power and actionable healthcare insights.

# 🎯 Problem Statement

Objectives

* Identify health and demographic factors influencing diabetes risk

* Build a robust ML classification model to predict diabetes (0 = No, 1 = Yes)

* Provide data-driven insights for early diagnosis and prevention

Target Variable

* diabetes → Binary classification (0 / 1)

# 📂 Dataset Description

Features Included:

* Gender

* Age

* BMI

* Hypertension

* Heart Disease

* Smoking History

* HbA1c Level

* Blood Glucose Level

Dataset Size:

* Rows: 100,000

* Columns: 9

# 🛠️ Tools & Technologies

* Python

* Pandas, NumPy

* Matplotlib, Seaborn

* Scikit-learn

* SciPy

* Joblib

# 🔄 Data Preprocessing & Wrangling

* Removed 3,854 duplicate records

* Encoded categorical variables (Gender, Smoking History)

* Standardized numerical features using StandardScaler

* Verified zero missing values

* Applied IQR-based outlier capping

* Handled class imbalance

* Split data into train/test sets

# 📊 Exploratory Data Analysis (EDA)

* Distribution analysis of BMI, Age, Blood Glucose

* Category-wise diabetes prevalence

* Correlation heatmap & pair plots

* Business-focused storytelling with visual insights

# Key EDA Insights

* High BMI, HbA1c, and blood glucose levels strongly correlate with diabetes

* Older age groups show higher diabetes prevalence

* Smoking history impacts BMI and diabetes risk

* Presence of hypertension and heart disease increases risk

# 📐 Hypothesis Testing

Statistical tests were conducted to validate assumptions:

* Hypertension vs Blood Glucose

  Result: Individuals with hypertension have significantly higher glucose levels (p < 0.05)

* Smoking vs BMI

  Result: BMI differs significantly between current smokers and non-smokers

* Heart Disease vs Diabetes Prevalence

  Result: Diabetes prevalence is higher among individuals with heart disease

✔ Independent t-tests used

✔ Statistically significant results

# 🤖 Machine Learning Models Implemented

* Logistic Regression

* Decision Tree

* Random Forest (Final Model)

* Support Vector Machine (SVM)

# Final Model: Random Forest Classifier

* Accuracy: 97%

* Strong balance of precision & recall

* Robust to noise and non-linear relationships

  * Accuracy: 0.97

  * Precision (Diabetic): 1.00

  * Recall (Diabetic): 0.67

# 📈 Model Evaluation Metrics

* Accuracy

* Precision

* Recall

* F1-Score

* Confusion Matrix

* Cross-Validation

# 🔍 Feature Importance

Top predictors identified:

* HbA1c Level

* Blood Glucose Level

* BMI

* Age

* Hypertension

# 💾 Model Deployment Readiness

* Best model saved using joblib

* Successfully reloaded and tested on unseen data

* Ready for integration into healthcare systems or applications

# 📌 Business Impact

* Enables early detection of diabetes

* Supports preventive healthcare strategies

* Improves resource allocation in medical systems

* Can power health monitoring apps & screening tools

# ✅ Conclusion

This project demonstrates the end-to-end application of data science in healthcare, combining:

* Statistical reasoning

* Machine learning

* Business insights

* Deployment readiness

It showcases the ability to turn raw medical data into accurate predictions and actionable intelligence.

# ⭐ Thank You for Reviewing!

If you’re a recruiter or hiring manager, this project reflects strong skills in EDA, ML modeling, statistical testing, and real-world problem solving.
