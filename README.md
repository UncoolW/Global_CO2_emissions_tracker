# 🌍 Global CO₂ Emissions Tracker
This project analyzes and visualizes global carbon emissions across countries, years, and sectors using data from Our World in Data.
It was completed as part of a 2-week data analytics internship and includes ETL in Python and interactive dashboards in Tableau.
This project tracks global carbon emissions across countries and sectors using data from [Our World in Data](https://github.com/owid/co2-data).  
Built as part of my project for visualizing and analyzing real-world emissions data.

---

## 🎯 Objective

- Analyze CO₂ emissions trends across time, geography, and sectors
- Prepare a cleaned dataset suitable for visual dashboards
- Build a Tableau dashboard for global climate insights 
- Track CO₂ emission trends globally across time and fuel type
- To highlight key emission insights and polluters
- Present storytelling visuals to support targeted climate policy conversations

---

##  🔄 ETL Summary (Phase 1 – Complete)
- Filtered dataset to post-2000 records
- Dropped irrelevant and >50% null columns
- Recalculated co2_per_capita and co2_per_gdp using valid population/GDP
- Imputed missing fuel CO₂ values using country medians, fallback: global median
- Exported final cleaned CSV for Tableau

---

##  📁 Files:

emissions_raw.csv — Original downloaded OWID dataset

cleaned_emissions_data.csv — Final cleaned dataset

global_co2_etl.ipynb — ETL Jupyter notebook with step-by-step cleaning logic

##  📊 Dashboard Summary (Phase 2 – Complete)

Developed in Tableau Public with multiple sheets & views:

Line Chart: Top 10 CO₂ emitters over time
Map View: Country-level emissions with color scale
Bar Chart: Fuel-based CO₂ emissions by country
Pie Chart: Proportions of CO₂ by fuel type globally

 Filters applied: Country, Year, Fuel Type
 Color-coded visual storytelling, annotations & calculated fields used

 File: Global CO2 Tracker.twbx (Tableau Packaged Workbook)
 Dashboard Screenshot: dashboard_screenshot.png

---

##  🔍 Key Insights
🌐 Global emissions dipped in 2020 (COVID-19) but quickly rebounded
🌏 China, US, and India = 50%+ of global CO₂
🔥 Coal remains the largest polluting fuel
🌡️ Fuel mix varies: China → coal, US → oil, Russia → gas
🧩 Conclusion: Effective climate action needs targeted country-level insights
 Full summary in: insights.txt and project report PDF

##  🛠 Tools Used

Python (Pandas, NumPy) – data cleaning & feature engineering
Jupyter Notebook – ETL walkthrough
Tableau Public – dashboard & visual analysis
Excel CSV – data format standardization

##  📜 Citation and License

Dataset Source:
- Our World in Data (OWID) – CO₂ and Greenhouse Gas Emissions Dataset.
https://github.com/owid/co2-data
- Citation: Hannah Ritchie and Max Roser (2024) – "CO₂ and Greenhouse Gas Emissions". Published online at OurWorldInData.org.
- Licensed under Creative Commons BY 4.0.