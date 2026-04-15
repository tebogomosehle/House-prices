# 🏠 House Price Prediction & Feature Analysis

## 📌 Project Overview
This project builds a Linear Regression model to predict house prices and analyzes the impact of different variables using statistical techniques.

---

## 📂 Dataset

### 📥 Data Source
Dataset obtained from Kaggle:  
https://www.kaggle.com/datasets/fratzcan/usa-house-prices 
- Size: 4140 entries, 17 features  
- Target variable: `Price'

---

## 🛠️ Tools & Libraries
- Python (Pandas, NumPy)
- Scikit-learn
- Statsmodels
- Seaborn (data visualisation)
---

## 📊 Approach

- Performed exploratory data analysis (EDA) using Seaborn visualisations (including jointplots) to understand relationships between variables
- Built a baseline Linear Regression model (RMSE ≈ 195,711)
- Handled outliers to improve model stability
- Used statsmodels to assess statistical significance
- Performed feature selection based on both p-values and model performance

### 🔍 Key Decisions
- `floors` removed → reduced MSE  
- `year_renovated` retained → improved prediction despite insignificance  

---

## 📈 Results

- Final RMSE: **~190,918**
- R² remained relatively stable (~0.63)

✔️ Model improvements reduced prediction error while maintaining explanatory power.

---

## ⚠️ Considerations
- Evidence of multicollinearity (high condition number)
- Location feature contributed to model complexity
- Some insignificant variables still improved prediction

---

## 💡 Key Insights
- Statistical significance ≠ predictive importance  
- Feature selection should be guided by performance metrics  
 
---

## 👤 Author
Tebogo Mosehle

📫 [tebogomosehle10@gmail.com]

