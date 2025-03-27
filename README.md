# 🚗 Predicting Claims Costs Using FNOL Data

This repository presents a data analysis project focused on predicting insurance claims costs using First Notification of Loss (FNOL) data. The analysis centers around head-on collision claims, using historical data to uncover trends, evaluate influencing factors, and support better pricing and reserving strategies.

---

## 📊 Project Overview

The goal of this project is to explore the relationship between various FNOL features and final incurred claim costs. We used a combination of data cleaning, exploratory data analysis (EDA), and statistical techniques to surface actionable insights.

---

## 📁 Dataset

- **Type**: Insurance claims data for head-on collisions  
- **Time span**: Multiple years, enabling trend and seasonality analysis  
- **Features**: 45 variables, including:
  - Region of incident
  - Number of third parties involved
  - Type of road (motorway, main road, minor road)
  - Time-based information (month, season)
  - Notification and claim timing details

The dataset's depth and coverage make it suitable for understanding long-term trends and refining predictive models.

---

## 🧹 Data Cleaning

Cleaning was performed using **Tableau Prep**, addressing:

- Inconsistent formats and corrupted values (e.g., `"n/k"`, `"unknown"`)
- Duplicate entries
- Standardizing numerical variables such as `Notification Period` and `Inception to Loss`

---

## 🔍 Exploratory Data Analysis (EDA)

We used **Tableau** for visual EDA, uncovering patterns across regions, time periods, and claim complexity.

---

## 🧠 Key Insights

### 1. Regional Differences in Incurred Costs

- **Scotland** consistently shows the **highest average incurred costs**.
- **East Anglia** and **the North** also show **elevated costs**.
- **London**, **East Midlands**, and the **Southwest** show **lower average costs**.

These differences may relate to accident severity, claims handling practices, or environmental conditions.

---

### 2. Seasonality and Monthly Trends

- Higher average claim costs occur in **January–March**, likely due to:
  - Hazardous winter weather
  - Increased holiday traffic
- Costs fluctuate throughout the year, indicating **time-based risk factors**.

Understanding these patterns improves **forecasting and pricing accuracy**.

---

### 3. Third-Party Involvement

- Incurred costs **increase with the number of third parties** involved.
- A sharp rise is observed when **3 or more third parties** are involved.
- These complex cases, though less frequent, have a **high financial impact** and require **careful reserving**.

---

### 4. Impact of Road Type

- **Motorways** and **main roads** are associated with **higher average claim costs** due to:
  - Higher speeds
  - More severe accidents
- **Minor roads** show **more variability**, making outcomes **less predictable**.

| Road Type   | Avg. Incurred Cost | Cost Variability |
|-------------|---------------------|------------------|
| Motorways   | High                | Low              |
| Main Roads  | High                | High             |
| Minor Roads | Medium              | High             |

---

## 🧰 Tools Used

- **Tableau**: Data visualization and EDA
- **Tableau Prep**: Data cleaning and preparation
- **ChatGPT**: Statistical guidance and correlation analysis
- **Python (Optional)**: For advanced statistical exploration

---

## 📌 Conclusions

This project demonstrates how FNOL data, when properly cleaned and explored, can yield critical insights into cost drivers and risk patterns. These findings support more accurate:

- Reserving
- Pricing
- Operational planning
