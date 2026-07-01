# MIS Executive Portfolio Projects

Excel-based MIS and dashboard projects built to demonstrate core data analysis skills: formulas, conditional formatting, pivot-style summaries, dynamic charts, and dashboard design.

---

## Project 1: Monthly Sales MIS Report
**File:** `Monthly_Sales_MIS_Report.xlsx`

**Business use-case:** A regional sales manager needs a monthly performance report showing which agents hit target, revenue by region, and top/bottom performers.

**What's inside:**
- `Raw Data` — 50 rows of sales records (Agent, Region, Product, Target, Actual, Month)
- `Achievement %` and `Status` formulas (`=Actual/Target*100`, `IF` logic)
- Conditional formatting — green for Met Target, red for Below Target
- `Region Summary` and `Agent Summary` — pivot-style tables using `SUMIF`/`AVERAGEIF`
- `Month Summary` — trend table feeding a line chart
- Bar chart (region-wise performance) and line chart (month-over-month trend)
- `Summary` sheet — 4 live KPI cards: Total Revenue, Total Agents, % Who Hit Target, Top Agent Name

**Skills demonstrated:** SUMIF/AVERAGEIF, IF logic, conditional formatting, pivot-table-style aggregation, charting, KPI dashboard design.

---

## Project 2: HR Attendance Dashboard
**File:** `HR_Attendance_Dashboard.xlsx`

**Business use-case:** An HR team needs a weekly/monthly attendance tracker showing absenteeism, leave, and attendance % by department.

**What's inside:**
- `Attendance` — 660 daily records for 30 employees across 22 working days (June 2026), with a dropdown-validated Status column (P/A/L/HD)
- `Employee Summary` — per-employee counts via `COUNTIFS`, Attendance % formula, and a `SUMIFS` cross-check by month + department
- Conditional formatting — red (<75%), yellow (75–85%), green (≥85%)
- `Department Summary` — pivot-style average attendance % by department, with bar chart
- `Dashboard` — KPI cards (Company Avg Attendance %, Total Employees, Employees Below 75%, Most Absent Employee) and a dynamic Top 5 Most Absent Employees table using `LARGE` + `INDEX/MATCH`

**Skills demonstrated:** COUNTIFS/SUMIFS multi-criteria formulas, data validation, conditional formatting, pivot-table-style aggregation, dynamic ranking formulas, dashboard design.

---

.
