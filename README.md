# Unilever Sales Analytics
<img width="1836" height="920" alt="image" src="https://github.com/user-attachments/assets/4ce7bd5d-a206-4a70-bd52-f415ad2a5289" />
<img src="/excel-dashboard.png?raw=true"/>

## What is this project?
This project used the [Unilever Sales Dataset](https://www.kaggle.com/datasets/zohairbaloch/unilever-retail-sales-dataset) to answer the question from the sales manager: How was sales performance over the last 7-day? The output was an interactive dashboard visualizing the overall health metrics, as well as the sales revenue breakdown across channels/categories/product lines.

## How is the repo organized?
The repo included the raw dataset (unilever_sales.csv) and the output Excel file (Unilever Sales.xlsx). The sales analysis followed these steps:
- Data transformation with PowerQuery
- Summarizing data with PivotTable
- Visualizing key findings with PivotChart
- Consolidated charts into a dashboard
- The dashboard is interactive by Slicers

## What are key analysis techniques?
I practiced:
- Contribution analysis (Waterfall Pareto chart)
- Pareto analysis (Combined stacked bar chart and line chart)
- Ranking analysis (Filtering top 5 and bottom 5)

## What are the insights?
I identified:
- 3 products with zero sales which all fell in HAIR CARE category. I suggested the HAIR CARE category team to examine the database connected the sales invoice with the inventory management. I expected a mismatch between two systems may have caused missing data of these products.
- WHOLESALE has 15% buyers that account for 70% sales. I suggested the BUSINESS DEVELOPMENT team focus more in finding quality WHOLESALE leads.
- 3% of products account for 70% revenue of HAIR CARE category. I suggested the HAIR CARE team bundle the slowest-selling items with the best-sellers to avoid dead stocks. The team also has to invest in forecasting and ordering the top products to avoid stockouts.

## Alternative analysis
Correlation analysis could be done to find relationship between quantity and discount, tax, price.
If there is long period (3 months, 6 months, ...), trend analysis could be implemented. Otherwise, variance analysis to compare the sales with the same time last year.
