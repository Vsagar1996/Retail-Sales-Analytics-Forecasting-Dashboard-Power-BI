## Retail Sales Analytics & Forecasting Dashboard (Power BI)

### Project Overview:

This project presents an end-to-end Retail Sales Analytics and Forecasting solution built using Microsoft Power BI using a publicly available Kaggle retail dataset.
The dashboard analyzes historical retail sales data to uncover insights related to sales performance, profitability, product trends, customer segments, logistics efficiency, and future sales forecasts.

The project follows industry best practices including a star schema data model, centralized DAX measures, and business-focused visual storytelling.

### Data Source:

The dataset used in this project was sourced from **Kaggle**, a public data science platform.  
It represents historical retail sales transactions and was used solely for **educational and portfolio purposes**.

### Business Objectives:

1. Evaluate overall sales and profit performance

2. Identify top-performing and loss-making products

3. Analyze customer segments and regional trends

4. Assess logistics efficiency (freight cost & delivery time)

4. Forecast future sales and profit trends using historical data

### Data Model:

1. Fact Table: Fact_Retail_Sales

2. Dimension Tables:

   - Dim_Date

   - Dim_Product

   - Dim_Geography

   - Dim_Customer

3. Measures Table for all DAX calculations

4. Star schema with one-to-many, single-directional relationships

5. Key Metrics (DAX)

  - Total Sales

  - Total Profit

  - Profit Margin %

  - Total Quantity

  - Average Discount

  - Average Delivery Days


### Dashboard Pages:

1.  Executive Sales Overview
    
    <img src="Images/Page 1 - Executive Sales Overview.JPG" width="900"/>

    - KPI cards for Sales, Profit, Margin, Discount

    - Sales & Profit trend over time

    - State-wise performance map with profitability insights

2.  Product Performance Analysis

    <img src="Images/Page 2 - Product Performance Analysis.JPG" width="900"/>

    - Sales & Profit by product type

    - Loss-making sub-category identification

    - Detailed performance table with conditional formatting

3.  Customer & Segment Insights

    <img src="Images/Page 3 - Customer & Segment Insights.JPG" width="900"/>

    - Sales distribution by customer segment

    - Quantity vs Profit analysis

    - Top-performing segments by sales and profit

4.  Logistics & Operations Analysis

    <img src="Images/Page 4 - Logistics & Operations Analysis.JPG" width="900"/>

    - Average delivery time by freight mode

    - Profitability by freight mode

    - Scatter analysis of freight cost vs profit

5. Sales & Profit Forecast

   <img src="Images/Page 5 - Sales & Profit Forecast.JPG" width="900"/>

    - Monthly sales and profit trends

    - 6-month forecast using Power BI built-in forecasting

    - Average monthly sales KPI for baseline comparison

 ### Tools & Technologies

1. Microsoft Power BI

2. DAX (Data Analysis Expressions)

3. Star Schema Data Modeling

4. Power BI Forecasting (Time Series)

 ### Key Learnings:

- Designing interview-ready star schema models

-  Writing optimized and reusable DAX measures

- Building business-driven dashboards

- Applying forecasting for trend analysis

- Improving report usability through formatting and storytelling

### Dashboard Preview:

(Add screenshots of each page here)

📁 #### File

Sales_dashboard.pbix

### Future Work & Enhancements:

1. Extend the current Power BI forecasting by exploring advanced machine learning–based time series models such as ARIMA or Prophet for improved accuracy.

2. Introduce what-if analysis to simulate the impact of discounts, freight costs, and pricing strategies on profitability.

3. Enhance interactivity using drillthrough pages, tooltip reports, and guided narratives.
