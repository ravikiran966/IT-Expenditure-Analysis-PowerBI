# IT Expenditure Analysis – Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-blue)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-green)
![Excel](https://img.shields.io/badge/Excel-Data%20Source-brightgreen)

## 📊 Project Overview

The **IT Expenditure Analysis** project is an interactive Power BI dashboard designed to analyze IT expenditure across different business areas, regions, IT areas, and cost categories.

The dashboard provides transparency into:

- Actual IT expenditure
- Forecast IT expenditure
- Planned IT expenditure
- Actual vs Plan variance
- Monthly expenditure trends
- Regional expenditure
- IT Area expenditure
- Cost Element Group distribution

The main objective is to help organizations monitor IT spending, identify significant deviations from planned budgets, understand major cost drivers, and support better budgeting and cost-control decisions.

---

## 🎯 Business Problem

Organizations need effective visibility into their IT expenditure to ensure that spending remains aligned with planned budgets.

Without a centralized analytical dashboard, it can be difficult to:

- Monitor actual IT expenditure
- Compare actual spending with planned budgets
- Track forecast expenditure
- Identify regions with significant budget deviations
- Understand which IT areas consume the most resources
- Identify major cost categories and cost drivers
- Support data-driven budgeting decisions

### Business Question

> **How can an organization effectively monitor and optimize IT expenditure across business areas, regions, and cost categories by comparing actual, forecast, and planned spending?**

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze IT expenditure across different business areas.
2. Compare actual expenditure with forecast and planned expenditure.
3. Calculate actual vs plan variance.
4. Identify regions with significant deviations from the plan.
5. Analyze IT expenditure by IT Area and IT Sub Area.
6. Understand expenditure distribution across cost element groups.
7. Analyze monthly expenditure trends.
8. Identify major IT cost drivers.
9. Provide an interactive dashboard for management reporting.
10. Support better budgeting and IT cost optimization.

---

# 📁 Dataset

The project uses an Excel workbook as the primary data source.

### Main Data Table

The main dataset contains fields such as:

| Column | Description |
|---|---|
| Date | Month of expenditure |
| Business Area | Business function or department |
| Region | Geographic region |
| Country | Country |
| IT Sub Area | Detailed IT function |
| IT Area | Main IT function |
| Cost element name | Individual cost element |
| Cost Element Group | Major cost category |
| Cost Element Sub Group | Detailed cost category |
| Actual | Actual IT expenditure |
| Forecast | Forecasted IT expenditure |
| Plan | Planned IT expenditure |

### Future Data

The workbook also contains a **Future Data** table containing future-period actual expenditure information.

The Future Data table was kept separately to avoid potential double counting with the main dataset.

---

# 🛠️ Tools & Technologies

The following tools were used:

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**

---
## Dashboard Preview
 <img width="772" height="423" alt="Screenshot 2026-08-23 204018" src="https://github.com/user-attachments/assets/51c781f6-3259-42fd-a13b-073fa4fd1405" />

# 🔄 Project Workflow

The complete project workflow is:

```text
Excel Dataset
      ↓
Data Import
      ↓
Power Query
      ↓
Data Cleaning & Transformation
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Exploratory Data Analysis
      ↓
Variance Analysis
      ↓
Interactive Dashboard
      ↓
Business Insights
      ↓
Recommendations


