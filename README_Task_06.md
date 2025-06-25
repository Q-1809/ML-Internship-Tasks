
# 🏠 Task 06: House Price Prediction using Boston Housing Dataset

## 🎯 Objective
Build a regression model to predict **median house prices** in Boston using selected features from the dataset.

---

## 📊 Dataset
- **Name**: Boston Housing Dataset
- **Source**: [Selva86 GitHub Dataset Link](https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv)
- **Target Variable**: `medv` — Median value of owner-occupied homes

---

## 🧹 Features Used
- `rm`: Average number of rooms per dwelling
- `dis`: Weighted distances to five Boston employment centers
- `rad`: Accessibility to radial highways

These were chosen for their intuitive relation to house price (space, location, accessibility).

---

## 🧠 Model
- **Type**: Linear Regression (from `sklearn.linear_model`)

---

## 📋 Steps Performed
1. Load dataset from remote URL using pandas
2. Preview dataset shape and summary statistics
3. Display correlation heatmap for EDA
4. Select features and define the target (`medv`)
5. Split data into training and test sets (80/20)
6. Train a linear regression model
7. Evaluate model using:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
8. Visualize predicted vs actual home prices

---

## 📈 Results Summary

| Metric | Value |
|--------|--------|
| MAE    | ~3.2   |
| RMSE   | ~4.5   |

> 🔍 Results may vary slightly due to randomness in train-test split.

---

## 🖼️ Visual Output

- A **scatter plot** of actual vs predicted prices with an ideal `y = x` reference line
- **Correlation heatmap** showing relationships between features and target

---

## 🧾 Libraries Used
- `pandas`, `numpy`
- `seaborn`, `matplotlib`
- `sklearn.linear_model`, `sklearn.metrics`, `sklearn.model_selection`

---

## ✅ Status
✅ Completed and ready to include in internship repository or submit on Google Classroom.
