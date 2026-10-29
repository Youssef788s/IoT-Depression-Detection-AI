# 🧠 IoT-Based Depression Detection System

## 📌 Project Overview
This project is an end-to-end Machine Learning solution designed to predict depression by analyzing continuous motor activity logs from IoT sensors combined with clinical and demographic data.

## 📊 Dataset & Feature Engineering
- Extracted statistical features from raw IoT time-series data (Mean Activity, Zero Activity Ratio, Standard Deviation).
- Preprocessed demographic data (imputation and range midpoints) and handled class stratification.

## 🏆 Model Performance
Five models were benchmarked (Random Forest, XGBoost, Gradient Boosting, Logistic Regression, SVM).
- **Best Model:** Random Forest Classifier
- **Accuracy:** 81.82%
- **F1-Score:** 75.00%

## 🚀 Deployment & Team Handoff
- [x] Model successfully trained, evaluated, and serialized as `best_depression_model.pkl`.
- [x] Inference script provided for new patient evaluations.
- [ ] **Backend Team:** Integrate the `.pkl` model into the system architecture via a REST API.
