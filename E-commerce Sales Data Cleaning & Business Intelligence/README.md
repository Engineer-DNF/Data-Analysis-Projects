#  GameZone Orders Data Analysis

![Excel](https://img.shields.io/badge/Excel-Data%20Cleaning-217346?logo=microsoftexcel&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-E97627?logo=tableau&logoColor=white)
![EDA](https://img.shields.io/badge/EDA-Business%20Analysis-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)


## Project Overview

This project showcases an end-to-end data analytics workflow using the **GameZone Orders Dataset**, a real-world e-commerce dataset containing **21,864 sales transactions**.

Starting from raw data, I performed data quality assessment, data cleaning, validation, exploratory analysis, and interactive dashboard development using **Microsoft Excel** and **Tableau**.

> 📷 **Project Dashboard**
>
> Click below to explore the interactive dashboard.
>
> 🔗 [View Interactive Dashboard](https://public.tableau.com/app/profile/facundo.diaz.neto/viz/SalesDashboard-Gamezone/SalesPerformanceDashboard)
>
> ![Dashboard Overview](images/Sales-Performance-Dashboard.png)

---

## Project Workflow

```text
Raw Dataset
      │
      ▼
Data Quality Assessment
      │
      ▼
Issues Log
      │
      ▼
Data Cleaning & Validation
      │
      ▼
Pivot Table Analysis
      │
      ▼
Insights Log
      │
      ▼
Interactive Tableau Dashboards
```

---

## Tools & Technologies

### Software
- Microsoft Excel
- Tableau

### Excel Features Used
- Pivot Tables
- Conditional Formatting
- Sparklines
- Sorting & Filtering
- Lookup Functions (VLOOKUP)
- Date Standardization
- Text Parsing Functions

### Data Analytics Skills Demonstrated
- Data Quality Assessment
- Data Cleaning & Validation
- Exploratory Data Analysis (EDA)
- Business Insight Generation
- Data Documentation
- Data Visualization

---

## Dataset

- **Source:** GameZone Orders Dataset
- **21,864** transaction records
- **2** related tables (`Orders` and `Region`)
- Sales data covering **2019–2022**

---

## Project Objectives

- Assess data quality before analysis
- Clean and standardize inconsistent data
- Validate data integrity
- Generate business insights
- Build interactive Tableau dashboards

---

## Data Cleaning & Validation

A structured data quality assessment was performed before any analysis.

The cleaning process included:

- Date standardization
- Missing value handling
- Product name normalization
- Duplicate detection
- Data validation
- Documentation through a dedicated **Issues Log**

When insufficient information was available, records were preserved and documented instead of being modified.

### 📷 Issues Log

*( screenshot - Issues Log worksheet)*

![Issues Log](images/issues_log.png)

---

## Business Analysis

The cleaned dataset was analyzed using Excel Pivot Tables and Tableau.

The analysis focused on:

- Revenue trends over time
- Product performance
- Sales volume
- Average Order Value (AOV)
- Marketing channel performance
- Regional performance

An **Insights Log** was created to document every business finding and identify the stakeholders who could benefit from each insight.

### 📷 Pivot Table Analysis

*(screenshot - Pivot Table with Conditional Formatting and Sparklines.)*

![Pivot Table](images/pivot_table.png)

---

## Tableau Dashboards

The project includes multiple interactive dashboards.

| Dashboard | Purpose |
|-----------|---------|
| Overall Revenue | Revenue trend over time |
| Product Revenue | Revenue by product |
| Product Sales Count | Units sold by product |
| Product AOV | Average Order Value |
| Marketing Revenue | Revenue by acquisition channel |
| Regional Revenue | Revenue by geographic region |
| Product Revenue by Marketing | Marketing performance by product |
| Product Revenue by Region | Regional performance by product |

### 📷 Dashboard Examples

#### Overall Revenue

![Overall Revenue](images/tableau_overall.png)

#### Product Revenue

![Product Revenue](images/tableau_products.png)

#### Marketing Performance

![Marketing Dashboard](images/tableau_marketing.png)

---
## Key Findings

- **USD 6.1M** in total sales analyzed across 21,864 transactions.
- Revenue nearly doubled during 2020 before declining in 2021.
- December consistently recorded the strongest sales performance.
- Gaming Monitor, Nintendo Switch, and PlayStation 5 were the top revenue drivers.
- Direct was the highest-performing marketing channel.
- Similar revenue patterns were observed across all geographic regions.
---

## Repository Structure

```text
GameZone-Orders-Data-Analysis/

├── excel/
│   ├── GameZone_Orders_Cleaning.xlsx
│
├── tableau/
│   └── GameZone_Dashboard.twbx
│
├── images/
│   ├── dashboard_overview.png
│   ├── issues_log.png
│   ├── pivot_table.png
│   ├── tableau_overall.png
│   ├── tableau_products.png
│   └── tableau_marketing.png
│
└── README.md
```

---

## Highlights
🟩 Performed end-to-end data cleaning on a real-world dataset.

🟩 Identified and documented data quality issues before analysis.

🟩Built a reproducible data cleaning workflow in Excel.

🟩 Performed exploratory business analysis using Pivot Tables.

🟩 Created interactive Tableau dashboards.

🟩 Generated actionable insights for Finance, Marketing, and Product teams.

---
