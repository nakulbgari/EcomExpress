📦 Ecom Express – Power BI Dashboard Project
📌 Project Overview

This Power BI project analyzes e-commerce order performance using customer, order, and product data.
The dashboard focuses on sales, revenue, cancellations, and order value metrics, calculated using custom DAX measures.

The objective of this project is to provide clear business visibility into:

Revenue performance

Order cancellation behavior

Average order value (AOV)

📂 Data Tables Used

The Power BI report is built using the following tables:

🔹 customer

Contains customer-level details used for order linkage and analysis.

🔹 orders

Core transactional table containing:

Order details

Sales values

Cancellation information

🔹 products

Contains product-related information used to analyze sales and revenue performance.

📐 Data Modeling

Relationships created between:

customer → orders

products → orders

Central orders table used as the fact table

Model designed to support DAX-based aggregations

📊 Measures Created (DAX)

The following custom measures were created inside Power BI:

Sales – total sales generated from orders

Revenue – overall revenue metric

AOV (Average Order Value) – average value per order

Cancellation Rate – percentage of cancelled orders

Lost Revenue (Cancellation) – revenue lost due to cancellations

These measures enable performance tracking and comparison across different dimensions such as customers and products.

📈 Dashboard Insights

Using the above measures, the dashboard provides insights into:

Overall sales and revenue performance

Average order value (AOV) trends

Order cancellation rate

Revenue loss due to cancellations

Comparison of sales and revenue across products and customers

❓ Business Questions Answered

What is the total sales and revenue generated?

What is the average value per order?

How frequently are orders getting cancelled?

How much revenue is lost due to cancellations?

Which products or customers contribute more to sales?

🛠️ Tools & Skills Used

Power BI Desktop

DAX (Measure creation)

Data Modeling

CSV data sources

Business KPI design

📁 Project Structure
📦 Ecom-Express-PowerBI
 ┣ 📂 Dataset
 ┃ ┣ Customers.csv
 ┃ ┣ Orders.csv
 ┃ ┗ Products.csv
 ┣ 📊 Ecom Express.pbix
 ┗ 📄 README.md

🚀 How to Use

Open Ecom Express.pbix in Power BI Desktop

Refresh the data

Use slicers and visuals to explore sales, revenue, AOV, and cancellations

📌 Key Takeaways

Built core business KPIs using DAX

Designed a clean and simple Power BI data model

Analyzed the impact of order cancellations on revenue

Created metrics useful for operational and business teams

👤 Author

Nakul Bagri
Power BI Developer | Data Analyst
