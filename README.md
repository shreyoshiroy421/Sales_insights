# Sales Insights Analysis – Atliq Hardware*

**Project Overview:**
This project aims to provide actionable insights for a sales director of a hardware company. Using Power BI, I transformed raw sales data into a dynamic dashboard to track key performance indicators (KPIs) and identify declining sales trends across different regions and products.

**Tech Stack:**

- **Tool:** Power BI Desktop
- **Database:** MySQL 
- **Data Modeling:** Star Schema (1:Many relationships)
- **Languages:** DAX (Data Analysis Expressions), Power Query (M)

 **Data Architecture:**
The project follows a **Star Schema** design:

- **Fact Table:** sales transactions (Sales amount, quantity, dates, and keys)
- **Dimension Tables:** sales customers, sales products, sales markets, and sales date.
- **Measure Table:** BaseMeasures (Consolidated DAX measures for Revenue and Sales Qty).
