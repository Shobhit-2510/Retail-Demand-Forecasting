# 📦 Retail Demand Forecasting via Gradient Boosting and Feature Encoding in Python

This project demonstrates a complete machine learning workflow for **retail demand forecasting** using the Big Mart Sales dataset. It includes data preprocessing, feature encoding, exploratory data analysis, and training a Gradient Boosting model (XGBoost Regressor) to predict item outlet sales.

---

## 🛠 Features

- Handling missing values (mean and mode imputation)
- Exploratory Data Analysis using Seaborn & Matplotlib
- Feature engineering and label encoding of categorical variables
- Model training using `XGBoostRegressor`
- Performance evaluation using R² Score
- Visual comparison of predicted vs. actual values

---

## 📁 Dataset

**Big Mart Sales Data**  
[Kaggle Link](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data)

---

## 📊 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

---

## 🚀 Model Overview

- **Model:** XGBRegressor
- **Hyperparameters:**
  - `n_estimators = 150`
  - `max_depth = 3`
  - `learning_rate = 0.05`
- **Evaluation Metric:** R² Score

---

## 📉 Results

| Metric           | Score |
|------------------|-------|
| R² Score (Train) | ~0.62 |
| R² Score (Test)  | ~0.61 |

> Includes scatter plots to visualize predictions vs. actual values.

---

## 📦 How to Run

1. Clone the repository.
2. Ensure dataset is available in the path.
3. Install dependencies:

```bash
pip install -r requirements.txt
python script.py

