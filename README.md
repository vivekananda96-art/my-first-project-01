# my-first-project-01
In this project, you will analyze pharmaceutical sales data. Analysing sales data based on historical data is a very common data analysis task. This is a great way to start working with data science projects.

# Pharmaceutical Sales EDA & Excel Financial Modeling Project

A comprehensive repository and study package combining **Python-based Exploratory Data Analysis (EDA)** in Google Colab with **advanced Excel financial modeling and interview prep** using pharmaceutical and operational datasets.

---

## 🚀 Project Overview

This project bridges data science and financial analysis. It is designed to prepare professionals and analysts for Excel-intensive interviews and data-driven pharmaceutical market analysis. The project covers:
1. **Time-Series EDA in Python (Google Colab):** Analyzing daily pharmaceutical sales (`salesdaily.csv`) categorized by ATC (Anatomical Therapeutic Chemical) codes.
2. **Financial & Valuation Modeling in Excel:** Building DCF schedules, dynamic arrays, advanced lookup logic, and automated calculations for compound growth, discount factors, and enterprise value.

---

## 📂 Repository Structure

```text
├── salesdaily.csv                        # Raw pharmaceutical daily sales dataset
├── Excel_Interview_Practice_Workbook.xlsx # Excel practice workbook with interview tasks
├── colab_scripts.py                      # Python scripts for data extraction and EDA
└── README.md                             # Project documentation
```

---

## 📊 Key Python Analyses & Google Colab Scripts

The Python scripts utilize the `pandas` library to uncover trends in `salesdaily.csv`:

### 1. Total Sales Quantities by ATC Code
Aggregates total volume sold across different drug categories.
* **Top Category:** `N02BE` (Analgesics / Antipyretics) leads significantly with over 63,000 units sold.

### 2. Seasonality Trends (Respiratory Drugs - `R03`)
Analyzes monthly average daily sales to detect seasonal patterns.
* **Finding:** Respiratory drugs (`R03`) show peak demand during winter/autumn months (December: ~7.92 units/day, October, February, January) and lower sales in summer.

### 3. Sales Frequency & Daily Averages
Evaluates consistency of sales across active days in a given year (e.g., 2017 performance).

---

## 📈 Excel Modeling & Interview Guide

The practice workbooks cover high-frequency technical interview questions:
* **Modern Lookups:** Leveraging `XLOOKUP` for exact and resilient matching.
* **Multi-Criteria Array Lookups:** Combining `INDEX` and `MATCH` with boolean logic (`*` for logical AND).
* **Financial Calculations:**
  * **Compound Growth:** `=I2*(1+$B$1)`
  * **Discount Factor:** `=1/(1+$B$2)^(ROW()-1)`
  * **Enterprise Value / Present Value:** `=H2*J2` or cumulative `SUM` formulas.
* **Conditional Aggregations:** `SUMIF`, `COUNTIFS`, and dynamic `FILTER` arrays.

---

## 🛠️ Getting Started

### Running the Python Scripts in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `salesdaily.csv` file to your Colab session.
3. Paste and run the data aggregation snippets for category totals, monthly trends, or frequency analysis.

### Opening the Excel Workbook
1. Download `Excel_Interview_Practice_Workbook.xlsx`.
2. Review the `Practice Data` sheet to test your formula-building skills against the `Answers & Solutions` sheet.

---

## 📝 License
This project is open-source and intended for educational, interview preparation, and analytical demonstration purposes.
