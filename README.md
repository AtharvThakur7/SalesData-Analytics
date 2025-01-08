# Retail Sales and Profitability Analysis for ElectroHub Using Power BI

Led a strategic sales analysis for ElectroHub using Power BI to visualize key metrics like sales, profit, and quantity sold across diverse product categories. The analysis focused on identifying top-performing products, understanding sales trends, and evaluating the correlation between sales and profitability. By deriving actionable insights, the project enabled data-driven decision-making, optimizing discount strategies, and prioritizing high-performing categories to accelerate business growth and profitability.

## Problem Statement 

ElectroHub, a multi-category retail company, seeks to optimize its sales performance and profitability across diverse product lines and regions. To achieve this, the company requires actionable insights into key business metrics, including:

- Identifying top and bottom-performing products by sales, profit, and quantity sold.
- Analyzing sales trends over time (daily, monthly, quarterly, and annually) to understand seasonal patterns.
- Evaluating the relationship between sales and profit to identify profitability drivers.
- Comparing performance metrics (sales, profit, and quantity sold) across selected time periods.
- Understanding the impact of discount categories on sales through average discounts offered.
- Monitoring the total number of orders to gauge customer demand.
- Visualizing sales distribution across different cities.
- Identifying the top profit-generating categories to prioritize strategic focus.

## Data Model 

![image alt ](https://github.com/AtharvThakur7/SalesData-Analytics/blob/351accd6e51b618072d01909abe36d49a2f2ff84/Screenshot%202025-01-07%20222053.png)


***Fact Table***: The Fact Table captures transactional data, including:

Date (dd/mm/yyyy), CustomerID, PromotionID, ProductID
Key metrics: Units Sold, Price Per Unit, Total Sales, Discount Percentage, Discount Value, and Net Sales.
This table stores the core numerical data for analysis.

***Dimension Tables*** :

- Customer: Contains customer details, providing context for sales data.
- Product: Stores product information, helping to analyze sales by category, type, etc.
- Promotion: Includes promotion details (e.g., Summer Sale, Festive Diwali, etc.), discount coupons, percentages, and values associated with each promotion.
- Date Table 1: Represents an active relationship to the Fact Table based on the transaction date, supporting time-based analysis (daily, monthly, etc.).
- Date Table 2: Represents an inactive relationship, used for specific date-based calculations such as comparing different time periods or analyzing data across alternate date ranges.


# Business InSights
##  a> Part 1  - Sales Trends and Key Metrics Analysis

![image alt]()
