# Customer Transaction Analysis Dashboard (Excel)

## Project Overview

The **Customer Transaction Analysis Dashboard** is an Excel-based data analysis and reporting project created for a PR Final Project. It analyzes simulated retail transactions from **April 2024 to September 2025** to understand sales performance, customer purchasing behavior, product performance, and regional revenue.

The workbook combines raw transaction data, Excel formulas, analysis summaries, visualizations, an executive dashboard, and a final report with business insights.

## Objectives

- Analyze total revenue, transaction volume, quantity sold, and average order value.
- Compare revenue across regions and product categories.
- Identify high-value customers and frequently purchased products.
- Review monthly revenue patterns.
- Demonstrate Excel functions and analysis tools.
- Present results through a dashboard and report.
- Prepare the data for PivotTables, PivotCharts, regression, and What-If analysis.

## Workbook Structure

| Sheet | Purpose |
|---|---|
| **Raw Data** | Source transaction table containing transaction ID, date, customer, product, category, quantity, unit price, region, and revenue. |
| **Analysis** | Formula demonstrations, customer spend rankings, product frequency, list matching, text abbreviations, regional comparisons, monthly revenue, and What-If inputs. |
| **Visualizations** | Summary tables for regional sales, category sales, monthly revenue, and customer revenue rankings, plus the workbook's charts. |
| **Dashboard** | Executive KPIs, regional performance, category breakdown, key insights, and guidance for interactive PivotTables and slicers. |
| **Final Report** | Project objective, key findings, technical summary, and instructions for using the workbook. |
| **Checklist** | Tracks the project requirements and where each feature is implemented. |

## Key Performance Indicators

The workbook dashboard reports the following results:

| KPI | Result |
|---|---:|
| Total Revenue | **60,776.10** |
| Total Transactions | **180** |
| Average Order Value | **337.65** |
| Unique Customers | **30** |
| Total Quantity Sold | **542** |
| Product Count | **20** |
| Regions | **5** |
| Product Categories | **6** |
| Data Period | **Apr 2024 – Sep 2025** |

*Revenue and order values are shown in the workbook's numeric units; a currency symbol is not specified in the source data.*

## Highlights from the Analysis

- **Leading region by revenue:** South, with **16,680.97** in revenue (about **27.45%** of total revenue).
- **Leading category by revenue:** Electronics, with **33,391.08**.
- **Second-highest category by revenue:** Furniture, with **14,091.71**.
- **Most frequently purchased product:** Water Bottle Insulated, listed with **14 transactions** in the product frequency analysis.
- **Highest-revenue product:** Laptop Pro 15, with **20,558.38** in revenue.
- **Highest-spending customer in the Analysis sheet:** Karen Thomas, with **5,090.86** in total spend.
- **Monthly revenue:** The workbook provides monthly revenue values for all 18 months, ready for trend analysis.

These findings can support decisions about regional marketing, product promotions, inventory planning, and customer retention.

## Excel Functions and Techniques

The workbook demonstrates or prepares examples for:

- **Date and time:** `TODAY()`, `NOW()`, `DATEDIF()`, and `EOMONTH()`
- **Conditional summaries:** `SUMIF()`, `COUNTIF()`, and `AVERAGEIF()`
- **Customer ranking:** customer-level spend summaries and ranking formulas
- **Matching and filtering:** `MATCH()`, `IF()`, and FILTER-style extraction
- **Text functions:** `LEFT()`, `MID()`, `RIGHT()`, `UPPER()`, and `TEXT()`
- **Conditional formatting:** icon and arrow indicators for regional performance
- **What-If analysis:** Scenario Manager and Goal Seek setup
- **Regression preparation:** monthly revenue against month number for Excel Data Analysis ToolPak
- **Dashboard reporting:** KPI cards, regional summaries, category summaries, and charts

Some features, such as running a regression or adding interactive PivotTable slicers, require the user to complete the indicated steps in Excel.

## Charts and Visualizations

The **Visualizations** and **Dashboard** sheets contain chart-ready summaries and visual reporting. They are intended to help compare:

1. Revenue by region
2. Revenue by product category
3. Monthly revenue trends
4. Customer revenue rankings

The dashboard also includes KPI indicators and written insights. For interactive reporting, follow the instructions on the Dashboard sheet to add PivotTables, PivotCharts, slicers, and a date timeline.

## How to Use the Workbook

1. Open the Excel workbook in Microsoft Excel.
2. Start with **Dashboard** for the high-level summary.
3. Review **Raw Data** to understand the transaction fields.
4. Open **Analysis** to inspect the formulas, customer rankings, product frequency, and What-If assumptions.
5. Use **Visualizations** to review regional, category, monthly, and customer summaries.
6. Read **Final Report** for the project's findings and implementation notes.
7. Use **Checklist** to review the deliverables.
8. If the raw data changes, check formulas and refresh any PivotTables or PivotCharts you create.

## Suggested Improvements

- Add slicers for region and category and a timeline for transaction date.
- Add a clearly labeled currency field if the dataset represents a specific currency.
- Validate dashboard rankings against the underlying customer totals before presenting results.
- Run the prepared regression in Excel's Data Analysis ToolPak and document the slope and R².
- Add data validation and duplicate/missing-value checks when importing new transactions.

## Tools Used

- **Microsoft Excel**
- Excel formulas and functions
- Conditional formatting
- Dashboard and chart summaries
- What-If Analysis preparation
- Data Analysis ToolPak regression preparation

## Project Files

- `PR_Final_Project_Customer_Analysis.xlsx` — Excel workbook containing the data, analysis, visualizations, dashboard, and report.
- `README.md` — Project documentation.

---

**Project:** PR Final Project – Customer Transaction Analysis  
**Purpose:** Excel data analysis, visualization, dashboarding, and business insight reporting.
