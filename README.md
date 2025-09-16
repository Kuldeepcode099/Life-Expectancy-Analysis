Life Expectancy Analysis – Machine Learning Project
 Overview

As part of my internship, I worked on this project to predict life expectancy across different countries using socio-economic and health-related indicators. The dataset included variables such as GDP, schooling, alcohol consumption, healthcare expenditure, mortality rates, and other key features.

The main goal of this project was to apply machine learning regression models to understand which factors influence life expectancy the most, and to build a reliable model for prediction.

 What I Did 

Data Cleaning
I started by removing duplicate records, handling missing values with mean imputation, and treating outliers using the IQR method by replacing them with the mean. This helped in improving the quality of the dataset.

Exploratory Data Analysis (EDA)
I explored the dataset with histograms, boxplots, and correlation heatmaps. I analyzed year-wise trends in life expectancy and compared values between developed and developing countries. I also studied how factors like schooling, population, and alcohol consumption were correlated with life expectancy.

Preprocessing
I used Label Encoding to convert categorical variables (such as country status) into numerical form and applied StandardScaler to normalize numerical features for better model performance.

Model Building
I experimented with multiple regression models:

RandomForest Regressor

ExtraTrees Regressor

Gradient Boosting Regressor

XGBoost Regressor

Model Evaluation
I compared the models based on RMSE (Root Mean Squared Error) and R² score. Among all, XGBoost performed the best, achieving high R² and low RMSE.

Cross Validation
To ensure the robustness of the XGBoost model, I performed cross-validation which confirmed consistent performance across folds.

🔹 Results

This project helped me understand how socio-economic and health indicators affect life expectancy. It also gave me hands-on experience with regression modeling, data preprocessing, and cross-validation. XGBoost proved to be the most reliable model for this task.
