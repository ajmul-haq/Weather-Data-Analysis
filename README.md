# 🌦️ Exploratory Data Analysis of Weather Data

## 📌 Project Overview

This project performs a **focused Exploratory Data Analysis (EDA)** on real-world **hourly weather data** to identify dominant patterns, seasonal trends, and relationships among key atmospheric variables such as temperature, wind speed, visibility, and weather conditions.
The project is designed as a **portfolio-ready analysis**, emphasizing clarity, insight generation, and effective visualization rather than excessive charting.

---

## 🎯 Objective

* Identify dominant weather conditions and their frequency
* Analyze distributions of key variables such as temperature and wind speed
* Detect seasonal and time-based temperature trends
* Explore relationships between selected weather variables

---

## 📂 Dataset

* **Source:** Real-world hourly weather dataset (CSV format)
* **Records:** 8,784 hourly observations (~1 year)
* **Type:** Time-series data with mixed numeric and categorical variables

### 🔑 Key Columns

| Column          | Description                     |
| --------------- | ------------------------------- |
| Date/Time       | Timestamp of observation        |
| Temp_C          | Temperature (°C)                |
| Wind Speed_km/h | Wind speed (km/h)               |
| Visibility_km   | Visibility distance (km)        |
| Press_kPa       | Atmospheric pressure (kPa)      |
| Weather         | Weather condition (categorical) |

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – data cleaning and manipulation
* **NumPy** – numerical operations
* **Matplotlib & Seaborn** – data visualization
* **Jupyter Notebook** – analysis and reporting

---

## 🧹 Data Cleaning & Preparation

* Converted `Date/Time` to proper datetime format
* Handled missing values and duplicates
* Standardized column names
* Created time-based features (month, season)

---

## 📊 Key Exploratory Analysis & Visualizations

### 1️⃣ Top 10 Most Frequent Weather Conditions

**Insight:** The dataset is dominated by clear and cloudy conditions, indicating generally stable weather throughout the year.

![Top Weather Conditions](https://github.com/ajmul-haq/Weather-Data-Analysis/blob/main/Images/top%20weather%20conditions.png?raw=true)

---

### 2️⃣ Wind Speed Distribution

**Insight:** Wind speeds are mostly mild to moderate (5–25 km/h), with rare high-wind events.

![Wind Speed Distribution](https://github.com/ajmul-haq/Weather-Data-Analysis/blob/main/Images/%20wind%20speed%20distribution.png?raw=true)

---

### 3️⃣ Temperature Trend Over Time

**Insight:** Temperature shows a clear seasonal pattern, rising toward mid-year and declining afterward.

![Temperature Trend](https://github.com/ajmul-haq/Weather-Data-Analysis/blob/main/Images/temperature%20trend.png?raw=true))

---

### 4️⃣ Wind Speed vs Visibility

**Insight:** Visibility remains high across most wind speeds, showing no strong linear relationship.

![Wind vs Visibility](https://github.com/ajmul-haq/Weather-Data-Analysis/blob/main/Images/Wind%20Speed%20vs%20Visibility.png?raw=true)

---

## 🔍 Key Takeaways

* Weather conditions are predominantly **clear or cloudy**, indicating stable climate behavior
* Wind conditions are generally calm to moderate, with few extreme events
* Temperature exhibits strong **seasonal variation**
* Visibility is largely unaffected by changes in wind speed

---

## 📌 Key Findings

* Extreme weather events are uncommon in the dataset
* Time-series analysis effectively reveals seasonal behavior
* The data is well-suited for exploratory and descriptive analysis

---

## ⚠️ Limitations

* Data represents a **single location and time period**
* Some atmospheric variables are not included
* Analysis is exploratory; no predictive modeling is performed

---

## ✅ Conclusion

This project demonstrates a **clean and insight-driven EDA workflow** using real-world weather data. By focusing on a small set of high-impact visualizations, the analysis highlights meaningful climate patterns while maintaining clarity and readability. The project provides a solid foundation for future extensions such as forecasting, correlation modeling, or dashboard development.

---

## 📬 Author

**Ajmul Haq**
Aspiring Data Analyst

---

📬 Contact

Author: Ajmul Haq
Role: Aspiring Data Analyst
LinkedIn: [linkedin](www.linkedin.com/in/mohammad-ajmul-haq-bhuiyan-566260194)
GitHub: [github](https://github.com/ajmul-haq/)

---


