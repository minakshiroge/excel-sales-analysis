# Excel-Sales-Analysis
“This project includes sales data cleaning, analysis, dashboards, and insights using Excel.” 

## Project Workflow — Step by Step

1. **Data Import**
   - Open Retail Store dataset (31,048 rows) in Excel.
   - Inspect column names, data types, and row/column counts.

2. **Data Formatting & Cleaning**
   - Correct data types (dates, numbers, text).
   - Remove blank rows and blank columns.
   - Identify null values: either remove or replace with appropriate values.
   - Standardize text (e.g., replace `m`, `w` with `men`, `women`).
   - Add derived columns: `Age Group`, `Month` (from Date).

3. **Data Processing & Pivot Tables**
   - **Pivot 1 — Orders vs Sales**
     - Values: Order ID (Count), Amount (Sum); Rows: Month.
     - Create column chart; format axis to show millions (0.00, "M"); remove Grand Total.
   - **Pivot 2 — Sales: Men vs Women**
     - Rows: Gender; Values: Amount (Sum).
     - Create pie chart; add callout labels and formatting; copy to dashboard.
   - **Pivot 3 — Order Status**
     - Rows: Status; Values: Order ID (Count).
     - Create pie chart; format slice angles and labels.
   - **Pivot 4 — Top 5 States**
     - Rows: Ship-State; Values: Amount (Sum).
     - Apply Top 5 filter; create bar chart; convert labels to millions.
   - **Pivot 5 — Age Group & Gender**
     - Rows: Age Group; Columns: Gender; Values: Order ID (Count) shown as % of Grand Total.
     - Create column chart with outside data labels.
   - **Pivot 6 — Orders by Channels**
     - Rows: Channel; Values: Order ID (Count) shown as %.
     - Create pie chart with data labels.

4. **Dashboard Creation**
   - Create `Annual Report 2022` sheet.
   - Copy and arrange charts from pivot tables.
   - Remove gridlines; set background and header style; merge and center title.
   - Insert slicers: `Month`, `Channel`, `Category`.
   - Connect slicers to all pivot tables using **Report Connections**.

5. **Final Checks**
   - Verify slicers filter all charts.
   - Add a `README.md` describing steps, KPIs, and how to use the dashboard.
   - Add screenshots/GIFs to showcase the final design.
