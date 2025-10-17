# Personal Productivity & Performance Tracker

<p align="center">
  <img src="/personalT.png" alt="Personal Productivity Dashboard" width="">
</p>


📊  1. Project Background & Overview

The Personal Productivity & Performance Tracker was developed to analyze daily habits and optimize productivity. Traditionally, manual to-do lists and monthly habit reviews make it challenging to identify patterns or analyze trends effectively. To address this, a dynamic dashboard was created to centralize daily, weekly, monthly, and all-time metrics in one place.

The dashboard focuses primarily on descriptive analytics, enabling the monitoring of the health of habits over different time periods through automated data cleaning, aggregation, and visualization. By tracking these metrics dynamically, the dashboard provides actionable insights that support data-driven decisions to continuously improve productivity.


Insights and recommendations are generated in the following key areas:

* **Time Series Analysis** (Daily, Weekly, Monthly, All-Time): Evaluates trends and patterns in key metrics by examining average values, cumulative totals, longest streaks, and consistency over time, and comparing performance against targets and moving averages.

* **Performance Benchmarking**: Compares current performance against personal goals or targets and analyzes month-over-month improvements to measure progress and identify areas for optimization.

* **Visualization & Dashboarding**: Uses charts, tables, and conditional formatting to highlight trends, outliers, streaks, and progress dynamically over different time periods.


- A dynamic Google Sheet dashboard can be viewed (here)


- The formulas used for descriptive analysis are documented (here)
_________________________________________________________________________________

## 2. Data Structure Overview

The dataset is organized into four main tables:
- Raw_Data – Contains the original, unprocessed data.-
- Helper_Columns – Includes additional engineered columns created to support calculations and visualizations.
- Calculations – Performs all the analysis and contains pre-aggregated values and computed metrics that serve as the foundation for the dashboard
- Dashboard – Consolidates the final, ready-to-visualize metrics for reporting and analysis.

In total, the analysis focuses on 11 primary metrics
1. Sleep
2. Planning the Day
3. Workout
4. Joirnaling
5. Deep Work
6. Steps
7. Daily Weight
8. Calory Defecit
9. Screen Time
10. Read Pages
11.  Diet Followed


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







