# PRODIGY_ML_01
House Price Prediction using Linear Regression
# Task 01: House Price Prediction using Linear Regression

This project predicts housing prices using a simple linear regression model, based on the number of rooms (RM) in a house.

## 📂 Dataset

- **Source:** Scikit-learn’s Boston Housing Dataset
- **Features Used:** Only `RM` (average number of rooms per dwelling)
- **Target Variable:** `PRICE`

## 📈 Objectives

- Implement Linear Regression from scratch
- Analyze data using plots and statistical summaries
- Evaluate model performance using MAE, MSE, and R² score

## 🛠️ Tools Used

- Python, NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## 🔍 Evaluation Metrics

- **R² Score:** Measures how well predictions fit actual data
- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error

## 📊 Results

- Achieved an R² score of approximately `0.4–0.5` depending on random split
- Positive linear relationship between `RM` and `PRICE`

## 📌 How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
