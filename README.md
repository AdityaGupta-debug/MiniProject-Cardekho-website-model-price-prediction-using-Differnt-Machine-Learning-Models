# 🚗 CarDekho Dataset - Price Prediction

This project focuses on predicting the **selling price of used cars** using various machine learning algorithms. By analyzing car features such as brand, year, fuel type, and more, we aim to estimate fair prices for vehicles in the Indian market. 🇮🇳

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

This dataset is ideal for practicing **regression techniques** and understanding how different features affect used car prices.

---

## 🎯 Objective

Build and evaluate multiple machine learning models to **predict the selling price** of used cars as accurately as possible.

---

## 🛠️ What I Did

- ✅ Data cleaning and preprocessing  
- 📊 Performed Exploratory Data Analysis (EDA) to understand feature relationships  
- 🏷️ Encoded categorical variables for ML compatibility  
- ⚖️ Handled missing values and outliers  
- 📈 Applied multiple regression algorithms:

  - 📐 Linear Regression  
  - 🔵 Ridge Regression (L2 Regularization)  
  - 🔴 Lasso Regression (L1 Regularization)  
  - 📍 K-Nearest Neighbors (KNN)  
  - 🌳 Decision Tree Regressor  
  - 🌲 Random Forest Regressor  

---

## 🏆 Result

The **Random Forest Regressor** delivered the best performance, offering the most accurate price predictions thanks to its ability to handle non-linearity and capture feature interactions effectively.

---

## 📌 Key Learnings

- 🧩 Regularized models like Ridge and Lasso helped reduce overfitting but didn’t outperform tree-based models  
- 🌴 Decision Trees were interpretable but prone to overfitting when used alone  
- 🌲 Random Forest struck the best balance between **bias and variance**, efficiently handling mixed data types and complex patterns
