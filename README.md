# Productivity KPI Tracker Dashboard


<p align="center">
  <img src="/personalT.png" alt="Personal Productivity Dashboard" width="">
</p>


📊  1. Project Background & Overview

The **Productivity KPI Tracker Dashboard** was developed to analyze daily habits and optimize productivity. Traditionally, manual to-do lists and monthly habit reviews make it challenging to **identify patterns** and **analyze trends** effectively. To address this, a dynamic dashboard was created to centralize daily, weekly, monthly, and all-time metrics in one place.

The dashboard focuses primarily on **descriptive analytics**, enabling the monitoring of the health of habits over different time periods through automated **data cleaning**, **aggregation**, and **visualization**. By tracking these metrics **dynamically**, the dashboard provides **actionable insights** that support **data-driven** decisions to continuously improve **productivity**.


Insights and recommendations are generated in the following key areas:

* **Time Series Analysis** (Daily, Weekly, Monthly, All-Time): Evaluates trends and patterns in key metrics by examining **average values**, **cumulative totals**, **longest streaks**, and **consistency over time**, and comparing performance against **moving averages**.

* **Performance Benchmarking**: Compares current performance against **personal goals** or targets and analyzes month-over-month improvements to measure progress and identify areas for **optimization**.

* **Visualization & Dashboarding**: Uses charts, tables, and conditional formatting to highlight **trends**, **outliers**, **streaks**, and **progress dynamically** over different time periods.


📊 **Dynamic Dashboard:**  

- You can explore the live **Google Sheets dashboard** [here](https://docs.google.com/spreadsheets/d/1x-mhHTT8bQrLh7cjOE0KSys-MGb55SVAtPmmatN_ONQ/edit?gid=59886938#gid=59886938), which updates automatically based on the dataset.
- The formulas used for descriptive analysis are documented [here](https://docs.google.com/spreadsheets/d/1x-mhHTT8bQrLh7cjOE0KSys-MGb55SVAtPmmatN_ONQ/edit?gid=922938351#gid=922938351).

_________________________________________________________________________________

## 2. Data Structure Overview

The dataset is organized into four main tables:

- **Raw_Data** – contains the original, unprocessed data
- **Helper_Columns** – includes additional engineered columns created to support calculations and visualizations.
- **Calculations** – performs all the analysis and contains pre-aggregated values and computed metrics that serve as the foundation for the dashboard
- **Dashboard** – consolidates the final, ready-to-visualize metrics for reporting and analysis.

In total, the analysis focuses on 11 primary metrics:

1. sleep_in_h (time: 00:00)
2. planned_the_day (categorical:Yes/No)
3. workout (categorical:Yes/No)
4. journal (categorical:Yes/No)
5. deep_work_in_h (time: 00:00)
6. steps (float: 2.0)
7. daily_weight_in_kg (float: 2.0)
8. calory_deficit (float: 2.0) 
9. screen_time_in_h	(time: 00:00)
10. read_pages (integer: 0 ) 
11. diet_followed (categorical:Yes/No)

All other columns were derived through feature engineering, designed to streamline the calculation and visualization of these metrics within the dashboard.

Below, you can see the **Entity–Relationship Diagram (ERD)** of these tables:
<p align="center">
  <img src="/table_relationship.png" alt="Personal Productivity Dashboard" width="">
</p>

________________________________________________________________________________________________________________________

3. Executive summary 

Get here right into the juicy staff . 



4. Insight Deep Dive 

We talk about specific part of the executive summary and break down more specific finding into detail. 

5. Recommendation. 







