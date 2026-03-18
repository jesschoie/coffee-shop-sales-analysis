# coffee-shop-sales-analysis
**Project Overview**

This project analyses coffee shop transaction data to evaluate sales performance, identify revenue drivers, and uncover customer purchasing patterns. The analysis focuses on trends over time, product performance, and store-level insights to support data-driven business decisions.

**Dataset Description**

This Maven Analytics dataset contains transaction-level sales records, where each row represents a single product purchase. 

Key fields include:

•	transaction_id

•	transaction_date

•	transaction_time

•	transaction_qty

•	store_location

•	unit_price

•	product_category

•	product_type

•	product_detail

**Analysis Questions**

•	How have sales trended over time?

•	What are the peak sales hours during the day?

•	Which products and categories drive the most revenue?

•	How does performance vary by store location?

•	Are there patterns in sales by day of the week?

**SQL Analysis**

Analysis was performed using MySQL to explore sales performance and extract key business insights from the dataset. Queries were written to aggregate transaction-level data and calculate key metrics such as total revenue, sales trends over time, and product performance.

**Dashboard**

A dashboard was created in Tableau to visualise key sales performance metrics, including revenue trends, product performance and customer demand patterns. 
<img width="1799" height="1199" alt="Sales Dashboard" src="https://github.com/user-attachments/assets/ba35d95b-8fa9-4d7f-8fae-2025f06ff563" />
View the interactive Dashboard in Tableau:
https://public.tableau.com/app/profile/jess.choie/viz/CoffeeShopSalesDashboard_17738416123990/SalesDashboard
 
**Key Insights & Recommendations**

•	Revenue has shown a consistent upward trend over the 6-month period, indicating growing demand and improving overall business performance. The drivers behind this growth should be investigated to determine whether it is sustainable and to ensure operations can support continued growth. 

•	Revenue varies across different days of the week, indicating cyclical customer demand. Staffing and inventory planning should be aligned with peak demand days to optimise operations and improve customer experience. 

•	Revenue across store locations is relatively consistent, suggesting balanced overall performance. However, revenue patterns vary by day, with different locations experiencing peak sales on different days. Staffing and inventory planning should therefore be tailored to each store’s specific demand patterns.

•	Sales are the highest in the morning and begin to decline from 11am onwards, suggesting that customer demand is driven by typical coffee consumption patterns at the start of the workday. Ensure there is sufficient staffing during the peak hours and could consider introducing promotions later in the day to increase sales during off-peak hours. 

•	Some product categories generate significantly higher revenue and sales volume than others. These categories should be focused on, and the underperforming ones should be reviewed for improvement or replacement. 

**Tools Used**

•	MySQL

•	Tableau
