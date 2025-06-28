# -Pandemic-Data-Analysis-with-SQL-Italy-Case
Performed advanced SQL analysis on Italy’s COVID-19 data to find regional and temporal trends. Used procedures, triggers, views, and window functions to calculate recovery and mortality rates, top regions, and case trends, showcasing SQL’s power for real-world data analysis.

# COVID-19 Italy SQL Data Analysis

## Overview

This project analyzes **Italy’s COVID-19 pandemic dataset** using advanced **SQL techniques** to uncover meaningful insights into the spread, recovery, and mortality trends across regions and time.

## Objectives
- Perform **regional and temporal analysis** of COVID-19 data.
- Calculate **recovery rates, mortality rates, and death/recovery ratios** across regions.
- Identify **top and bottom regions** by cases and deaths.
- Create **views, stored procedures, and triggers** to automate analysis workflows.
- Showcase **advanced SQL capabilities** in real-world data analysis.

## Dataset
- `covid19_italy_region`: Daily COVID-19 regional case data in Italy.
- `italy_province`: Province-level case data for Italy.

## Key SQL Features Used
✅ **DDL:** Database, table, and view creation  
✅ **DML:** SELECT, JOIN, GROUP BY, HAVING, ORDER BY, UNION  
✅ **Stored Procedures:** Parameterized analysis by region, date range, and metric  
✅ **Triggers:** Insert logging for audit trails  
✅ **Window Functions:** Ranking regions by daily cases  
✅ **CTEs:** For clean structured analysis  
✅ **Data cleaning queries** to handle missing values.

## Example Analyses
- Top 5 regions with the highest total positive cases.
- Daily and weekly new case trends.
- Recovery and mortality rates across regions.
- Death-to-recovery ratio computation across different time frames.
- Province-level contribution to regional cases.

## Skills Demonstrated
- **Advanced SQL query design and optimization**
- Real-world data cleaning and exploration using SQL
- KPI extraction and temporal trend analysis
- Automation of repeatable analysis using procedures and views

## Key Findings
- Lombardia consistently had the highest number of cases across the observed period.
- Mortality and recovery rates varied significantly across regions, indicating regional healthcare disparities.
- Temporal trends allowed the identification of peak periods and effective monitoring of case surges.

## How to Use
1. Clone this repository.
2. Run the provided `.sql` script in your MySQL environment.
3. Use the procedures (e.g., `call get_region_summary('Lombardia');`) to extract custom summaries.
4. Explore the created views for quick temporal analysis.

---

## Next Steps
To enhance this project further:
- Connect with **Power BI / Tableau** for interactive visual dashboards.
- Export analysis results to CSV for advanced visualization in Python (matplotlib/seaborn).
- Extend analysis to compare with other countries for global trend analysis.

---

## License
This project is for educational and portfolio demonstration purposes.

---
