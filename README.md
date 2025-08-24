# Retail-Analytics-Predicting-Product-Sales-with-Machine-Learning
Big Mart Sales Prediction using Machine Learning

This project predicts the sales of products across different Big Mart outlets using machine learning techniques.
The goal is to build an end-to-end ML pipeline that can help retailers understand sales drivers and forecast demand effectively.

📌 Project Overview

Objective: Predict sales of individual products at different stores.

Dataset: Big Mart Sales dataset (commonly used for regression problems in retail).

ML Lifecycle Covered:

Data Exploration & Cleaning

Handling Missing & Duplicate Values

Feature Engineering (e.g., Outlet Size, Item Fat Content, Establishment Year)

Encoding Categorical Variables

Model Training (Random Forest Regressor)

Model Evaluation

🗂️ Dataset

The dataset consists of sales transactions from Big Mart outlets.
Key Columns:

Item_Identifier – Unique product ID

Item_Weight – Weight of product

Item_Fat_Content – Fat type (Low Fat / Regular)

Item_Visibility – Shelf visibility percentage

Item_Type – Category of the item

Item_MRP – Maximum Retail Price

Outlet_Identifier – Store ID

Outlet_Size – Size of the store

Outlet_Establishment_Year – Year of establishment

Outlet_Location_Type – Tier location of outlet

Item_Outlet_Sales – Target variable (sales)

🔑 Key Steps
1. Data Cleaning

Removed duplicates

Handled missing values using Univariate and Multivariate Imputation

2. Feature Engineering

Transformed categorical columns like Item_Fat_Content, Outlet_Size

Extracted features from Outlet_Establishment_Year

Adjusted Item_Visibility for better interpretability

3. Encoding

Converted categorical features into numerical form using encoding techniques

4. Model Training

Trained a Random Forest Regressor to predict sales

Evaluated model performance using R² and error metrics

📊 Results

Random Forest achieved strong predictive performance on sales prediction.

Demonstrated the importance of feature engineering (e.g., visibility correction, outlet details).
