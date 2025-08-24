# 🚴‍♂️ Seoul Bike Sharing Demand Prediction

## 📌 Problem Statement
The goal of this project is to predict the **hourly demand for rented bikes** in Seoul based on various factors such as weather, seasons, holidays, and functioning days.  
Accurate predictions help optimize bike availability, reduce operational costs, and improve customer satisfaction.

---

## 📊 Dataset
- **Source:** Seoul Bike Sharing dataset  
- **Target Variable:** `Rented Bike Count`  
- **Features:**  
  - Temporal: Hour, Seasons, Holiday, Functioning Day  
  - Weather: Temperature (°C), Humidity (%), Wind speed (m/s), Visibility (10m), Dew point temperature (°C), Solar radiation (MJ/m2), Rainfall (mm), Snowfall (cm)

---

## 🔎 Exploratory Data Analysis (EDA)
- Distribution analysis of rentals across seasons, holidays, and hours.  
- Pair plots and correlation heatmaps to understand feature relationships.  
- Outlier treatment (Rainfall, Snowfall, Bike Count).  
- Feature transformations: log tra
