# Weather-Report-via-Free-API
Dynamic weather dashboard built in Power BI using real-time API data. It shows temperature, AQI, wind, and forecasts with interactive visuals, DAX measures, and Power Query for efficient data modeling.
# 🌦️ Power BI Weather Dashboard

## 📌 Overview
This project is an interactive Weather Dashboard built using Power BI, integrating real-time data from a weather API. It provides comprehensive insights into current weather conditions, air quality index (AQI), and future forecasts in a visually appealing and user-friendly format.

---

## 🚀 Features
- 🌡️ Real-time temperature and weather conditions
- 🌬️ Wind speed, humidity, pressure, and visibility tracking
- 📊 Air Quality Index (AQI) with dynamic status and color indicators
- 📅 7-day weather forecast with trend visualization
- 🌅 Sunrise and Sunset timings
- 🌧️ Chances of rain analysis
- 🎯 Interactive and modern UI design

---
## 🔗 Data Source

This project uses real-time data from the WeatherAPI:

Base API Endpoint:
http://api.weatherapi.com/v1/forecast.json

### 🌍 Cities Used

Below are the sample API endpoints used in this project:

#### 📍 New Delhi
http://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=New Delhi&days=7&aqi=yes&alerts=no

#### 📍 Lucknow
http://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=Lucknow&days=7&aqi=yes&alerts=no

#### 📍 Shimla
http://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=Shimla&days=7&aqi=yes&alerts=no

#### 📍 Hyderabad
http://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=Hyderabad&days=7&aqi=yes&alerts=no

#### 📍 Kanpur
http://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=Kanpur&days=7&aqi=yes&alerts=no

#### 📍 Jammu
http://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=Jammu&days=7&aqi=yes&alerts=no

---

## 📊 Dashboard Highlights
- KPI Cards for quick insights
- Line charts for forecast trends
- Gauge chart for AQI visualization
- Conditional formatting based on AQI levels
- Dynamic text and color measures using DAX

---

## 🛠️ Tools & Technologies
- Power BI Desktop
- Power Query (Data Transformation)
- DAX (Data Analysis Expressions)
- Weather API (Data Source)

---

## ⚙️ Data Processing
- Data extracted from Weather API
- Cleaned and transformed using Power Query
- Handled inconsistent values (e.g., "No moonset")
- Created calculated measures using DAX for insights

---

## 📈 Key Metrics
- Temperature (°C)
- AQI (PM10, PM2.5, NO2, SO2, CO, O3)
- Wind Speed (Kph)
- Humidity (%)
- Pressure
- Visibility

---

## 🧠 Insights
- Real-time environmental conditions monitoring
- AQI-based health suggestions
- Weather trends for better planning
- Clean and intuitive data storytelling

---

## 📷 Dashboard Preview
(Add your screenshot here)

---

## 📂 Project Files
- `.pbix` file (Power BI report)
- README.md

---

## ⚠️ Limitations
- Real-time streaming not fully supported (uses scheduled refresh)
- API limitations based on free tier

---

## 🔮 Future Improvements
- Real-time streaming integration
- Mobile optimization
- Advanced forecasting analytics
- Alerts & notifications system

---

## 👤 Author
Mohammad Asjad Khan
