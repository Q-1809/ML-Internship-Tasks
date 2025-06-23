
# 📈 Task 02: Predict Future Stock Prices (Short-Term)

## 🎯 Objective
Use historical stock data to predict the **next day's closing price** using regression models.

---

## 📊 Dataset
- Source: Yahoo Finance
- Ticker: AAPL (Apple Inc.)
- Date Range: January 2022 – December 2024
- Retrieved using the `yfinance` Python library.

---

## ⚙️ Features Used
- **Open**
- **High**
- **Low**
- **Volume**

The target variable is the **Next Day's Close Price**, created by shifting the `Close` column.

---

## 🧠 Models Applied
- **Linear Regression**
- **Random Forest Regressor**

---

## 📋 Steps Performed
1. **Data Download** using `yfinance`
2. **Feature Engineering**: Created `Next_Close` target
3. **Data Preprocessing**: Handled missing values using `.dropna()`
4. **Training and Testing**: 80-20 split, no shuffling (to preserve time sequence)
5. **Model Training** using scikit-learn
6. **Evaluation Metrics**:
   - R² Score
   - RMSE (Root Mean Squared Error)
7. **Visualization**:
   - Actual vs Predicted close prices (line plot)
   - Correlation heatmap

---

## 📈 Results Summary

| Model              | R² Score | RMSE       |
|-------------------|----------|------------|
| Linear Regression | ~0.92    | Moderate   |
| Random Forest     | **~0.97**| Lower (Better)|

> 🔍 **Random Forest Regressor** outperformed Linear Regression in accuracy and prediction consistency.

---

## 🖼️ Visual Output

- Actual vs Predicted plot showing strong correlation.
- Feature correlation heatmap showing most impactful predictors.

---

## 🧾 Tools & Libraries
- `yfinance`, `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## 🗂️ Repository Structure

```
📁 Task_02_Stock_Prediction/
├── task02_stock_price_prediction.ipynb
└── README.md
```

---

## ✅ Status
✅ Completed and ready for submission on GitHub and Google Classroom.

---
