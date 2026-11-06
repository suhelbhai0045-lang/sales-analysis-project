Electronics Sales Performance Analysis — FY 2024

An Excel analysis of 252 order-level electronics sales transactions from January to December 2024, summarised by month, product, region and salesperson.

Business questions

1. Which months generated the most revenue?
2. Which products are the most profitable, not just the highest in revenue?
3. Which region has the lowest sales?
4. How is revenue spread across salespeople?

Dataset

- 252 transactions (Order IDs 1001–1252), January–December 2024
- 5 products: Laptop, Mobile, Tablet, Earphones, Smart Watch
- 4 regions: North, South, East, West
- 8 salespeople
- Columns: order, month, quarter, product, category, region, salesperson, units, unit price, revenue, cost, profit, profit margin %
- Total revenue Rs 34,943,000 and total profit Rs 12,257,485 (35.08% overall margin)

The workbook does not state where the data came from. The results describe this dataset only.

Workbook structure

Sales_Analysis_Suhail_Hussain.xlsx has seven worksheets:

Sheet	Content

00_Project_Overview	Business questions, findings, suggested next steps
01_Raw_Data	The 252 transactions
02_Monthly_Analysis	Orders, revenue, profit and margin by month, with charts
03_Product_Analysis	Product totals, margin and ranking, with a chart
04_Region_Analysis	Orders, revenue, market share and average order value by region
05_Salesperson_Analysis	Salesperson totals, ranking and share of revenue, with a chart
06_Executive_Dashboard	KPI cells and summary notes


Method

- The summary sheets use SUMIF, COUNTIF, AVERAGEIF, RANK and INDEX-MATCH formulas linked to the raw data sheet.
- Margin figures in the analysis sheets are simple averages of each order's margin %. The weighted margin (profit divided by revenue) is given where it differs.
- Average order value is revenue divided by number of orders.
- The raw data was checked for blank cells and for consistency: revenue equals units x unit price, and profit equals revenue minus cost, in every row.

Key findings

All figures were recalculated from the raw data sheet.

- Months: November and December contributed 28.4% of annual revenue (November 17.8%, December 10.6%). November is the highest month. October to December together contributed 36.6%.
- Products: Earphones have the highest margin (44.99% simple average, 45.4% weighted) and the lowest revenue (Rs 1,169,000, 3.3% of the total). Laptops contribute 45.2% of revenue at a 32.0% average margin.
- Regions: East has the lowest revenue (13.5% of total) and the fewest orders (15.5%). North contributes 33.7% of revenue, South 32.2% and West 20.6%. Average order value is lowest in West (Rs 117,754) and East is next (Rs 120,808); South is highest (Rs 160,886).
- Salespeople: The top two, Rahul Sharma (15.8%) and Rohit Verma (14.6%), generated 30.4% of total revenue. The next three are close behind (13.7% to 14.4% each). The lowest three are Vikas Rao (9.7%), Sneha Patel (9.3%) and Priya Singh (8.1%), and they also have the lowest average order values.

Suggested next steps

These are ideas to investigate, not conclusions from the data.

1. Test whether Earphone sales can grow, since the margin is highest but revenue is small.
2. Find out why East has the fewest orders and the lowest revenue before choosing a fix.
3. Review stock and staffing plans ahead of the October–December period.
4. Compare the top five and lowest three salespeople on deal size and product mix before planning training.

Limitations

- Only one year of data, so seasonality cannot be separated from one-off effects. The data shows when sales peaked, not why.
- No customer, discount, stock or target data, so causes of the regional and salesperson differences cannot be tested.
- Profit and margin depend on the cost column as given and were not independently checked.
- The analysis is descriptive. No statistical tests were done.

Tools

Microsoft Excel (formulas and charts). No PivotTables or Power Query are used in this workbook.

Author

Suhail Hussain. GitHub: suhelbhai0045-lang
