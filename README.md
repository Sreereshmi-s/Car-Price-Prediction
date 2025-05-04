# 🚗 Car Price Prediction using Machine Learning

This project aims to model and predict car prices based on various features, using multiple regression algorithms. The goal is to support strategic decision-making for a Chinese automobile company entering the US market.

---

## 📊 Business Problem

A Chinese automobile company wants to understand the pricing dynamics of the US car market. They need to know:
- Which features influence car prices the most.
- How accurately we can predict prices using those features.

---

## 🧠 Machine Learning Models Used

The following regression models were implemented and evaluated:

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **Gradient Boosting Regressor**
5. **Support Vector Regressor (SVR)**

---

## 🧪 Steps Performed

1. **Data Preprocessing**
   - Dropped irrelevant columns
   - One-hot encoding for categorical variables
   - Feature scaling where needed

2. **Model Training & Evaluation**
   - R² Score, Mean Squared Error (MSE), and Mean Absolute Error (MAE) used for performance comparison
   - Graphical R² comparison across models

3. **Feature Importance Analysis**
   - Identified most influential features using tree-based models
   - Top factors: Engine Size, Curb Weight, Horsepower, etc.

4. **Hyperparameter Tuning**
   - Grid Search applied to Random Forest for performance boost

---

## 📈 Results

- **Best Model**: ✅ Random Forest Regressor  
- **Performance**:
  - R² Score: ~0.96
  - MAE & MSE: Lowest among all models

---

## 🔍 Business Insights

- Car prices are most influenced by technical specifications like engine size, horsepower, and vehicle weight.
- These insights can help guide vehicle design, market segmentation, and pricing strategy for new market entry.

---
