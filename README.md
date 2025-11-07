# Heart_Disease_Prediction
❤️ Heart Disease Prediction (PRCP-1016)
📘 Overview

This project focuses on predicting the likelihood of heart disease in patients using clinical and exercise-test data such as age, chest pain type, blood pressure, cholesterol, max heart rate, and more.

By applying advanced machine learning algorithms, this project demonstrates how data-driven models can support early diagnosis and preventive healthcare.

🎯 Objectives

Analyze clinical data to identify key factors influencing heart disease.

Build and compare multiple ML models to predict heart disease risk.

Evaluate model performance and interpret key features driving predictions.

Develop an interpretable, accurate, and generalizable predictive model.

🧠 Why This Project Is Useful

Early Detection: Helps identify high-risk patients before major symptoms appear.

Clinical Decision Support: Assists doctors with data-based risk estimation.

Insight Generation: Highlights the most influential health indicators (like chest pain type, exercise-induced angina, max heart rate).

Automation: Can be integrated into healthcare systems or screening tools for real-time predictions.

🔍 Data Description

The dataset (based on the UCI Heart Disease dataset) includes features such as:

Age, Sex, Chest Pain Type

Resting Blood Pressure, Serum Cholesterol

Fasting Blood Sugar, Resting EKG Results

Max Heart Rate Achieved, Exercise-Induced Angina

Oldpeak (ST Depression), Slope, Number of Major Vessels

Target: Presence or absence of heart disease

⚙️ Workflow

Data Cleaning & Preprocessing – Handling missing values, encoding categorical features, scaling.

Exploratory Data Analysis (EDA) – Univariate, bivariate analysis, and correlation heatmap.

Feature Engineering – Transformation and normalization of predictors.

Model Training & Tuning – Logistic Regression, k-NN, SVM, Decision Tree, Random Forest, Gradient Boosting, XGBoost, and Neural Network.

Hyperparameter Optimization – GridSearchCV and cross-validation.

Evaluation – Accuracy, Precision, Recall, F1-score, ROC-AUC, and confusion matrix comparison.

Model Interpretation – Feature importance and explainability analysis.

🏆 Key Results

After training and tuning multiple models, the XGBoost Classifier achieved the best performance:

Accuracy: 91.3%

ROC-AUC Score: 0.94
This indicates that ensemble boosting techniques effectively capture nonlinear patterns in patient data, making XGBoost the most reliable model for heart disease prediction.

🧩 Tools & Technologies

Language: Python 🐍

Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost

Techniques: GridSearchCV, Feature Engineering, EDA, Model Evaluation

Environment: Jupyter Notebook / Google Colab

💡 Key Learnings

Built an end-to-end ML pipeline from raw data to model evaluation

Improved model accuracy through GridSearch-based hyperparameter tuning

Enhanced interpretability using feature importance and correlation analysis

Gained insights into cardiovascular health through data patterns
