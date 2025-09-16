# Weather Dataset — Exploratory Data Analysis (EDA)

This project explores hourly Toronto weather readings for **2012** through pandas-based exploratory data analysis (EDA).  
The focus is on understanding dataset structure, assessing quality, and answering practical questions such as how often it was *Clear*, what wind speeds were observed, and identifying conditions like snow or fog.

---

## 📦 Data Overview

- **Rows & Columns:** 8,784 rows × 8 columns  
- **Columns:** Date/Time, Temp_C, Dew Point Temp_C, Rel Hum_%, Wind Speed_km/h, Visibility_km, Press_kPa, Weather  
- **Unique Weather Conditions:** 50  
- **Unique Wind Speeds:** 34  
- **Missing Values:** None  

---

## 🔍 Key Insights

- **Weather Conditions:**  
  - Most frequent: *Mainly Clear* (2,106 times), *Mostly Cloudy* (2,069 times), *Cloudy* (1,728 times).  
  - Weather was exactly *Clear* on 1,326 occasions.  

- **Wind Speeds:**  
  - 34 distinct wind speeds recorded, with 4 km/h appearing 474 times.  

- **Visibility:**  
  - Average visibility was ~27.66 km.  

- **Humidity:**  
  - Relative humidity variance: ~286.25.  

- **Snow Events:**  
  - 390 rows had exactly *Snow*.  
  - 583 rows contained “Snow” in any form (e.g., *Snow Showers*, *Snow, Fog*).  

- **Fog Events:**  
  - 150 rows were recorded with *Fog*.  

- **Condition Combinations:**  
  - 308 rows had wind speed > 24 km/h and visibility = 25 km.  
  - 2,921 rows matched either: *Clear* with humidity > 50%, or visibility > 40 km.  

---

## 📊 Aggregations

- **Means by Weather Condition:**  
  Each condition had distinct averages for temperature, dew point, humidity, wind speed, visibility, and pressure.  
  - Example:  
    - *Clear:* Avg Temp ~6.8°C, Humidity ~64%, Wind Speed ~10.5 km/h.  
    - *Mainly Clear:* Avg Temp ~12.6°C, Visibility ~34.2 km.  
    - *Snow:* Avg Temp ~-4.5°C, Humidity ~79%.  

- **Min/Max by Weather Condition:**  
  - *Clear:* Min temp -23.3°C, Max temp 32.8°C.  
  - *Cloudy:* Min temp -21.4°C, Max temp 30.5°C.  
  - *Snow:* Min temp -16.7°C, Max temp 3.7°C.  

---

## 📈 Potential Extensions

- Trend analysis by month and hour (e.g., seasonal temperatures, humidity).  
- Comparing pressure/visibility changes with specific weather conditions.  
- Visualization of snow, fog, and rain distributions over time.  

---

## 👤 Author

**Mohammed Atif Syed Ali**  
MS IT @ Arizona State University • SQL • Python • Power BI • Data Analysis

