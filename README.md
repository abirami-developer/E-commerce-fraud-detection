# E-commerce-fraud-detection
This project applies EDA, feature engineering, preprocessing, and multiple machine learning models to detect fraudulent transactions in an e-commerce dataset.

# Project Structure

ecommerce_fraud_detection.ipynb – Main Jupyter Notebook with EDA, preprocessing, feature engineering, model training, and evaluation

counterfeit_transactions.csv – Original dataset

fraud_detection_model.pkl – Saved trained model

E-Commerce-Fraud-Dashboard.pbix – Power BI dashboard for interactive fraud insights

# Features

Exploratory Data Analysis (EDA): Data summary, duplicates, outliers (boxplots), categorical distributions, fraud by weekday, correlation heatmap

Feature Engineering: Created fraud risk flags (high discount, velocity, frequent refunder, shipping risk, delivery anomaly) and fraud risk score

Data Preprocessing: Scaling, one-hot encoding, and class balancing with SMOTE

Machine Learning Models: Logistic Regression, Random Forest, XGBoost, LightGBM, Neural Network (Keras)

Evaluation Metrics: Confusion Matrix, Precision, Recall, F1-score, ROC-AUC, feature importance, ROC curve

Interactive Dashboard (Power BI): Visualizations of fraud by location, payment method, monthly trend, and risk patterns

# How to Run

Open ecommerce_fraud_detection.ipynb in Jupyter Notebook

Run the workflow step by step: EDA → Preprocessing → Feature Engineering → Modeling → Evaluation

Open E-Commerce-Fraud-Dashboard.pbix in Power BI to explore the dashboard

# Tools Used

Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM, Imbalanced-learn, TensorFlow/Keras

Jupyter Notebook

Power BI (Dashboard)

Excel/CSV (Dataset)
