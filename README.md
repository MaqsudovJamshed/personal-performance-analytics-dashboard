# Productivity KPI Tracker Dashboard


<p align="center">
  <img src="/personalT.png" alt="Personal Productivity Dashboard" width="">
</p>


# Project Background & Overview

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

# Data Structure Overview

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
# Executive summary
### Overview & Key Findings

This dashboard presents an analytical summary of my personal productivity KPIs, designed to measure daily performance, consistency, and behavioral trends across key habit areas.
Each metric is evaluated based on Consistency %, Gap vs Target, Average Value, Rank, and Longest Streak, allowing for a clear understanding of which habits are most stable and which require improvement.

You can explore the executive summary in a dynamic google sheets [here](https://docs.google.com/spreadsheets/d/1x-mhHTT8bQrLh7cjOE0KSys-MGb55SVAtPmmatN_ONQ/edit?gid=1214931430#gid=1214931430)

<p align="center">
  <img src="/Executive_sum_project.png" alt="Personal Productivity Dashboard" width="">
</p> 

***High Consistency Areas***:

* **Sleep (88.3%)** and **Daily Weight Tracking (78.3%)** show the strongest consistency, reflecting well-established daily routines and disciplined monitoring habits.
* **Steps(62.8%)** and **Diet Followed (62.3%)** indicate steady adherence to physical activity and nutritional goals.

***Moderate Consistency Areas***:

* **Journaling (55.7%)** and **Planning (53.9%)** demonstrate moderate consistency, suggesting good structure in daily planning and reflection but with room for more regular execution.
* **Deep Work (40.9%)** and **Pages Read (42.1%)** show partial alignment with productivity goals, indicating fluctuations in focus and knowledge-building routines.
  
 ***Low Consistency Areas***:

* **Workout(34.9%)**, **Calorie Deficit (36.5%)**, and **Screen Time(8.2%)** display the largest deviation from targets, representing the key opportunities for behavioral improvement.
* In particular, screen time management and workout regularity show the greatest potential for optimization.

The data suggests that habits supported by structure and measurable feedback (e.g., sleep, tracking weight) exhibit higher consistency, while those requiring high activation energy or impulse control (e.g., workouts, screen time reduction) are less stable.

________________________________________________________________________________________________________________________________________________________________________________________

## 4. Insight Deep Dive 

________________________________________________________________________________________________________________________________________________________________________________________
1. **PLAN THE DAY**

<p align="center">
  <img src="/plan.png " alt="Personal Productivity Dashboard" width="800">
</p>
 
**Trends**

* ***Weekly Trend***: On average, **4** of 7 days were **planned** each week. Out of 23 weeks, only **3 reached full planning**, showing **moderate consistency** with **occasional peaks**.
* ***Monthly Average***: The trend is stabilizing, with an **average of 17 planned** days per month. Planning improved notably from July (10 days) to August (23 days),
then **slightly decreased** to 20 days in September–October.
* ***All-Time Consistency***: Between June and October, 87 of 160 days were planned (57% consistency), indicating **moderate adherence** and **steady improvement** over time.
* ***Longest Streak***: The longest continuous planning period was 14 days, reflecting periods of strong engagement.
  
**Insight**:

Overall, the data shows a clear improvement in planning behavior and increasing stability over time,
with opportunities to strengthen weekly consistency and extend sustained planning streaks.
________________________________________________________________________________________________________________________________________________________________________________________
2. **DAILY JOURNALING**
<p align="center">
  <img src="/journal.png " alt="Personal Productivity Dashboard" width="800">
</p>

***Trends***:

* ***Weekly Consistency***
Journaling occurred an average of 3 times per week, reflecting a 43% weekly consistency rate over the 22-week period.
* ***Monthly Trend***:
On average, journaling took place on 15 days per month, maintaining a 48–50% monthly consistency across 5 months.
* ***Overall Daily Consistency***
Across 153 days, journaling was recorded on 59 days, indicating a 39% overall daily adherence.

* ***Month-over-Month Change***: **July** (+10 days) Strong improvement from June’s inactivity. **August** (+11 days) Peak consistency month. **September** (–8 days)
Noticeable drop in journaling frequency. **October** (+2 days) Slight recovery after September’s dip.

**Insight**:

Journaling habits improved steadily after June, peaking in August (+11 days) before dipping in September (–8) and slightly recovering in October (+2).
Overall consistency averaged 3 entries per week or 15 days per month, showing moderate but growing discipline in maintaining the habit.

________________________________________________________________________________________________________________________________________________________________________________
3. **DEEP WORK**

<p align="center">
  <img src="/dwork.png " alt="Personal Productivity Dashboard" width="800">
</p>

* ***Longest streak***: The longest consecutive DW streak is 7 days, with each day averaging 4 hours. This shows the potential for sustained focus, though such streaks are rare.

* ***Daily consistency***: Daily consistency is 9%, meaning DW was achieved on very few days. However, cumulative consistency is 43%, indicating that many days exceeded the 4-hour goal, which increases overall consistency.
* ***All-time average***: The average DW per day is 1 hour 43 minutes, still 2 hours 16 minutes below the target.
* ***Weekly totals***: The average weekly DW is ~11 hours, compared to a target of 28 hours, leaving a 17-hour gap.
* ***Monthly totals***: The average monthly total is 43 hours 57 minutes, approaching the target of 76 hours, showing solid progress but still room for improvement.
* ***Monthly trend***: Monthly average DW shows a clear upward trend:

- June: 25 minutes
- July: 30 minutes
- August: 2 hours 10 minutes
- September: 2 hours 7 minutes
- October: 3 hours 21 minutes

**Insight**:

Although daily consistency remains low, the upward trend in monthly averages and cumulative consistency 
shows meaningful progress toward DW goals. The focus is steadily improving month by month.
________________________________________________________________________________________________________________________________________________________________________________________
4. **DAILY READING**

   
<p align="center">
  <img src="/readpage.png" alt="Personal Productivity Dashboard" width="800">
</p>

* ***Longest Pages Read in a Day***: The maximum pages read in a single day was 24 pages, exceeding the minimum daily target of 10 pages.
* ***Daily Consistency***: The habit shows 28% daily consistency, indicating that reading every day is low. However, considering cumulative consistency, it rises to 42%, reflecting that some days involve higher reading activity than others.
* ***All-Time Average Pages per Day***: The average reading rate is 4 pages per day, which is below the target of 10 pages per day.
* ***Weekly Reading***: The average number of pages read per week is 28, falling short of the minimum weekly target of 70 pages.
* ***Monthly Reading***: The total monthly average is 129 pages, missing 171 pages to meet the monthly target.

**Insight**.

Overall, while peak reading days show strong performance, the habit lacks consistency and volume. Focused strategies to increase daily engagement could help in meeting both weekly and monthly targets.
________________________________________________________________________________________________________________________________________________________________________________________

10. **SLEEP**

Sleep serves as a **behavioral performance** indicator reflecting recovery **discipline** and **sustained productivity**. 
Maintaining sleep between 7–8 hours indicates **effective time and energy management**.

<p align="center">
  <img src="/Sleep.png " alt="Personal Productivity Dashboard" width="800">
</p>

**Trends**:

* ***Consistency (≥7 hours)***: 81%
* ***All-time Daily Sleep Average***: 7 hours 38 minutes
* ***Daily Trends***: Sleep durations remain stable and **mostly above** the 7-hour target.
* ***Weekly Trends***: Consistently **above goal**, with only one minor dip (Week 22: 6h 50m).
* ***Monthly Averages***: June (7h58m), July (7h40m), August (7h56m), September (7h17m), October (7h16m). A **deliberate adjustment** toward ~7h reflects **optimized sleep duration**.
* ***Cumulative Totals***: June–October range from 239h to 203h (as of Oct 29). The recent decline reflects **intentional alignment** with **productivity goals** while maintaining recovery balance.

**Insight**:
  Sleep data indicates **high consistency** and **intentional control**. The recent **reduction** in averages represents a **strategic balance** between ***adequate rest*** and ***productivity optimization***.
________________________________________________________________________________________________________________________________________________________________________________________


________________________________________________________________________________________________________________________________________________________________________________________
5. Recommendation 







