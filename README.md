📦 Retail Demand Forecasting via Gradient Boosting and Feature Encoding in Python
This project demonstrates a complete machine learning workflow for retail demand forecasting using the Big Mart Sales dataset. It includes data preprocessing, feature encoding, exploratory data analysis, and training a Gradient Boosting model (XGBoost Regressor) to predict item outlet sales.

🛠 Features
Handling missing values (mean and mode imputation)

Exploratory Data Analysis using Seaborn & Matplotlib

Feature engineering and label encoding of categorical variables

Model training using XGBoostRegressor

Performance evaluation using R² Score

Visual comparison of predicted vs. actual values

📁 Dataset
Big Mart Sales Data
Available at: [/content/drive/MyDrive/Datasets_for_ML_Projects/Big Mart Sales Data/Train.csv](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data)

📊 Libraries Used
pandas, numpy

matplotlib, seaborn

sklearn (LabelEncoder, train_test_split, metrics)

xgboost

🚀 Model Overview
Model Used: XGBRegressor

Hyperparameters:

n_estimators = 150

max_depth = 3

learning_rate = 0.05

Evaluation Metrics: R² Score on both training and test sets

📉 Results
Metric	Score
R² Score (Train)	≈ 0.61
R² Score (Test)	≈ 0.62

Visuals include actual vs. predicted scatter plots for both train and test sets.

📌 How to Run
Clone this repository.

Install required libraries (pip install -r requirements.txt).

Upload the dataset to the appropriate path.

Run the Python script or Jupyter Notebook.
