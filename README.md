##  Retail Diagnostic Analysis: Underperformance and Assortment Strategy 

This project is a diagnostic analysis designed to identify and solve underperformance issues affecting the Commercial Performance of the Male Category across various store segments of a major retailer. The goal is to move beyond aggregated reporting to provide data-justified strategies for assortment correction and marketing spend reallocation.

Status: (In Progress)

**Next Update:** SQL query scripts and the final Tableau visualization link will be uploaded shortly.
***

###  Methodology & Execution

Data Modeling & Simulation (Power Query/M Language): Power Query is used to cleanse, model, and apply M language conditional logic to enforce business rules, accurately simulating the Male Category underperformance scenario.

Performance Diagnostics (SQL): Complex SQL queries (JOINs, GROUP BY) calculate key efficiency metrics like AOV and Basket Size, isolating specific low-performing store/category combinations.

Strategic Delivery (Tableau): SQL output is loaded into a Tableau dashboard to visualize findings and deliver data-backed strategies for assortment correction and marketing reallocation.
***

###  Visual Analysis & Screenshots

####  Tableau Dashboard Screenshot
![Tableau Email Marketing Dashboard Screenshot]()

***

###  Key Business Insights & Recommendations

The analysis identified key areas for immediate strategic action:

* **Profit Leakage Elimination:** Identified a critical issue in the **40% discount tier** (Avg. Profit $36 vs. $50 Target). **Recommendation:** Eliminate this tier to protect margins.
* **Conversion Optimization:** Submission Hour data revealed specific peak conversion times (11 AM, 4 PM, 5 PM). **Recommendation:** Optimize email send schedules to target these precise hours.
* **Regional Focus:** **United States** and **India** are the highest profitability regions. **Recommendation:** Focus expansion and marketing spend on these high-performing markets.

***

###  Tools & Techniques Used

The project pipeline involved: **Data Preparation** using Power Query (MS Excel) ; 
**Data Modeling** using Advanced Excel (Pivot Tables, XLOOKUP/VLOOKUP) to generate metrics;
**Visualization** in Tableau Desktop (Dual-Axis charts, customized KPIs);
**Version Control** via Git & GitHub.

***

### 📂 Repository Contents & Access

* **Tableau Dashboard:** `Email Marketing Profitability & Risk Analysis.twbx` (Interactive workbook).
* **Excel Data Model:** `email_marketing_excel.xlsx` (Cleaned data, lookups, and final analysis).
* **Live Dashboard Link:** [**View the Dashboard Live Here**](https://shorturl.at/ikTSE)
