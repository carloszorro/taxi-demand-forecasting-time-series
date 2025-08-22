# ⏱️ Taxi Demand Forecasting with Time Series  

> Built a time series forecasting model to predict hourly taxi demand for Sweet Lift Taxi, achieving RMSE < 48.  

✅ Español: Modelo de series temporales para predecir la demanda horaria de taxis en aeropuertos, alcanzando un RMSE < 48 para Sweet Lift Taxi. 

## 📊 Project Overview  
This project is part of the **Sprint 15: Time Series** module at TripleTen Latam.  
The objective was to support **Sweet Lift Taxi** by predicting the number of taxi orders for the next hour, allowing the company to optimize driver availability during peak hours.  

---

## 🛠️ Tasks Completed  
- Downloaded and resampled raw order data into 1-hour intervals.  
- Conducted exploratory data analysis (EDA) to identify demand trends and seasonality patterns.  
- Built and compared multiple forecasting models with hyperparameter tuning:  
  - Linear Regression with lag features  
  - Random Forest Regressor  
  - Gradient Boosting Regressor  
- Evaluated models on a 10% hold-out test set.  
- Selected the model with the lowest RMSE (<48).  

---

## 📂 Dataset Description  
Data contained historical records of taxi orders with timestamps.  
Key steps:  
- Resampling into hourly intervals  
- Creating lag features for demand forecasting  
- Splitting into training and test sets (90% / 10%)  

---

## 🚀 Tools & Technologies  
- Python  
- Pandas, NumPy  
- Scikit-learn (Regression models, metrics)  
- Matplotlib for visualization  
- Time series feature engineering  

---

## 📈 Results  
- Developed and validated a time series model achieving **RMSE < 48** on the test set.  
- Identified peak-hour demand patterns to support driver allocation.  
- Provided a reproducible workflow for forecasting short-term demand in mobility services.  

---

## 📫 Contact  
If you want to discuss this project, connect with me on [LinkedIn](https://www.linkedin.com/in/carlos-sanchez-zorro-data). 
