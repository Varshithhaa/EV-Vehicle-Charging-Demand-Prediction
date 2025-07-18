# 🚗 EV Adoption Forecasting Using Machine Learning

This project uses machine learning to **forecast the growth of electric vehicle (EV) adoption** in Washington State based on **historical registration trends**.  
By applying regression techniques to data from 2017 to 2024, the model helps predict **future EV demand**, enabling better planning for **charging infrastructure** and policy decisions.

---

## 🧠 Problem Statement

As the number of electric vehicles grows rapidly, city planners and policymakers face the challenge of providing sufficient infrastructure.  
Without proper forecasting, EV users may experience delays, and sustainability goals may be compromised.

This project aims to:
- Analyze **monthly EV registration trends** by county
- Predict future EV adoption levels using **regression models**
- Highlight high-growth areas that may require **additional charging stations**

---

## 🎯 Objectives

- 📈 Predict the number of registered EVs (BEVs, PHEVs, and total) by county and month/year  
- 🔍 Analyze historical **EV growth patterns** and **regional trends**  
- 🧪 Evaluate regression model performance using key metrics  
- 💡 Provide insights into **charging demand** and **infrastructure planning**

---

## 📂 Dataset

- **Source**: Washington State Department of Licensing (DOL)  
- **Time Range**: January 2017 – February 2024  
- **Key Fields**:
  - `Date` – Monthly vehicle registration snapshot  
  - `County` – Region of vehicle registration  
  - `Vehicle Primary Use` – Passenger or Truck  
  - `BEVs`, `PHEVs`, `EV Total`, `Non-EV Total`, `Total Vehicles`, `Percent EV`  

- 📥 Dataset Link: [Kaggle – Electric Vehicle Population Size 2024](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024/data)

---

## 🛠️ Technologies & Libraries Used

### 📊 Data Processing & Machine Learning
- **Python** – Core programming language  
- **Pandas**, **NumPy** – Data cleaning and manipulation  
- **Scikit-learn** – Linear Regression, Decision Trees, XGBoost  
- **Joblib** – For saving trained models  
- **TimeSeriesSplit** – Cross-validation for time-based data  

### 📉 Model Evaluation
- `MAE` (Mean Absolute Error)  
- `RMSE` (Root Mean Squared Error)  
- `R²` (Coefficient of Determination)  

### 📍 Visualization
- **Matplotlib**, **Seaborn** – Trend plots, correlation heatmaps  
- **Folium / GeoPandas** *(optional)* – Geographic heatmaps of EV growth  

---



