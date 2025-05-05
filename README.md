# 🌍 Mini Project: Earthquake Perception Analysis (API-based EDA)

This project is part of the **mini_project_api_data_EDA** assignment and focuses on exploring how people perceive the intensity of earthquakes compared to their actual magnitude. The analysis uses data retrieved from the official **USGS Earthquake API**.

---

## 🔗 API Source

All data was collected via the **USGS Earthquake API**:  
📎 [https://earthquake.usgs.gov/fdsnws/event/1/query](https://earthquake.usgs.gov/fdsnws/event/1/query)

---

## 🎯 Project Theme

**Research Focus:**  
*How does the reported felt intensity (CDI) differ from the actual earthquake magnitude?*

The project investigates:
- Whether people tend to over- or underestimate earthquakes
- The relationship between earthquake magnitude and number of felt reports
- Patterns in reporting behavior and data quality issues

---

## 🛠️ Methods

- Data Cleaning (handling ~90% missing values in CDI/felt fields)
- Binning by magnitude (e.g. 4–5, 5–6, …)
- Descriptive Statistics
- Pearson's Correlation Coefficient
- Visualization: Histograms, Boxplots

---

## 📈 Key Findings

- **No clear correlation** between magnitude and number of people who felt the quake (Pearson's r ≈ 0.02)
- People tend to **overestimate** earthquake intensity on average (CDI > magnitude)
- Many outliers for moderate magnitudes → possibly due to location, depth, and population density
- Higher magnitudes showed fewer reports, possibly due to remote locations or reporting disruptions

---


---

## 💡 Author

*Fee Pieper*  
Mini Project – Exploratory Data Analysis from API Data  
Date: May 2025

---

