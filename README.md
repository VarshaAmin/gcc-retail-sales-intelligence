# GCC Retail Sales Intelligence – Power BI

A Power BI dashboard built to analyze retail sales and profitability across different categories, cities, and sales channels.

## Project Overview

This project focuses on turning retail sales data into an interactive dashboard for understanding sales performance and profitability.

The report includes three pages:

### 1. Sales & Profit Overview

Provides a quick overview of the main business metrics.

* Total Sales
* Total Profit
* Total Quantity
* Profit Margin %
* Sales Trend
* Sales by Category
* Sales by Channel
* Profit by Category
* Quantity by Category

### 2. Sales Analysis

Provides a more detailed view of sales performance.

* Monthly Sales Trend
* Sales vs Profit Trend
* Sales by City
* Category Sales Performance
* Sales by Channel
* Average Order Value
* Sales Transaction Details

Filters are available for:

* City
* Category
* Sales Channel
* Order Date

### 3. Profitability Analysis

Focuses on profit and margin performance.

* Total Profit
* Profit Margin %
* Total Sales
* Profit by Category
* Profit Margin by Category
* Profit by City
* Profit by Sales Channel
* Sales vs Profit
* Profitability Details

## DAX Measures

Some of the measures used in the report:

```DAX
Total Sales = SUM([Sales Amount])
```

```DAX
Total Profit = SUM([Profit Amount])
```

```DAX
Total Quantity = SUM([Quantity])
```

```DAX
Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)
```

```DAX
Average Order Value =
DIVIDE([Total Sales], [Total Quantity], 0)
```

## Tools Used

* Power BI Desktop
* Power Query
* DAX
* CSV

## Project Structure

```text
GCC-Retail-Sales-Intelligence/
│
├── GCC_Retail_Sales_Intelligence.pbix
├── data/
│   └── gcc_retail_sales.csv
├── screenshots/
│   ├── page1-overview.png
│   ├── page2-sales-analysis.png
│   └── page3-profitability.png
└── README.md
```

## What I Practiced

* Building interactive Power BI reports
* Creating DAX measures
* Working with filters and slicers
* Creating KPI cards
* Sales and profitability analysis
* Designing multi-page dashboards
* Creating tables and visual reports

## Dataset

Sample retail sales data used for learning and portfolio purposes.

## Author

**Varsha V**

Power BI | SQL | Data Analysis | Automation Testing
