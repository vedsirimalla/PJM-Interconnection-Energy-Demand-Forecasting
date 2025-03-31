# PJM Interconnection Energy Demand Forecasting

## 📌 Project Overview
This project focuses on energy demand forecasting using the **PJM Interconnection (PJME & PJMW) hourly datasets**. PJM is a regional transmission organization in the United States that manages electricity distribution across multiple states. The dataset consists of **178,000+ records** from **January 2002 to August 2018**, providing valuable insights into historical energy consumption trends.  

Our analysis explores **seasonal patterns, correlations, and statistical insights** to develop accurate forecasting models that help in efficient energy distribution and planning.

## 📌 Introduction
The goal of this project is to analyze and forecast energy consumption patterns for **PJM East (PJME) and PJM West (PJMW)**. This is essential for:
- **Predicting future energy demand** for efficient power distribution.
- **Identifying seasonal consumption trends** affecting peak energy loads.
- **Analyzing historical consumption fluctuations** and correlations.
  
---

## 📂 Dataset Description
- **Source:** PJM website
- **Timeframe:** January 2002 - August 2018
- **Records:** ~178,000 hourly energy consumption entries
- **Regions Covered:** Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, District of Columbia
- **Key Variables:**
  - **PJME Consumption (MW)**
  - **PJMW Consumption (MW)**
  - **Hourly, Daily, Monthly Trends**
  - **Temperature & Seasonal Impact**
  
---

## 📈 Exploratory Data Analysis
### 🔹 Histogram Plots
- The distribution of hourly energy consumption follows a **bell-shaped curve**, indicating **normality**.
- **PJME has higher consumption (Mean: 32,080.5 MW) compared to PJMW (Mean: 5,602.4 MW)**.
- Seasonal patterns: **Winter > Summer > Spring > Fall**.

### 🔹 Time Series Plots
- **Increasing trend over time**, with periodic seasonal peaks.
- **PJME has higher volatility** due to industrial and commercial energy demands.
- **No long-term decreasing trend**, suggesting stable energy requirements over the years.

### 🔹 Scatter Plots
- **PJME shows greater variability** in energy usage compared to PJMW.
- **Seasonal fluctuations are more evident in PJME**, indicating its dependency on temperature variations.

### 🔹 Correlation Heatmap
- Weak **negative correlation** between months and energy consumption.
- Moderate **positive correlation** between hourly changes in PJME and PJMW consumption.

---

## 📊 Summary Statistics
- **Mean Energy Consumption:**
  - PJME: **32,080.5 MW**
  - PJMW: **5,602.4 MW**
- **Standard Deviation:**
  - PJME: **6,463.87 MW**
  - PJMW: **979.12 MW**
- **Box plots highlight seasonal variations and outliers**.

---

## 📉 Parameter Estimation
- Mean and standard deviation were calculated for both regions.
- **Daily, monthly, and yearly percentage shifts** in energy consumption were measured.

---

## 📊 Hypothesis Testing
- We conducted statistical tests to verify whether energy consumption differences between seasons were significant.

---

## 🔄 Correlation Analysis
- The correlation coefficients indicate a weak **negative correlation** between months and energy consumption.
- **Hourly energy changes show a moderate positive correlation** between PJME and PJMW.

---

## 📈 Model Building
We developed forecasting models using:
- **Time Series Analysis**
- **Linear Regression**
- **ARIMA Models**
- **Machine Learning Approaches (Random Forest, XGBoost)**

---

## 📌 Conclusion
- **Energy consumption is highly seasonal**, with peaks in **winter and summer**.
- **PJME has significantly higher consumption** and greater fluctuations compared to PJMW.
- **Predictive models were effective in forecasting future energy demands**, aiding in strategic power management.

---

## 🚀 Future Work
- **Improve forecasting models** using deep learning (LSTMs, GRUs).
- **Analyze external factors** like weather conditions, economic trends, and policy changes.
- **Deploy predictive models for real-time energy monitoring**.
