# Online-Transactions-RFM-Analysis

This project implements a regression and clustering model to analyze customer behavior and predict future customer spending based on Recency, Frequency, and Monetary (RFM) analysis.
Project Overview
The RFM analysis is a powerful technique used in marketing and customer relationship management to segment customers based on their transaction history. This project applies RFM analysis to a large dataset of online sales transactions, utilizing various data science techniques and machine learning models.
Key Features

Data Cleaning: Processed a dataset of 541,909 rows, removing columns with null values to ensure data quality.
Exploratory Data Analysis (EDA): Generated various visualizations using Seaborn, Matplotlib, and Plotly libraries to understand customer behavior and spending patterns.
Customer Segmentation: Implemented K-Means clustering to assign RFM segments based on Recency, Frequency, and Monetary values.
Predictive Modeling: Developed Linear Regression and Decision Tree Regressor models to predict future customer spending.

Techniques Used

Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
K-Means Clustering
Linear Regression
Decision Tree Regression

Results

The Linear Regression model achieved an RMSE score of 865.09
The Decision Tree Regressor model achieved an RMSE score of 1245.66
The Linear Regression model performed better in predicting the monetary value

Libraries Used

Pandas (for data manipulation)
NumPy (for numerical operations)
Seaborn (for statistical data visualization)
Matplotlib (for creating static, animated, and interactive visualizations)
Plotly (for interactive plots)
Scikit-learn (for machine learning models and evaluation)

Future Work

Experiment with other clustering algorithms for customer segmentation
Implement more advanced regression models (e.g., Random Forest, Gradient Boosting)
Develop a user interface for easy interaction with the analysis results
Incorporate additional features for more comprehensive customer analysis
