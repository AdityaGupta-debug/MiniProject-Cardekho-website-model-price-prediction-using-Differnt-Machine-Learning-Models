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
- 📊 Performed Exploratory Data Analysis (EDA)  
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

- ✅ **XGBoost Regressor** gave the **best performance** with approximately **94% accuracy** (R² score), thanks to its ability to handle non-linearity, regularization, and boosting power.
- 🌲 **Random Forest** was also strong, striking a great balance between **bias and variance**.
- 🚀 **Gradient Boosting** closely followed, performing well by improving residuals iteratively.
- ⚡ **AdaBoost** showed decent accuracy but underperformed compared to Random Forest and XGBoost.
- 🧩 Regularized models like Ridge and Lasso helped reduce overfitting but weren’t top performers.
- 📍 KNN and Linear Regression were the weakest due to their limitations in capturing non-linearities.

---

## 📌 Key Learnings

- Tree-based ensemble models are generally more powerful for structured tabular data.
- Boosting algorithms (like XGBoost and Gradient Boosting) can outperform bagging (like Random Forest) with proper tuning.
- Regularization (Ridge, Lasso) is helpful but may not always outperform more complex models.
- Feature engineering and EDA significantly affect model performance.

---

## 📂 Folder Structure

