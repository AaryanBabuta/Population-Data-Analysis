# Population Data Analysis on Dataset By World Bank
# 🌍 World Bank Global Population Analysis (1960–2022)

## 📌 About
This project analyzes **global population trends** from **1960 to 2022** using official **World Bank** data.  
The analysis identifies the most and least populated countries per decade, examines long-term growth patterns, and explores regional demographic changes using Python data analysis and visualization tools.

---

## 📂 Dataset
- **Source**: [World Bank Open Data](https://data.worldbank.org/indicator/SP.POP.TOTL)
- **File**: `API_SP.POP.TOTL_DS2_en_csv_v2_45183.csv`
- **Coverage**: Population totals for over 260 countries and regions (1960–2022)
- **Format**: CSV (wide format, years as columns)

---

## 🛠 Tools & Libraries Used
- **Python** (Data Processing & Visualization)
- [Pandas](https://pandas.pydata.org/) – Data manipulation  
- [NumPy](https://numpy.org/) – Numerical operations  
- [Matplotlib](https://matplotlib.org/) – Data visualization  
- [Seaborn](https://seaborn.pydata.org/) – Statistical plots

---

## 📊 Analysis Workflow
1. **Data Import** – Read and load CSV file using Pandas.  
2. **Data Cleaning** – Remove non-country entries, handle missing values.  
3. **Reshaping** – Convert wide-format dataset to long-format for easier grouping.  
4. **Decade-Wise Ranking** – Identify top and bottom populated countries for each decade.  
5. **Regional Aggregation** – Summarize populations by region.  
6. **Visualization** – Generate line charts, bar plots, and heatmaps.

---

## 🔍 Key Insights
- **China & India** consistently lead as the most populated countries.  
- **Small island nations** like Tuvalu & Nauru remain least populated.  
- The **global population tripled** from ~3B in 1960 to over 7.9B in 2022.  
- **Africa** shows the **fastest population growth** in recent decades.

---

## 📈 Example Visualizations
- Decade-wise top & bottom populated countries.  
- Regional population share over time.  
- Country-specific population growth trends.  
