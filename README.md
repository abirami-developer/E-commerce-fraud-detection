# E-commerce-fraud-detection

This project applies EDA, feature engineering, preprocessing, and multiple machine learning models to detect fraudulent transactions in an e-commerce dataset.

# Project Structure

ecomm.ipynb – Main Jupyter Notebook with full workflow: EDA, preprocessing, feature engineering, model training, and evaluation

Ecommerce_Fraud_data.xlsx – Original dataset used for analysis

Ecommerce_Fraud_testdata.xlsx – Cleaned/test dataset for modeling

E-Commerce Dashboard.pbix – Power BI dashboard for interactive fraud insights

# Features

Exploratory Data Analysis (EDA): Data summary, duplicates, outliers (boxplots), categorical distributions, fraud by weekday, correlation heatmap

Feature Engineering: Fraud risk flags including high-value transaction, velocity, suspicious discount, frequent refunder, shipping risk, delivery anomalies, and fraud risk score

Data Preprocessing: Scaling, one-hot encoding, and class balancing using SMOTE

Machine Learning Models: Logistic Regression, Random Forest, XGBoost, LightGBM, Neural Network (Keras)

Evaluation Metrics: Confusion Matrix, Precision, Recall, F1-score, ROC-AUC, feature importance, ROC curve

Interactive Dashboard (Power BI): Visualizations of fraud by location, payment method, monthly trends, and high-risk patterns

# How to Run

Open ecomm.ipynb in Jupyter Notebook

Follow the workflow step by step: EDA → Preprocessing → Feature Engineering → Model Building → Evaluation → Insights

Open E-Commerce Dashboard.pbix in Power BI to explore the interactive dashboard

# Tools Used

Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM, Imbalanced-learn, TensorFlow/Keras

Jupyter Notebook (ecomm.ipynb)

Power BI (E-Commerce Dashboard.pbix)

Excel/CSV (Ecommerce_Fraud_data.xlsx, Ecommerce_Fraud_testdata.xlsx)
