# The Papilion Product Sales & Performance Analysis Report
      Portfolio project | Microsoft Excel | Sales analytics | Business intelligence
This project examines sales performance across products, categories, customers, regions, cities, and sub-categories to identify revenue drivers, profit opportunities, and areas requiring further business attention.
Total revenue
$533.67M
Total profit
$79.71M
Profit margin
14.94%
Sales records
5,000
1. Introduction

Sales performance analysis helps businesses understand not only how much revenue they generate, but also which products, customers, categories, and locations contribute to that performance.
For this project, I conducted a Product Sales & Performance Analysis using a retail sales dataset containing 5,000 records and 14 columns. The dataset covers order information, customer names, geographic locations, product categories, sub-categories, quantities, unit prices, discounts, sales, profit, and payment methods.

The objective was to transform transactional data into actionable business insights that could support better decisions about product performance, regional sales, customer value, pricing, profitability, and inventory planning.
Rather than focusing on revenue alone, I examined revenue and profit together to develop a more balanced understanding of business performance.


2. Analytical approach and data story

My analytical process followed a structured workflow:

Data understanding

Review the dataset, fields and reporting period

Data validation

Check missing values, types and calculations

Exploratory analysis

Analyze trends, categories, products, customers and regions

Visualization

Build PivotTables, charts and a sales dashboard in Excel

Business recommendations

Translate findings into measurable actions

The story behind the data


The analysis revealed a business generating approximately $533.67 million in recorded sales and $79.71 million in profit. However, performance was not uniform across all dimensions.

Home Decor was the leading category by revenue, while North was the strongest region by total sales. Bangalore recorded the highest sales among the cities, and May generated the highest combined sales among calendar months.

At the product level, Headphones Accusantium recorded the highest total profit among individual products. These findings highlight different dimensions of performance: a category can lead in revenue, a product can lead in profit, and a region can outperform others in total sales.

The central question was therefore not simply, “How much did the business sell?” It was, “Where is performance strongest, what is driving it, and where can management improve results?”


3. Instruments and tools used

- Instrument	&  Purpose

- Microsoft Excel	:  Data exploration, calculations, analysis and dashboard development

- Excel Tables and filters	: Reviewing records and examining specific segments

- PivotTables	: Aggregating sales and profit by category, region, city, customer and time

- PivotCharts and chart  : Presenting comparisons and trends visually

- Custom number formatting  : Making large values easier to read without changing underlying data

- KPI calculations	: Measuring revenue, profit, profit margin and units sold

The documented workflow was Excel-based. The results below were also checked against the dataset using calculations, so the project metrics reflect the 5,000-row source rather than relying solely on the displayed dashboard.


. Pre-analysis  : Understanding the dataset

The first stage was to establish the dataset's structure, reporting period, key variables and suitability for analysis.

Dataset size - 5,000 rows × 14 columns

First order date - 4 Oct 2023

Last order date - 3 Oct 2025

Unique order IDs - 5,000

Unique customer names - 4,844
Missing values  - 0

Key variables examined

●	Sales and Profit: Financial performance measures.

●	Order Date: Time-based analysis.

●	Category and Sub-Category: Product group performance.

●	Product Name: Individual product profitability.

●	Region and City: Geographic performance.

●	Customer Name: Customer-level sales contribution.

●	Quantity, Unit Price and Discount: Transaction characteristics.

●	Payment Mode: Distribution of recorded payment methods.

Data quality observations : The  data contained no missing values across its 14 columns, and every order ID was unique. The Order Date field was usable for date-based analysis.
However, the absence of missing values does not automatically guarantee that every record is correct. A full production-quality validation should also test duplicate transactions, invalid discounts, non-positive quantities, unusual prices, sales calculations, and the business definition of profit.
The analysis also needs to respect the partial calendar years: 2023 begins in October and 2025 ends in October. Comparisons between full and partial years would be misleading without a like-for-like reporting period.

5. In-analysis: Findings and observations

A. Overall sales performance

The business generated substantial sales and positive recorded profit during the reporting period.


KPI	Result

- Total sales revenue	= $533,666,024.35

- Total recorded profit	 = $79,708,734.91

- Profit margin	 = 14.94%

- Total units sold	= 14,963

- Average sales per record	 = $106,733.20

- Number of records	     = 5,000

The average sales per record is total sales divided by the 5,000 records. It should not be called average order value unless each record is confirmed to represent one complete customer order.

Key insight derived: The recorded profit margin is approximately 14.94%, meaning the dataset records about $14.94 in profit for every $100 in sales.

Business implication: Revenue growth should be evaluated alongside profit. Increasing sales through heavy discounts or low-margin products may not improve overall business performance.


B. Sales performance by category

Sales by Product Category

Total recorded sales for each product category.
 
Home Decor led category revenue at $57.23 million, followed by Furniture at $56.65 million and Clothing at $55.05 million. Groceries recorded the lowest category revenue at $47.88 million.
The gap between the highest and lowest categories was approximately $9.35 million.

Key insight derived: Revenue is spread across several categories, although Home Decor has a measurable lead.

Actionable recommendation: Examine category-level profit margins, stock availability, discount levels and sales volume before allocating more inventory to the highest-revenue categories. Investigate whether Groceries' lower revenue reflects lower demand, lower prices, stock constraints or another factor.


C. Sales performance by region

Sales Revenue by Region

Comparison of total sales across the four regions.
 
The North region recorded the highest sales at approximately $143.58 million, while the South region recorded the lowest at approximately $123.23 million.
The difference was about $20.35 million.

Key insight derived: Geographic performance varies, creating an opportunity to compare the commercial conditions of stronger and weaker regions.

Actionable recommendation: Review regional customer demand, product mix, pricing, promotional activity and distribution costs. Use successful practices in the North as hypotheses to test in the South rather than assuming the same strategy will work everywhere.


D. Sales trend by calendar month

Combined Sales by Calendar Month

Sales grouped by month name across all years in the dataset, not a sequential monthly time series.
 

May recorded the highest combined sales across all May records, at $50.76 million. February recorded the lowest combined sales, at $39.76 million.

Important analytical distinction: These values combine sales from the same calendar month across the reporting period. They do not establish that sales increased from January to December or that May was the strongest month in every year.

Actionable recommendation: Investigate the May sales peak for possible seasonal demand, promotional campaigns or product-mix effects. Build a separate chronological monthly trend by year and month to confirm whether the pattern repeats.


E. Top six cities by sales

Top Six Cities by Sales

Cities ranked by total recorded sales.

 

Bangalore ranked first at $29.99 million, closely followed by Lucknow at $29.90 million. The relatively small gap between these cities suggests that the leading locations have similar sales totals.

Key insight derived: The highest-performing city is not dramatically ahead of the other leading cities.

Actionable recommendation: Compare city-level profitability, order frequency, customer retention, and distribution expenses before deciding where to expand or concentrate marketing expenditure.


F. Top five sub-categories by sales

Top Five Sub-Categories by Sales

Highest-revenue product sub-categories.
 
Sofa led the five sub-categories with $15.19 million in revenue, followed by Lamp at $14.77 million. Fiction completed the top five at $12.38 million.

Actionable recommendation: Examine these sub-categories' margins, inventory turnover and return rates. High sales alone do not establish which items should receive the largest inventory allocation.


G. Most profitable individual products

The product-level profit analysis identified the following leaders:


Product	Total recorded profit

Headphones Accusantium -  $141,873.79

Laptop Similique -  $136,751.80

Accessories Repellendus	-  $131,526.41

Textbook Omnis - $119,166.66

Lipstick Accusamus - $119,017.65

Key insight derived: Headphones Accusantium was the leading product by total recorded profit, followed by Laptop Similique.

Actionable recommendation: Evaluate these products for continued stock availability and targeted marketing, while also comparing profit per unit, sales volume, discount dependence and inventory holding costs.


H. Highest-sales customers

The customer analysis identified Aaryahi Madan as the highest-sales customer in the dataset, with $650,151.90 across three records.

The next-highest customer by recorded sales was Kimaya Vala, with $490,935 across two records.

Key insight derived: The highest-sales customer contributed a substantial amount relative to the other leading customers.

Actionable recommendation: Review purchase history and retention opportunities for high-value customers. Before introducing loyalty offers, evaluate customer profitability and the cost of incentives.

6. My dashboard

The Excel dashboard brings the different analytical views together so a viewer can move from an overall performance summary to specific product, customer, geographic and time-based questions.
 
The dashboard is designed to communicate the following:

●	KPI summary: Revenue, profit, profit margin and units sold.

●	Sales trend: Combined monthly sales and opportunities for chronological trend analysis.

●	Product performance: Highest-revenue categories and sub-categories, plus leading products by profit.

●	Geographic performance: Regional and city-level comparisons.

●	Customer contribution: Highest-sales customers and their contribution to recorded revenue.

The number formatting improvements also help make the dashboard easier to scan. For example, displaying $79.7M instead of $79,708,734.91 reduces visual clutter while preserving the underlying numerical value.

7. Who this analysis matters to, and why

Stakeholder	Why the analysis matters

Business owners and executives	- Understand total performance and identify where further investigation is needed

Sales managers	- Compare regional and city-level results and prioritize sales improvement

Product managers	- Identify leading categories, sub-categories and profitable products

Marketing teams	- Develop targeted campaigns for promising product groups and customer segments

Inventory and procurement teams	- Use product and category demand patterns to support stock planning

Finance teams	- Evaluate profit margins alongside sales revenue and discounting

Data analysts	- Demonstrate data validation, aggregation, exploratory analysis and dashboard communication

The project demonstrates how a sales dataset can support multiple business functions, while also showing why conclusions should be based on both revenue and profitability.


8. Post-analysis insights

The analysis produced several important observations.

1. Revenue and profitability must be considered together. The dataset recorded $533.67 million in sales and $79.71 million in profit, giving a profit-to-sales ratio of 14.94%.

2. Home Decor was the leading category by revenue. Its $57.23 million in sales places it ahead of the other categories, but its long-term value should be assessed using margin and stock-turnover measures.

3. The North region led geographic sales. Its $143.58 million in revenue was approximately $20.35 million above the South region.

4. May had the highest combined monthly sales. This is a useful starting point for investigating seasonality, but it must be validated with a chronological year-month analysis.

5. Bangalore led the six highest-sales cities. The narrow gap between leading cities suggests that city-level strategy should consider more than revenue ranking.

6. Headphones Accusantium led individual product profit. This finding offers a starting point for investigating product-level margin and demand.

7. Customer sales concentration deserves further analysis. The highest-sales customer contributed $650,151.90, but a broader customer segmentation is needed to assess how dependent the business is on a small group of customers.

8. Data quality and reporting periods affect decision-making. The absence of missing values is encouraging, but calculation validation and like-for-like date comparisons remain important.


9. Overall recommendations

1.	Optimize for profitable growth. Track revenue, profit, margin and discount levels together. Investigate categories with lower revenue or profit before changing product strategy.

2.	Investigate regional performance gaps. Compare demand, product mix, customer behaviour and distribution costs between North and South, then test improvements in the lower-performing region.

3.	Build a proper year-month trend. Create a date field grouped by both year and month so that seasonal patterns and year-over-year performance can be evaluated accurately.

4.	Strengthen product-level reporting. Track profit per unit, sales volume, margin, returns and inventory turnover alongside total product revenue.

5.	Develop customer segmentation. Group customers by total sales, frequency, recency and, where possible, profit contribution to distinguish high-value customers from occasional purchasers.

6.	Validate financial calculations. Confirm the definitions and formulas for Sales and Profit, including how discounts and product costs are handled.

7.	Improve dashboard usability. Use consistent currency formats, clear titles, readable labels, appropriate chart types and documented filters.

8.	Monitor results over time. Establish a repeatable reporting cycle and track whether implemented changes improve margin, sales, retention and inventory performance.


10. Conclusion
This Product Sales & Performance Analysis transformed 5,000 retail sales records into a structured view of revenue, profitability, customer contribution, product performance and geographic variation.
The results identified Home Decor as the leading category by revenue, North as the leading region, Bangalore as the leading city among the six examined, and Headphones Accusantium as the highest-profit product. The analysis also highlighted the importance of examining monthly patterns carefully and evaluating revenue alongside profit.
The project demonstrates my ability to structure a business question, inspect and validate data, perform multi-dimensional analysis, create an Excel dashboard, and translate numerical findings into recommendations.

My key takeaway

My key takeaway is that sales analysis becomes more valuable when it explains not only what happened, but also where performance differs, what needs to be investigated, and which actions could improve business outcomes. 
