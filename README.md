# Executive Sales Performance Dashboard

## Project Overview

This project was developed as part of a Business Analyst assignment to design an interactive Executive Sales Performance Dashboard using Tableau. The objective was to transform raw sales transaction data into meaningful business insights that can support executive-level decision making.

The dashboard enables stakeholders to monitor key business metrics, identify performance trends, compare regional performance, evaluate customer segments, analyze profitability, understand the impact of discounts, monitor shipping efficiency, and investigate product return patterns.

Instead of reviewing thousands of individual transactions, decision-makers can use this dashboard to quickly understand the overall health of the business and identify areas requiring attention.

---

# Business Problem

Organizations generate large volumes of transactional sales data every day. While this data contains valuable information, it is often difficult for business managers to interpret without visualization.

The management team requires a centralized dashboard that can answer important business questions such as:

- How much revenue has the company generated?
- Is the business profitable?
- Which regions perform the best?
- Which product categories generate the highest profit?
- Which customer segment contributes the most revenue?
- Do higher discounts negatively impact profit?
- Which shipping methods require improvement?
- Which product categories experience higher return rates?

Without a centralized dashboard, answering these questions requires manual analysis and significant effort.

---

# Project Objectives

The primary objectives of this project are:

- Build an interactive executive dashboard using Tableau.
- Present key performance indicators in a clear and concise format.
- Analyze sales performance across multiple business dimensions.
- Support data-driven decision making through visualization.
- Identify opportunities to improve profitability and operational efficiency.
- Enable executives to explore the data using interactive filters.

---

# Dataset Description

Dataset Name:
dashboard_sales_data.xlsx

The dataset contains transactional sales records including:

- Order Date
- Ship Date
- Region
- Category
- Sub Category
- Customer Segment
- Ship Mode
- Sales
- Profit
- Quantity
- Discount
- Delivery Days
- Customer Rating
- Return Flag

The dataset consists of approximately 4,200 sales records representing multiple business regions and customer segments.

---

# Data Preparation

Before creating the dashboard, the dataset was inspected to ensure data quality.

The following validation steps were performed:

- Verified row and column count.
- Checked data types.
- Identified missing values.
- Verified duplicate records.
- Confirmed date fields.
- Reviewed numerical distributions.
- Validated calculated fields.

Only minimal cleaning was performed to preserve the original dataset for Tableau analysis.

---

# Tools Used

- Google Colab
- Python
- Pandas
- Tableau
- GitHub

---

# Dashboard KPIs

The executive dashboard includes three primary Key Performance Indicators (KPIs):

- Total Sales
- Total Profit
- Total Orders

These KPIs provide executives with an immediate understanding of business performance before exploring detailed visualizations.



---

# Dashboard Components

The dashboard consists of the following visualizations:

1. KPI Card – Total Sales
2. KPI Card – Total Profit
3. KPI Card – Total Orders
4. Monthly Sales Trend
5. Regional Performance
6. Category Profitability
7. Customer Segment Analysis
8. Shipping Performance
9. Discount vs Profit
10. Return Analysis

---

# Interactive Features

The dashboard contains interactive filters that allow users to analyze data dynamically.

Available filters include:

- Region
- Category
- Customer Segment

These filters enable executives to quickly focus on specific business areas without modifying the underlying data.

---

# Key Business Value

This dashboard supports executives by:

- Monitoring overall business performance
- Comparing regional sales
- Identifying profitable product categories
- Understanding customer purchasing behavior
- Evaluating shipping efficiency
- Measuring discount impact on profitability
- Monitoring return patterns

---

# Assumptions

The analysis assumes:

- Sales values are accurate.
- Profit values represent actual business profit.
- Delivery Days correctly measure shipping duration.
- Return Flag values are correctly maintained.
- Each Order ID represents one business transaction.

---

# Limitations

Although the dashboard provides valuable insights, several limitations exist.

- Historical data only.
- Customer demographic information is unavailable.
- Marketing campaign performance is not included.
- Competitor information is unavailable.
- Inventory availability is outside the scope.

---

# Future Improvements

Possible future enhancements include:

- Sales forecasting
- Customer lifetime value analysis
- Inventory optimization
- Product recommendation analysis
- Geographic mapping
- Predictive analytics
- Customer churn prediction

---

# Folder Structure

project/

├── data/

├── tableau/

├── outputs/

├── screenshots/

└── README.md

---

# Skills Demonstrated

This project demonstrates:

- Data Understanding
- Data Cleaning
- Exploratory Data Analysis
- Tableau Dashboard Development
- Business Storytelling
- Dashboard Design
- Business Insight Generation
- Executive Reporting
- GitHub Documentation

---

# Conclusion

The Executive Sales Performance Dashboard transforms raw transactional sales data into actionable business insights. By combining key performance indicators, interactive visualizations, and business-focused analysis, the dashboard enables executives to monitor performance, identify improvement opportunities, and support strategic decision-making.

