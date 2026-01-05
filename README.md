# 🌦️ Exploratory Data Analysis of Weather Data

## 📌 Project Overview

This project performs a **comprehensive Exploratory Data Analysis (EDA)** on real-world hourly weather data to identify **patterns, trends, and relationships** among key atmospheric variables such as temperature, wind speed, air pressure, visibility, humidity, and weather conditions. The analysis demonstrates practical data cleaning, visualization, and analytical reasoning skills relevant to data analyst roles.

---

## 🎯 Objective

* Understand dominant weather conditions and their frequency
* Analyze distributions of temperature, wind speed, and visibility
* Identify seasonal and time-based trends
* Explore relationships between weather variables
* Identify dominant weather patterns and seasonal trends from hourly weather data


---

## 📂 Dataset

* **Source:** Real-world hourly weather dataset (CSV format)
* **Records:** 8,784 hourly observations (~1 year)
* **Nature:** Time-series, mixed data types, includes missing values

### 🔑 Key Columns

| Column           | Description                     |
| ---------------- | ------------------------------- |
| Date/Time        | Timestamp of observation        |
| Temp_C           | Temperature (°C)                |
| Dew Point Temp_C | Dew point temperature (°C)      |
| Rel Hum_%        | Relative humidity (%)           |
| Wind Speed_km/h  | Wind speed (km/h)               |
| Visibility_km    | Visibility distance (km)        |
| Press_kPa        | Atmospheric pressure (kPa)      |
| Weather          | Weather condition (categorical) |

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – data cleaning and manipulation
* **NumPy** – numerical computations
* **Matplotlib & Seaborn** – data visualization
* **Jupyter Notebook** – analysis and reporting

---

## 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed:

* Converted `Date/Time` to proper datetime format
* Checked and handled missing values
* Standardized column names
* Removed duplicate records 
* Created time-based features where necessary (month, season)

---

## 📊 Exploratory Data Analysis (EDA)

The analysis includes the following visualizations and analytical questions:

1. **Top 10 Most Frequent Weather Conditions**
   → Which weather conditions dominate the dataset?

2. **Wind Speed Distribution (Histogram & Boxplot)**
   → What is the typical wind speed range? Are there extreme values?
   ![image alt](https://github.com/ajmul-haq/Weather-Data-Analysis/blob/main/Images/%20wind%20speed%20distribution.png?raw=true)

4. **Temperature Distribution & Boxplot**
   → How is temperature distributed and are there outliers?

5. **Temperature Trend Over Time**
   → Are there observable seasonal patterns?
   ![image alt](https://github.com/ajmul-haq/Weather-Data-Analysis/blob/main/Images/temperature%20trend.png?raw=true)

7. **Air Pressure Trend Over Time**
   → Is air pressure generally stable or volatile?

8. **Scatter Plot: Wind Speed vs Visibility**
   → Does wind speed influence visibility?

9. **Mean Visibility by Weather Condition**
   → Which weather conditions reduce visibility the most?

---

## 🔍 Key Takeaways

* Weather conditions are **predominantly stable**, dominated by clear and cloudy days.
* Wind speeds are generally **mild to moderate (5–25 km/h)**, with rare extreme events.
* Temperature exhibits **clear seasonal trends**, with moderate values most frequent.
* Visibility remains high in most cases and shows **no strong correlation with wind speed**.
* Air pressure is largely stable, with occasional short-term fluctuations.

---

## 📌 Key Findings

* Clear, Mainly Clear, and Cloudy conditions occur most frequently.
* Extreme weather events (high wind, low visibility, pressure drops) are uncommon.
* Seasonal variation is clearly visible in temperature trends.
* Weather data is well-suited for trend and pattern analysis.

---

## ⚠️ Limitations

* Data represents a **single location and time period**.
* Some weather variables (e.g., precipitation amount, solar radiation) are not included.
* Missing values may slightly affect precision.
* Analysis is exploratory; **no predictive modeling** is performed.

---

## ✅ Conclusion

This project demonstrates the effective use of **exploratory data analysis techniques** on real-world weather data. The findings highlight a **predominantly stable climate with clear seasonal behavior**, showcasing practical skills in data cleaning, visualization, and insight generation. The analysis also provides a strong foundation for future work such as **forecasting, correlation modeling, or dashboard development**.

---

📬 Contact

Author: Ajmul Haq
Role: Aspiring Data Analyst
LinkedIn: [linkedin](www.linkedin.com/in/mohammad-ajmul-haq-bhuiyan-566260194)
GitHub: [github](https://github.com/ajmul-haq/)

---


