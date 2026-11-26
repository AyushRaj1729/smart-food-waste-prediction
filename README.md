# Smart Food Waste Prediction System

## 1. Introduction

Food wastage is a major problem in the retail and food
industry. Businesses often struggle to estimate customer
demand, resulting in excess inventory and food wastage.

This project aims to develop a Machine Learning-based
system that predicts food demand and identifies potential
surplus inventory.

## 2. Objectives

- Predict daily demand for different food products.
- Identify products at risk of becoming surplus.
- Reduce unnecessary food wastage.
- Recommend suitable inventory management actions.

## 3. Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Streamlit

## 4. Machine Learning Algorithms

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## 5. Project Status

Currently in the initial development stage.

## 6. Future Scope

- Interactive prediction dashboard.
- Food surplus identification.
- Discount recommendations.
- Food redistribution support.



## 📊 Dataset Description

This project uses three datasets to analyze food demand patterns and predict food orders, helping reduce food wastage.

### 1. Training Dataset (`train.csv`)
- Contains historical food order information.
- Includes features such as `id`, `week`, `center_id`, `meal_id`, `checkout_price`, `base_price`, `emailer_for_promotion`, `homepage_featured`, and `num_orders`.
- The `num_orders` column represents the target variable used for demand prediction.

### 2. Meal Information Dataset (`meal_info.csv`)
- Contains details about different meal items.
- Includes `meal_id`, `category`, and `cuisine`.
- Helps identify food categories and cuisine types associated with customer demand.

### 3. Fulfilment Center Dataset (`fulfilment_center_info.csv`)
- Contains information about fulfilment centers.
- Includes `center_id`, `city_code`, `region_code`, `center_type`, and `op_area`.
- Helps analyze food demand across different locations and operational areas.

### Dataset Integration
The three datasets are merged using `meal_id` and `center_id` to create a unified dataset for exploratory data analysis, preprocessing, feature engineering, and machine learning model development.