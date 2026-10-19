# Retail Sales & Business Performance Dashboard

## Project Overview
An interactive Power BI dashboard designed to analyze retail sales, profitability, product performance, and regional business results. The project demonstrates data cleaning, DAX measures, business intelligence visualization, and analytical reporting.

## Business Objectives
- Monitor overall sales, profit, order volume, and profit margin.
- Analyze sales and profit trends over time.
- Compare sales performance across product categories and regions.
- Identify top-performing product sub-categories.
- Investigate loss-making product sub-categories.
- Enable interactive analysis using a year slicer.

## Tools & Technologies
- Microsoft Power BI Desktop
- Power Query (data cleaning and transformation)
- DAX (measures and calculations)
- Microsoft Excel / CSV data
- GitHub (project documentation and version control)

## Key Metrics
- **Total Sales:** Sum of sales revenue
- **Total Profit:** Sum of transaction profit
- **Total Orders:** Distinct count of order IDs
- **Profit Margin:** Total Profit divided by Total Sales

## Dashboard Pages

### 1. Retail Sales Overview
Provides KPI cards, yearly sales and profit trends, category sales, regional sales, profit by category, and an interactive year filter.

### 2. Product Performance
Highlights the top five sub-categories by sales and compares profitability across product sub-categories.

## Data Preparation
The dataset was imported into Power Query, where data types and key fields were checked. A separate cleaned query was created for analysis, excluding rows with missing Order IDs. The original source query was retained.

## Repository Structure
```text
Retail-Sales-Business-Performance/
├── data/
│   └── superstore.csv
├── screenshots/
│   ├── main-dashboard.png
│   └── product-performance.png
├── sql/
├── README.md
└── Retail_Sales_Business_Performance.pbix
```

## How to Use
1. Download the `.pbix` file from this repository.
2. Open it using Microsoft Power BI Desktop.
3. Use the year slicer and interact with the report visuals to explore performance.

## Learning Outcomes
This project demonstrates practical skills in data preparation, DAX calculations, interactive dashboard development, and translating retail performance data into business insights.