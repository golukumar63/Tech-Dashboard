1. Project Title
Tech Sales Performance Dashboard (FY 2024–25)

2.Short Description / Purpose

A Power BI dashboard designed to analyze and monitor the sales performance of technology products across various categories and brands. It provides a centralized view of key metrics such as total sales, cost, quantity, and transaction count, helping management track performance, identify top-performing products, and optimize sales strategy.

3.Tech Stack
Power BI Desktop – for dashboard creation and visualization
Power Query (M Language) – for data extraction, cleaning, and transformation
DAX – for creating measures and calculated columns (e.g., Total Sales, Average Value)
Excel/CSV – for sales and category data input
Git & Git LFS – for version control and storage of .pbix files

4.Data Source

Origin: Internal sales dataset representing product category and brand-wise transactions for FY 2024–25.
Grain: Transaction-level data aggregated at “Supervisor × Brand × Category × Year.”
Tables (Star Schema):

FactSales: Transaction details (Sales, Cost, Quantity, Transactions)
DimCategory: Product details (Category Name, Item Type)
DimBrand: Brand-level mapping (Brand Name, Share %)
DimSupervisor: Sales manager details (Supervisor Name, Team Performance)

5.Features / Highlights
a) Business Problem

The company required a unified dashboard to monitor sales performance across multiple product categories and brands. Fragmented reports made it difficult to compare team contributions, track top-selling items, and manage cost efficiency.

b) Goal of the Dashboard

Track Total Sales, Total Cost, Total Quantity, and Transactions

Compare sales performance by product category and brand

Identify top and low-performing items based on quantity and sales value

Highlight supervisor-wise contribution for performance evaluation

c) Walk-Through of Key Visuals

KPI Cards:

₹19M – Total Sales
₹14M – Total Cost
2,362 – Total Quantity Sold
967 – Total Transactions
₹7.92K – Average Sales Value
₹19K – Maximum Sales
₹455 – Minimum Sales

Quantity by Category (Bar Chart):
Displays the number of units sold per product category. Monitors (344 units) and CPUs (258 units) are the highest-selling categories, followed by Mouse and SSD.

Total Sales by Brand (Pie Chart):
Visualizes brand contribution. Intel (17.68%), Samsung (17.12%), and Dell (13.76%) lead in sales, followed by Nvidia and Western Digital.

Supervisor Panel:
Lists key sales supervisors such as Aarvi Gupta, Aadil Khan, and Ajay Sharma, showing their assigned performance scope.

d) Business Impact & Insights

Top Performers: Monitors and CPUs drive the highest volume, indicating strong demand in computing accessories.
Brand Performance: Intel and Samsung dominate overall sales share, reflecting their brand strength in tech hardware.
Cost-Sales Gap: With ₹19M total sales vs. ₹14M cost, profitability margins remain solid.
Team Efficiency: Supervisors like Aarvi Gupta lead high-performing sales teams, driving consistent category growth.
Strategic Insight: Focus marketing and supply efforts on top-performing categories and maintain balanced inventory for lower-selling items (e.g., NIC, Modem).

Tech Sales Snapshot

A data-driven Power BI dashboard offering real-time visibility into sales performance across categories, brands, and supervisors. It empowers decision-makers to optimize product mix, manage cost efficiency, and enhance overall sales strategy for FY 2024–25.
<img width="1155" height="652" alt="Tech_dashboard_snapshort" src="https://github.com/user-attachments/assets/be07d934-0179-4d0b-a320-bf4e9815f276" />

