# 🗳️ Elections Ad Spending Analysis (India General Elections 2024)

## 📌 Project Overview

This project analyses the **advertising expenditure** by political parties across Indian states and union territories during the **2024 General Elections**, and investigates its correlation with **voter turnout**. The aim is to explore whether campaign ad spending influenced public participation.

---

## 🧰 Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis  
- **NumPy** – Numerical operations  
- **Plotly** – Interactive data visualization  
- **Jupyter Notebook** – Data analysis and experimentation  
- **CSV Files** – Source data format

---

## 📁 Dataset Description

The analysis is based on three datasets:

| File Name         | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `advertisers.csv` | Contains political party names, advertiser info, and total ad expenditure   |
| `locations.csv`   | State-wise advertising amount spent                                         |
| `results.csv`     | Election results including voter turnout (Polled %) per state               |

---

## 🧹 Data Cleaning

- Standardized state/UT names using `str.strip()` and `str.title()`
- Ensured numeric consistency by converting ad spend and voter turnout columns to appropriate data types
- Merged datasets on `State` column to align ad spend with voter turnout

---

## 📊 Key Visualizations

### 1. Total Ad Spend by State
- **Bar chart** showing states with the highest ad spend
- Example insight: *Uttar Pradesh*, *Maharashtra*, and *Odisha* had the largest spending

### 2. Average Voter Turnout by State
- **Bar chart** visualising states with the highest public engagement
- Example insight: *Lakshadweep*, *Tripura*, and *Assam* showed highest voter turnout

---

## 🎯 Objectives

- Examine how political parties distributed their ad budgets geographically
- Identify trends and patterns in voter turnout
- Correlate ad spend with turnout to derive potential insights

---

## 📈 Future Enhancements

- Add **correlation matrix** or **regression analysis** between ad spend and turnout
- Perform **sentiment analysis** using ad content (if available)
- Build an **interactive dashboard** using Streamlit or Looker Studio
- Schedule automatic data updates and visualisations

---
