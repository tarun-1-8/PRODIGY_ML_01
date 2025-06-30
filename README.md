# 🏡 Task 01: House Price Prediction using Linear Regression

This project is part of my Machine Learning Internship under **Prodigy InfoTech**.  
The goal is to predict house prices using regression techniques based on real estate data provided by Kaggle.

---

## 📁 Dataset Information

- **Source:** [Kaggle: House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- **Rows:** 1460 training records
- **Columns:** 81 features (e.g., LotArea, Neighborhood, OverallQual, YearBuilt, SaleCondition, etc.)
- **Target Variable:** `SalePrice` (the final price of each house)

---

## 🎯 Objective

The main aim is to build a **Linear Regression** model to predict house prices based on different numerical and categorical features.

---

## 🧪 Project Steps

1. **Dataset Loading & Preprocessing**
   - Loaded data from CSV file
   - Handled missing values
   - Selected relevant numerical features for linear regression

2. **Exploratory Data Analysis (EDA)**
   - Used correlation matrix to identify most influential features
   - Visualized relationships between features and price

3. **Model Building**
   - Implemented a Linear Regression model using `scikit-learn`
   - Split data into training and testing sets
   - Trained model and made predictions

4. **Model Evaluation**
   - Calculated:
     - R² Score
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
   - Plotted actual vs predicted values
   - Visualized residuals

---

## 📊 Results

- Top correlated features with `SalePrice`: `OverallQual`, `GrLivArea`, `GarageCars`, `TotalBsmtSF`, `1stFlrSF`
- Linear Regression worked well for selected features
- Achieved an R² Score of around `0.75 - 0.85` depending on feature set and split
- Error metrics showed reasonably good prediction performance

---

## 📦 Tools & Libraries Used

- Python 3
- NumPy, Pandas
- Seaborn, Matplotlib
- Scikit-learn

---

## 📘 Learning Outcomes

- Practiced data cleaning and feature selection
- Understood real estate dataset structure
- Applied linear regression on real-world data
- Improved understanding of evaluation metrics and plotting

---

## 📁 Files Included

| File Name | Description |
|-----------|-------------|
| `Task01_House_Price_Prediction.ipynb` | Main code with complete workflow |
| `regression_plot.png` | Plot showing predicted vs actual sale prices |
| `residuals_plot.png` | Distribution of prediction errors |
| `README.md` | This documentation |

---

## 📬 Author

## 📬 Connect with Me:

**Tarun Sharma**  
B.Tech CSE | K.R. Mangalam University  
Machine Learning Intern @ Prodigy InfoTech  
GitHub: [tarun-1-8](https://github.com/tarun-1-8)  
LinkedIn: [Tarun Sharma](https://www.linkedin.com/in/tarun-sharma-1-8/)


---



