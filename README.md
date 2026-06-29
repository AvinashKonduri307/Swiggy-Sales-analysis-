# End-to-End Swiggy Sales Analytics Project using Microsoft Fabric & Power BI

I recently completed an end-to-end Sales Analytics project using **Microsoft Fabric** and **Power BI**, where I implemented a modern data analytics workflow from data ingestion to interactive business reporting.

The project began with loading raw Swiggy sales data into a **Microsoft Fabric Lakehouse**, which served as the centralized storage layer for the unstructured data. After validating the data, I transformed it into a structured format suitable for analytics and reporting.

To automate the movement of data, I designed a **Data Pipeline** in Microsoft Fabric. The pipeline copied multiple datasets—including Fact Orders, Date, Restaurant, Dish, and Location dimensions—from the Lakehouse into a **Fabric Data Warehouse**, enabling a clean star schema for analytical queries. This process demonstrated how Microsoft Fabric integrates data engineering and business intelligence into a single platform.

Within the Warehouse, I used SQL to validate the data, perform transformations, and ensure data quality before reporting. I then connected **Power BI Desktop** directly to the Fabric Warehouse to create a **Semantic Model**, establishing relationships between fact and dimension tables for efficient querying and business analysis.

Using the semantic model, I built an interactive Power BI dashboard that provides valuable insights into Swiggy's sales performance. The dashboard includes key performance indicators such as **Total Sales (₹53.01M), Average Order Value, Total Orders, Average Rating, and Total Rating Count**. It also features interactive visualizations including Monthly, Weekly, and Daily Sales Trends, Sales by Food Type, Top Performing Restaurants, and State-wise Sales Analysis. Dynamic slicers allow users to filter data by City, Restaurant, Food Type, and Quarter, enabling flexible exploration of business performance.

After completing the report development, I published the Power BI report back to **Microsoft Fabric**, making it available for centralized access, collaboration, and future enhancements.

### Technologies Used

* Microsoft Fabric
* OneLake
* Lakehouse
* Data Pipeline
* Data Warehouse
* SQL
* Power BI Desktop
* Semantic Modeling
* Data Modeling (Star Schema)
* DAX
* Data Visualization

### Key Learnings

This project strengthened my understanding of the complete analytics lifecycle—from data ingestion and engineering to semantic modeling and business intelligence. It provided practical experience with Microsoft Fabric's unified analytics platform while reinforcing best practices in SQL, data modeling, ETL pipelines, and dashboard development.

This project represents more than building a dashboard; it demonstrates how raw business data can be transformed into meaningful insights through a scalable, end-to-end analytics solution. It has been a valuable step in enhancing my skills in Data Analytics, Business Intelligence, and Microsoft's modern analytics ecosystem.

