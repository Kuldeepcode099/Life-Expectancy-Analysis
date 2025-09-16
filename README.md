Project 1: Cybersecurity – Suspicious Web Threat Interactions

This project focuses on analyzing AWS CloudWatch web traffic logs to detect suspicious or malicious activity. The dataset contained information such as IP addresses, ports, countries, bytes transferred, and rule names.

🔹 Key Steps

Data Cleaning & Preprocessing: Removed duplicates, handled missing values, converted timestamps.

Feature Engineering: Session duration, average packet size, throughput, and a binary suspicious label.

EDA: Distribution plots, port/protocol analysis, country-wise traffic, correlation heatmap, and network graphs.

Anomaly Detection: Isolation Forest and Local Outlier Factor for unsupervised detection.

Classification Models: RandomForest, MLP, and Conv1D Neural Networks.

Evaluation: Accuracy, precision, recall, F1-score, and ROC-AUC.

🔹 Results

RandomForest achieved more than 90% accuracy, and anomaly detection models successfully flagged abnormal traffic patterns.

👉 Notebook: Cybersecurity_Project.ipynb

🚀 Project 2: Life Expectancy Analysis

This project predicts life expectancy across countries using socio-economic and health-related indicators such as GDP, schooling, healthcare expenditure, and mortality rates.

🔹 Key Steps

Data Cleaning: Handled missing values with mean imputation, treated outliers using IQR, removed duplicates.

EDA: Distribution plots, correlation heatmap, year-wise trends, and developed vs. developing country comparison.

Preprocessing: Label Encoding for categorical features and Standard Scaling for numeric values.

Regression Models: RandomForest, ExtraTrees, GradientBoosting, and XGBoost.

Model Evaluation: Compared models using RMSE and R².

Cross Validation: Performed on XGBoost for consistent results.

🔹 Results

XGBoost provided the best performance with low RMSE and high R², proving reliable for predicting life expectancy.
