# Advance-EDA
# 🔌 Power Consumption vs Weather Analysis

This project explores the relationship between **household electricity usage** and **weather conditions** using statistical methods, visualizations, and machine learning techniques. By combining power consumption data with external weather factors like **temperature, humidity, and precipitation**, we aim to uncover how environmental factors influence energy demand.

---

## 📂 Project Overview

- **Goal**: Understand how weather impacts household electricity usage  
- **Approach**: Data merging, time-series analysis, correlation assessment, rolling averages, lag analysis, and unsupervised clustering  
- **Tools**: Python, pandas, seaborn, matplotlib, scikit-learn  

---

## 📈 Key Insights

- 📉 Power consumption **increases during colder temperatures**
- 🌡️ **Temperature** is the most significant environmental factor
- 💧 **Humidity** shows a weak positive relationship with power usage
- 🌧️ **Precipitation** has little to no direct impact
- 🔄 **Lag analysis** suggests temperature effects carry over to the next day
- 🤖 **Clustering** segmented days into 3 interpretable profiles:
  - Cold & Humid → Highest power usage
  - Mild & Rainy → Moderate usage
  - Warm & Dry → Lowest usage

---

## 📊 Visual Highlights

- 📌 Correlation Matrix of power and weather variables
- 🔄 Rolling averages for smoothed trend visualization
- 📉 Time-series plots (scaled & unscaled) for internal and external dependencies
- 📦 Boxplots comparing daily usage across weather clusters

---

## 📁 Files Included

- `powerVsWeather.ipynb` – Full Jupyter notebook with code and plots  
- `powerVsWeather_Report.md` – Markdown version of the full technical report  
- `Power Weather Ieee.pdf` – IEEE-style formatted final report *(optional export)*  
- `README.md` – Project summary for GitHub  

---

## 📌 Data Sources

- [UCI ML Repository - Household Power Consumption](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)  
- [Open-Meteo Archive API](https://open-meteo.com/) – Historical weather data for France  

---

## 🧠 Applications

- 📡 Smart grid forecasting  
- 📊 Dynamic pricing strategy design  
- 🏠 Weather-responsive energy automation systems
