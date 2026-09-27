# House Price Prediction Using Regression

## Project Overview

This project focuses on predicting house prices using **Machine Learning Regression techniques**.

The dataset contains information about residential properties, including area, number of bedrooms, bathrooms, stories, parking availability, location-related features, and furnishing status.

The project combines **Data Analytics, Exploratory Data Analysis (EDA), Data Preprocessing, Regression Modeling, and Model Evaluation** to understand the factors influencing house prices and predict prices for new properties.

---

## Objectives

- Understand and analyze the house price dataset.
- Perform data cleaning and preprocessing.
- Explore relationships between house features and prices.
- Analyze numerical and categorical variables.
- Convert categorical variables into machine-readable format.
- Build a Linear Regression model.
- Build a Random Forest Regression model.
- Compare model performance.
- Evaluate predictions using MAE, RMSE, and R² Score.
- Predict the price of a new house based on its features.

---

## Dataset

The dataset contains **545 house records** and **13 columns**.

### Dataset Features

| Column | Description | Data Type |
|---|---|---|
| `price` | Price of the house | Integer |
| `area` | Area of the house | Integer |
| `bedrooms` | Number of bedrooms | Integer |
| `bathrooms` | Number of bathrooms | Integer |
| `stories` | Number of stories | Integer |
| `mainroad` | Whether the house is connected to the main road | Categorical |
| `guestroom` | Availability of a guestroom | Categorical |
| `basement` | Availability of a basement | Categorical |
| `hotwaterheating` | Availability of hot water heating | Categorical |
| `airconditioning` | Availability of air conditioning | Categorical |
| `parking` | Number of parking spaces | Integer |
| `prefarea` | Whether the property is in a preferred area | Categorical |
| `furnishingstatus` | Furnishing status of the house | Categorical |

### Dataset Summary

- **Rows:** 545
- **Columns:** 13
- **Target Variable:** `price`
- **Numerical Features:** 5
- **Categorical Features:** 7
- **Missing Values:** None

---

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Google Colab / Jupyter Notebook**
- **GitHub**

---

##  Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Correlation Analysis
   ↓
Feature Preprocessing
   ↓
Train-Test Split
   ↓
Linear Regression
   ↓
Random Forest Regression
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
House Price Prediction
