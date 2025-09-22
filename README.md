# Personal-Performance-Analytics-Dashboard

📊 Project Overview

A Google Sheets dashboard that tracks and analyzes my personal productivity and performance metrics.

The project demonstrates my ability to **clean**, **structure**, and **visualize** data using **spreadsheet functions** and **dynamic scorecards and charts**.

## 🎯 Motivation

I built this project to:

Track my habits and performance over both the short and long term.

Practice data analysis with real personal data that reflects my life.

Gain insights to improve key metrics like productivity and consistency.

Blend self-tracking with a professional analytics approach to demonstrate skills relevant for a junior data analyst role.



## 🛠 Data & Tools

Data Source: Self-recorded daily performance metrics. 

**Main Metrics:**

1. Plan the Day – Yes/No (categorical)
2. Journaled – Yes/No (categorical)
3. Deep Work Hours – float
4. Daily Reading – float
5. Workout – Yes/No (categorical)
6. Steps – float
7. Diet Followed – Yes/No (categorical)
8. Weight (kg) – float
9. Calorie Deficit – float
10. Sleep – hh:mm (duration)
11. Screen Time – hh:mm (duration)

**Tools Used**

Google Sheets: data cleaning, formulas, pivot tables, conditional formatting.

- *Functions*:

**Aggregation**: COUNT, SUM, COUNTIF, SUMIF

**Statistical**: AVERAGE, AVERAGEIFS, MIN, MAX

**Filtering & Lookup**:   FILTER, INDEX, MATCH

**Date Functions**: ISOWEEKNUM, WEEKNUM, MONTH

**Visualizations**:  Area Charts, Bar Charts, Column Charts, Pie Charts, Trend Lines, Scorecards.



## Methodology

**Data Collection** : Recorded daily performance metrics over 18 weeks.

**Data Cleaning**:    Standardized inputs, ensured completeness, and created helper fields 
                       (e.g., extracting week numbers, months, and weekdays).
                       
**Analysis**:         Built calculated fields such as streaks, averages, percentages, cumulative totals, and actual vs. target comparisons.

**Visualization**:   Designed scorecards and charts including:

- Weekly and monthly averages
- Monthly cumulative values
- Moving averages for trend smoothing
- Actual vs. target comparisons
- Consistency rates (% of days habit completed)

**Monitoring & Diagnosis**: Used the dashboard to identify patterns, trends, and performance gaps, providing a clear picture of 
                            habit health over time.



## Skills Demonstrated

Data Preparation:        Cleaned inputs, structured raw data, and created helper fields (weeks, months, weekdays).

Statistical Techniques: Applied descriptive statistics (averages, percentages, min/max, cumulative totals) and time-series 
                        methods (moving averages, trend analysis).

Trend & Pattern Identification: Tracked weekly/monthly performance, consistency rates, and habit patterns across weekdays.

Target vs. Actual Analysis: Compared performance against goals to highlight progress and gaps.

Visualization: Converted metrics into clear scorecards and charts (bar, column, area, pie, trend lines) for easy interpretation.



## Dashboard

The link to the dynamic dashboard: 

https://docs.google.com/spreadsheets/d/1x-mhHTT8bQrLh7cjOE0KSys-MGb55SVAtPmmatN_ONQ/edit?gid=59886938#gid=59886938

## Key Insights

| Metric          | Type                 | Insight / Trend                                                                  |
| --------------- | -------------------- | -------------------------------------------------------------------------------- |
| Plan the Day    | Categorical (Yes/No) | Completed on \~70% of days; correlated with higher deep work hours               |
| Journaled       | Categorical (Yes/No) | Completed \~60% of days; higher reflection days coincide with better consistency |
| Deep Work Hours | Float                | Higher on weekdays; moving average shows upward trend                            |
| Daily Reading   | Float                | Averaged 30 min/day; peaks on weekends                                           |
| Workout         | Categorical (Yes/No) | Completed \~65% of days; weekends had highest consistency                        |
| Steps           | Float                | Averaged 8,500 steps/day; highest on weekends                                    |
| Diet Followed   | Categorical (Yes/No) | \~70% adherence; consistent with workout days                                    |
| Weight (kg)     | Float                | Minor fluctuations; downward trend over 4 months                                 |
| Calorie Deficit | Float                | Achieved on 60% of days; correlates with workout days                            |
| Sleep           | Duration (hh\:mm)    | Averaged 7:30h; shorter on weekdays                                              |
| Screen Time     | Duration (hh\:mm)    | Decreasing trend; lowest on weekends                                             |



## Next Steps

Expand the dataset beyond the initial 4-month period to track longer-term trends.

Incorporate deeper statistical analysis, including correlations between metrics and more advanced KPIs.

Enhance the dashboard with predictive elements and automated updates to make it more actionable.

Refine visualizations and scorecards based on ongoing insights and usability improvements.


