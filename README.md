Overview

During my internship, I worked on two major projects that helped me apply machine learning to real-world problems. The first one was based on cybersecurity, where I analyzed AWS CloudWatch traffic logs to detect suspicious activity. The second one was in the healthcare domain, where I predicted life expectancy of different countries based on socio-economic and health indicators.

Both projects gave me practical experience in handling data from scratch — cleaning, preprocessing, exploring it through visualization, building models, and evaluating them to find the best results.

🚀 Project 1: Cybersecurity – Suspicious Web Threat Interactions

This project was focused on detecting unusual or malicious web traffic. The dataset had IPs, ports, countries, bytes transferred, and detection rule names.

🔹 What I Did

Cleaned and preprocessed the dataset (removed duplicates, handled missing values, converted timestamps).

Created new features like session duration, average packet size, and throughput.

Did EDA with histograms, port/protocol usage, traffic by country, correlation heatmaps, and even a small network graph.

Used Isolation Forest and Local Outlier Factor to detect anomalies.

Built classification models using RandomForest and experimented with MLP and Conv1D neural networks.

Evaluated models with accuracy, precision, recall, F1-score, and ROC-AUC.

🔹 Results

RandomForest gave the best performance with 90%+ accuracy, and anomaly detection models flagged unusual patterns successfully.

👉 Notebook: Cybersecurity_Project.ipynb

🚀 Project 2: Life Expectancy Analysis

The second project was about predicting the life expectancy of different countries using health and economic data.

🔹 What I Did

Cleaned the dataset (handled missing values, removed outliers using IQR, dropped duplicates).

Explored trends with distribution plots, correlation heatmaps, and compared developed vs. developing countries.

Preprocessed data with Label Encoding for categorical features and scaling for numeric ones.

Trained regression models: RandomForest, ExtraTrees, GradientBoosting, and XGBoost.

Compared models using RMSE and R².

Performed cross-validation on XGBoost to check consistency.

🔹 Results

XGBoost turned out to be the best model, giving strong predictions with high R² and low RMSE.

👉 Notebook: Life_Expectancy_Project.ipynb

⚙️ Requirements

pandas, numpy, matplotlib, seaborn

scikit-learn

xgboost

tensorflow / keras

networkx
