# Linear Regression – Housing Price Prediction

This project implements **simple and multiple linear regression** using the Housing Price Prediction dataset to understand how various features impact housing prices.

---

## 📂 Dataset

- **Name**: Housing Price Prediction Dataset  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)  
- **Format**: CSV  
- **Records**: 545 rows × 13 columns  
- **Target Variable**: `price`

---

## ✅ Task Objectives

1. Import and preprocess the dataset  
2. Split data into train-test sets  
3. Fit a Linear Regression model using `sklearn.linear_model`  
4. Evaluate model using MAE, MSE, R²  
5. Plot regression line  
6. Interpret model coefficients

---

## ⚙️ Tech Stack

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📈 Evaluation Metrics

| Metric | Value |
|--------|-------|
| Mean Absolute Error (MAE) | ₹970,043 |
| Mean Squared Error (MSE) | ₹1.75 Trillion |
| R² Score | 0.653 |

---

## 📊 Key Observations

- House `area`, `bedrooms`, and `bathrooms` significantly influence the price.  
- Fully **furnished houses** command a **higher price** than semi- or unfurnished ones.  
- The model captures ~65.3% of variance in the dataset (R² score = 0.65).

---
