# 🚗 CarDekho Dataset - Used Car Price Prediction

This project focuses on predicting the **selling price of used cars** using various machine learning algorithms. By analyzing features like brand, manufacturing year, fuel type, and more, we aim to estimate fair market prices for vehicles in the Indian market. 🇮🇳

---

## 📖 About the Dataset

The dataset is sourced from **Kaggle** and contains detailed information about used cars listed on the CarDekho platform. Each record includes:

- Car brand and model  
- Year of manufacture  
- Fuel type (Petrol, Diesel, etc.)
- Seller type (Dealer or Individual)
- Transmission type  
- Number of kilometers driven  
- Ownership status  
- Selling price (target variable)  

This dataset is ideal for practicing **regression techniques** and understanding how different features influence used car prices.

---

## 🎯 Objective

Build and evaluate multiple machine learning models to **predict the selling price** of used cars as accurately as possible.

---

## 🛠️ What I Did

- ✅ Data cleaning and preprocessing  
- 📊 Exploratory Data Analysis (EDA)  
- 🏷️ Encoded categorical variables  
- ⚖️ Handled missing values and outliers  
- 📈 Applied multiple regression algorithms:
  - 📐 Linear Regression  
  - 🔵 Ridge Regression (L2 Regularization)  
  - 🔴 Lasso Regression (L1 Regularization)  
  - 📍 K-Nearest Neighbors (KNN)  
  - 🌳 Decision Tree Regressor  
  - 🌲 Random Forest Regressor  
  - 🚀 Gradient Boosting Regressor  
  - ⚡ **AdaBoost Regressor**  
  - 💥 **XGBoost Regressor**

---

## 🏆 Results

- 💯 **XGBoost Regressor** delivered the **best performance** with an **R² score of ~94%**, thanks to its ability to handle non-linearity, regularization, and ensemble learning.
- 🌲 **Random Forest Regressor** also performed well, striking a strong balance between **bias and variance**.
- 🚀 **Gradient Boosting** was competitive, gradually improving residuals over iterations.
- ⚡ **AdaBoost** showed moderate performance but fell behind the other ensemble models.
- 🔵🔴 **Ridge and Lasso** (regularized linear models) helped control overfitting but were less powerful compared to tree-based models.
- 📐 **KNN** and **Linear Regression** underperformed due to their limitations in capturing non-linear relationships.

---

## 📌 Key Learnings

- Tree-based ensemble models are generally more effective for structured/tabular data.
- Boosting techniques (like XGBoost and Gradient Boosting) often outperform bagging models (like Random Forest) when properly tuned.
- Regularization techniques (Ridge, Lasso) are useful for avoiding overfitting in simpler models.
- **Hyperparameter tuning and feature engineering** play a crucial role in improving model performance.
