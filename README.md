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

![image alt](https://github.com/AtharvThakur7/SalesData-Analytics/blob/94ba46898437a56aa56ae411986052fed5c220fa/Screenshot%202025-01-07%20231647.png)

1. ***Relationship Between Sales And Profit*** :  
 The scatter plot reveals a positive correlation between sales and profit. Higher net sales generally translate to higher profits.

2. ***Sales Trends Over Time*** :

- Annual net sales show a slight decline from 2020 to 2024, peaking at 32M in 2023 but dropping in 2024.
- Seasonal promotions, like "Weekend Flash Sale" and "Clearance Sale," contribute significantly to sales spikes.



***Average Discount Offered in Categories***:

- Weekend Flash Sales have the highest average discount (23K), followed by Clearance Sales (18K).

- Minimal discounts (or none) are observed for Festive Diwali and New Year Special, indicating premium pricing strategies during festive periods.

4. ***Total Orders***:

- The business processed 3.51K orders, showing a reasonable volume given the high-value products like electronics.

5. ***Sales by City*** :

- Major cities like Mumbai, Pune, Hyderabad, and Bangalore dominate sales.
- Tier 2 cities such as Indore and Nagpur also contribute significantly, indicating a balanced urban-rural penetration strategy.

## b> Part 2 - Top and Bottom Product Performance

![image alt](https://github.com/AtharvThakur7/SalesData-Analytics/blob/ea153fde828db80cde7fbdc529fcd90357d4a167/Screenshot%202025-01-07%20222344.png)

1.***Top/Bottom 5 Products by Sales***:

- Top Performers: High-ticket items like the Apple iPhone 14 (21.4M) and Apple MacBook Air drive significant revenue.
- Underperformers: Products like Colgate Toothpaste (21K) indicate either low demand or competitive pricing issues.


2.***Top/Bottom 5 Products by Unit Sold***:

- High Quantity Sellers: Apple iPhone 14 leads in both sales and quantity, showing brand strength.

- Low Quantity Sellers: Borosil Glass Set and Nivea Body Lotion are at the bottom, suggesting limited demand or niche markets.


3.***Top/Bottom 5 Products by Profit*** :

- High Profit Generators: Electronics dominate, with the iPhone 14 contributing the most profit (2.14M).

- Low Profit Generators: Low-value items like Dove Soap Pack and Colgate Toothpaste yield minimal profit margins.


## c> Part 3  - Comparative Sales and Profit Analysis

![image alt](https://github.com/AtharvThakur7/SalesData-Analytics/blob/ea153fde828db80cde7fbdc529fcd90357d4a167/Screenshot%202025-01-07%20222413.png)

1. ***Comparison of Metrics Between Periods*** :

- The dashboard facilitates direct comparison of sales, profit, and units sold for two custom timeframes.

 - From the given trends, consistent sales (~122M) and profits (~12.2M) suggest a steady performance.

## Bussiness Insights Summary 

1.***Key Observations***:

- High-value electronics (e.g., iPhones, laptops) are the business's core strength, contributing the most to sales and profits.

- Promotions like Weekend Flash Sales drive significant short-term gains but may erode profit margins.

 - Low-performing products (e.g., daily essentials) require attention to reposition or discontinue them.



2. ***City Insights***:

- Expanding operations in high-performing cities (Mumbai, Pune) and targeting Tier 2 cities with promotions can further increase sales.



3.***Sales Trends***:

- The decline in net sales from 2023 to 2024 signals the need to reinvigorate product offerings or enhance promotional strategies.


## Conclusion and Impact

1. ***Conclusion*** :

- Electronics lead in driving overall business performance.

- Strategic promotions (e.g., flash sales) are effective but should balance discounts to protect margins.
  
- Focus on high-value cities and improve marketing for underperforming product categories.



2. ***Business Impact***:

- Improving profitability requires targeting high-margin products and optimizing promotional expenses.

- Geographic expansion in Tier 2 cities and festive sales can sustain long-term growth.

- Regularly updating the product portfolio ensures competitiveness and mitigates the risk of declining trends.
