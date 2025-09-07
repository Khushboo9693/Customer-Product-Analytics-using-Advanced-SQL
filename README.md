# Advanced SQL Data Analytics Project – Customer & Product Insights

Welcome to the **Advanced SQL Analytics Project**, a real-world end-to-end data analytics solution powered entirely by **SQL**. This project simulates how data analysts work with large datasets to generate actionable insights, build performance KPIs, and deliver clean, ready-to-use reporting views for business stakeholders and dashboard tools (e.g., Power BI, Tableau).


##  Project Objectives

*  Perform **deep customer and product analysis** using raw transactional data
*  Implement **advanced SQL techniques** like CTEs, segmentation logic, and KPI computation
*  Create **modular and reusable SQL scripts** for exploration, transformation, and reporting
*  Build **final reporting views** for use by analysts or dashboard developers
*  Demonstrate a full **analytics pipeline** using SQL from raw data to insight delivery


##  Key Features

###  Customer Report View (`gold.report_customers`)

* Customer demographics & identifiers
* Customer segmentation by:

  * **Spending behavior**: New / Regular / VIP
  * **Age group**: <20, 20–29, 30–39, etc.
* KPIs:

  * Recency (months since last order)
  * Average order value (AOV)
  * Average monthly spend

###  Product Report View (`gold.report_products`)

* Product metadata: name, category, subcategory
* Product segmentation by revenue performance: High / Mid / Low
* KPIs:

  * Average order revenue
  * Average monthly revenue
* Aggregations:

  * Total orders, customers, quantity, sales


##  SQL Techniques Used

* CTEs (Common Table Expressions)
* Aggregations & Window Functions
* Data segmentation (CASE WHEN logic)
* Date difference calculations
* Derived KPIs
* View creation for reporting layers



## 📎 Tools & Environment

* SQL Server (or any modern RDBMS)
* Power BI / Tableau (for visualization)
* GitHub (for collaboration and versioning)


##  Acknowledgment

This project is inspired by a practical YouTube tutorial series on SQL analytics. It has been extended and customized to reflect real-world reporting practices.



