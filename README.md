# Sales-Analysis
This project presents an interactive Sales Performance Dashboard developed using Microsoft Power BI to analyze business sales data and generate meaningful insights for data-driven decision making.

The dashboard helps track sales, cost, profit, and growth trends across regions, products, and time periods.
The dashboard helps track sales, cost, profit, and growth trends across regions, products, and time periods.

🛠 Tools & Technologies

Power BI Desktop

Power Query

DAX

Excel / CSV datasets

🎯 Objective

To design a dynamic dashboard that:

Monitors overall sales performance

Identifies top performing products and regions

Tracks profit and margins

Supports strategic business decisions

📂 Dataset Information

The dataset includes:

Field Name	Description
Date	Order date
Region	Sales region
Product Category	Product type
Product Name	Individual product
Quantity Sold	Units sold
Revenue	Sales amount
Cost	Product cost

🧹 Data Preparation

Performed using Power Query:

Removed duplicates

Handled missing values

Standardized column names

Corrected data types (Date, Numeric, Text)

Created Date table for time intelligence

📊 Data Modeling

Star schema model created with relationships:

Orders → Date

Orders → Customers

Orders → Restaurants

Orders → Delivery Partners

filtering

🔍 Key Insights

Sales show consistent monthly growth with peak performance in recent months.

Few products contribute to majority of revenue (Pareto effect).

Some regions generate higher profit margins than others.

Certain categories have high sales but lower profitability.

Seasonal patterns impact overall revenue.

