# 🚗 Kaggle Playground Series 2024 - Automobile Insurance Offer Response Prediction

## 🌟 Overview

This notebook was created for the 2024 Kaggle Playground Series competition. The objective is to predict which customers respond positively to an automobile insurance offer using a synthetically generated dataset.

## 🛠️ Steps Followed

### 1. Data Preparation 📊
- **Loading Data:** Imported datasets and explored their structure.
- **EDA:** Visualized key features and analyzed correlations.
- **Feature Engineering:** Created new features like `age_bucket`, `premium_ratio`, and `damage_history`.

### 2. Model Development 🤖
- **Model Selection:** Implemented LightGBM, CatBoost, and XGBoost.
- **Hyperparameter Tuning:** Optimized parameters using `RandomizedSearchCV`.
- **Model Training:** Applied cross-validation to ensure robustness.

### 3. Model Evaluation 🏅
- **Performance Metrics:** Evaluated models using AUC and ROC curves.
- **Feature Importance:** Analyzed and visualized feature importance.

### 4. Final Submission 📝
- **Prediction:** Generated predictions on the test set.
- **Submission Preparation:** Formatted results for submission.

## 🎯 Results
- Achieved competitive AUC scores, with LightGBM providing the best performance.

## 🚀 How to Use
- **Run the Notebook:** Execute cells sequentially to replicate the analysis.
- **Dependencies:** Ensure all necessary libraries (`pandas`, `numpy`, `lightgbm`, `catboost`, `xgboost`, etc.) are installed.

