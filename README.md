# 🌱 Farm Profitability Prediction

A machine learning project for predicting annual net profit for U.S. farms using historical USDA income and expense data.

## 📊 Data Summary

- **Source**: USDA Economic Research Service
- **Years Covered**: 1910–2025
- **Variables**: Seed, fertilizer, electricity, labor, fuel, revenue (commodity receipts), and more
- **Preprocessing**: Missing value imputation, column renaming, and rescaling by 1000

## 🧠 Model Summary

- **Target**: All Commodity Receipts (Revenue)
- **Features**: 9 top-correlated farm expense categories
- **Model**: Random Forest Regressor (Scikit-learn)
- **Evaluation**: K-Fold CV, Time Series CV, Feature Importance
