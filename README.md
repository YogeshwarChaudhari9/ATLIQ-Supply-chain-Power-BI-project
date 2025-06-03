📦 ATLIQ Mart Supply Chain Analysis – Power BI Project
🧾 Overview
This project presents a comprehensive supply chain analytics solution developed using Power BI for AtliQ Mart, a growing FMCG manufacturer based in Gujarat, India. The primary objective is to analyze and improve delivery performance metrics to address service issues affecting key customer contracts.

🧩 Problem Statement
AtliQ Mart has been facing challenges with poor delivery service levels, leading to dissatisfaction among key customers and issues with contract renewals. It is speculated that essential products were either not delivered on time or not delivered in full over a continued period. Management aims to fix this issue before expanding to other cities and has requested the supply chain analytics team to track the ‘On-Time’ and ‘In-Full’ delivery service levels for all customers on a daily basis.

🎯 Goals
Measure Key Performance Indicators (KPIs):

On-Time Delivery (OT%): Percentage of orders delivered on or before the agreed delivery date.

In-Full Delivery (IF%): Percentage of orders delivered with the full quantity ordered.

On-Time In-Full (OTIF%): Percentage of orders delivered on time and in full.

Line Fill Rate (LIFR): Percentage of order lines fulfilled.

Volume Fill Rate (VOFR): Percentage of the total volume fulfilled.

Develop Interactive Dashboards:

Visualize daily delivery service levels using the above KPIs.

Identify systemic issues in the delivery process, particularly for key customers.

Provide actionable insights to improve delivery service levels.

📊 Data Sources
The analysis is based on the following datasets:

dim_customers.csv: Customer details.

dim_date.csv: Date dimension table.

dim_products.csv: Product details.

dim_targets_orders.csv: Target service levels for orders.

fact_order_lines.csv: Detailed order line information.

fact_orders_aggregate.csv: Aggregated order data.

🛠️ Tools and Technologies
Power BI: For data visualization and dashboard creation.

DAX (Data Analysis Expressions): For creating calculated columns and measures.

Power Query: For data transformation and cleaning.

Data Modeling: Establishing relationships between tables to create a star schema.

📈 Key Insights
Performance Gaps: The company is falling short of targets in OT%, IF%, and OTIF%.

City-wise Performance: Vadodara has the lowest customer service performance, followed by Ahmedabad and Surat.

Client Rankings: "Propel Mart" has the best service, while "Cool Blue Mart" and "Acclaimed Stores" rank the lowest.

Product Preferences: "AM Butter 500" has high order lines, indicating strong customer preference.

Product-Specific Metrics: "AM Biscuits 750" has the highest LIFR, suggesting reliable full quantity deliveries.

Overall Product Performance: VOFR is consistent across all products.

Category-wise Issues: Dairy products show both high undelivered quantities and low performance.

Monthly Variations: May had the highest delivered quantity, while August had the lowest.
