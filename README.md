# 🏡 House Price Prediction

This project aims to predict house prices using various regression models and identify the best-performing algorithm based on evaluation metrics such as R², MAE, and RMSE.

## 📊 Project Goals

- Explore and understand housing data
- Train and evaluate multiple regression models
- Compare their performance
- Select the best model for deployment

## 📁 Dataset

The dataset includes features such as city, land size, building area, and more. It is not publicly available due to privacy concerns.

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- scikit-learn
- XGBoost

## 🔄 Workflow

1. Exploratory Data Analysis (EDA)
2. Data Preprocessing:
   - Handling missing values (if any)
   - Encoding and scaling
3. Splitting into Train & Test sets
4. Model Training:
   - Linear Regression
   - Ridge, Lasso, ElasticNet
   - Decision Tree, Random Forest
   - SVR, KNN
   - XGBoost
5. Model Evaluation:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score
6. Model Comparison (with visualizations)

## 📈 Evaluation Summary

| Model               | R² Score | MAE     | RMSE    |
|--------------------|----------|---------|---------|
| Linear Regression   | …        | …       | …       |
| Random Forest       | …        | …       | …       |
| XGBoost             | ✅ **Best** | …       | …       |

*Full results are in the notebook.*

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook BNSP.ipynb
```

## 📌 Notes

- Created as part of a certification assessment for Data Science (BNSP).
- The notebook is self-contained and well-commented for learning purposes.
