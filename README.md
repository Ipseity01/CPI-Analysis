# CPI-Analysis
This project explores and analyzes India's Consumer Price Index (CPI) data, focusing on **inflation trends** across various **SubGroups**, **Sectors**, **States**, and **Years**.

---

## 📁 File Structure

- `CPI.ipynb` – Jupyter notebook containing all data cleaning, transformation, visualizations, and analytical code.

---

## 📌 Dataset Overview

The dataset includes CPI data with the following key columns:

- `Year` – Year of record (2013–2025)
- `Month` – Month of record
- `State` – Indian state or UT
- `Sector` – Urban or Rural
- `Group` – Broad category (e.g., Miscellaneous, Food)
- `SubGroup` – Specific category (e.g., Health, Education, Vegetables)
- `Index` – CPI index value
- `Inflation (%)` – Monthly inflation rate

---

## ✅ Key Tasks Performed

1. **Data Cleaning**
   - Replaced invalid inflation entries (`'*'`) with `NaN` and dropped them
   - Renamed ambiguous subgroup labels (like `*`) to `Other`
   - Converted numeric columns to appropriate datatypes

2. **Data Analysis**
   - Yearly and monthly inflation trend analysis
   - Sector-wise inflation comparison (Urban vs Rural)
   - State-wise average inflation ranking
   - SubGroup-wise average and volatility (std. dev) comparison
   - Health inflation tracking across pandemic years (esp. 2020)
   - Correlation matrix between subcategories for a given year

3. **Visualizations**
   - Line plots for inflation trends
   - Bar charts for SubGroup/State comparisons
   - Heatmaps for correlation analysis
   - Seasonal inflation analysis (month-wise)

---

## 🔍 Sample Insights

- Health inflation spiked in 2020, likely due to the COVID-19 pandemic.
- Urban areas show slightly higher average inflation than Rural areas in most years.
- Categories like Vegetables, Pulses, and Oils were among the most volatile.
