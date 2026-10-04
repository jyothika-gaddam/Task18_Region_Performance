# Task 18 - Region Performance

## Objective
Compare sales across regions, compare sales and profit, and rank regions by performance.

## Tools
- Excel
- Power BI (concept can be recreated using the included summary)
- Python was used only to prepare the deliverables.

## Dataset
The project uses a 200-row sales dataset containing Order ID, Order Date, Product, Category, Region, State, Quantity, Unit Price, Discount, Sales, and Profit.

## Region Summary

| Rank | Region | Orders | Quantity | Sales | Profit | Profit Margin |
|---:|---|---:|---:|---:|---:|---:|
| 1 | North | 54 | 239 | 3,978,704.50 | 765,586.20 | 19.24% |\n| 2 | East | 50 | 191 | 2,789,762.00 | 536,842.00 | 19.24% |\n| 3 | West | 43 | 190 | 2,618,277.50 | 445,081.74 | 17.00% |\n| 4 | South | 53 | 188 | 2,465,317.50 | 386,420.97 | 15.67% |\n
## Key Findings
1. **North** ranks #1 in both sales and profit.
2. **East** ranks #2 in both sales and profit and has the highest profit margin at **19.24%**.
3. **West** ranks #3 in sales and profit.
4. **South** ranks #4 in sales and profit and has the lowest profit margin at **15.67%**.
5. The bar chart compares Sales and Profit for all four regions.

## Deliverables
- `data/sales_data.csv` - source dataset copy
- `reports/region_summary.csv` - region-wise summary and rankings
- `charts/region_sales_profit_bar_chart.png` - Sales vs Profit bar chart
- `Task18_Region_Performance.xlsx` - Excel workbook with raw data, summary, chart, and findings

## Interview Question
**Why compare profit with sales?**

Sales show the revenue generated, while profit shows how much money remains after costs. A region can have high sales but a lower profit margin, so comparing both helps identify whether sales are actually translating into healthy profitability.
