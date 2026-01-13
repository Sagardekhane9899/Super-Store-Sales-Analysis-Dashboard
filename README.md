# Super-Store-Sales-Analysis-Dashboard
Super Store Sales Analysis Dashboard
Super Store Sales Analysis Dashboard
This project utilizes Power BI to analyze retail performance, providing a comprehensive view of sales trends, profitability, and future forecasts for a "Super Store."

1. Business Problem
The retail management team needs to understand the drivers of their $341.01K in total sales and $27.45K in profit. Key challenges include:



Shipping Efficiency: Identifying if the average shipping time of 4.04 days is consistent across regions.



Segment Performance: Determining which customer segments (Consumer, Corporate, or Home Office) drive the most value.



Payment & Logistics: Evaluating the impact of different payment modes (like COD vs. Online) and shipping methods (Standard vs. Same Day) on the bottom line.



Future Planning: Predicting sales demand to manage inventory effectively over the next 20 days.


2. Methodology

Data Integration: Merged sales, logistics, and geographic data to create a unified view of the Super Store's operations.



Time Series Analysis: Developed Year-over-Year (YoY) comparisons for both monthly sales and monthly profit to identify seasonal trends.



Geographic Mapping: Implemented a map-based visualization to track sales and profit across various U.S. states.
+1


Predictive Modeling: Utilized Power BI's forecasting capabilities to generate a 20-day sales forecast based on historical OrderDate trends.



Categorical Breakdown: Organized data into Categories and Sub-Categories (e.g., Furniture, Office Supplies, Technology) for granular analysis.


3. Key Insights

Dominant Segments: The Consumer segment is the largest contributor, accounting for 48% of total sales.


Payment Preferences: Cash on Delivery (COD) is the most popular payment method at 41%, closely followed by Online payments at 39%.


Logistics Trends: Most customers prefer Standard shipping, which handled 78K in sales volume, significantly higher than "Same Day" shipping at 7K.



Product Leaders: Office Supplies is the leading category by volume ($0.15M) , while Chairs is the top-performing sub-category ($46K).



Sales Forecasting: Historical peaks reached as high as 10.6K in late 2020 , with the forecast model predicting continued activity into January 2021.


4. DAX Measures Used
The dashboard's core metrics are driven by the following calculated measures:


Total Sales: SUM(Sales[Amount]) — calculated at 341.01K.


Total Profit: SUM(Sales[Profit]) — calculated at 27.45K.


Total Quantity: SUM(Sales[Quantity]) — totaling 5K units.



Average Shipping Time: AVERAGE(Sales[ShipDate] - Sales[OrderDate]) — resulting in 4.04 days.



Year-over-Year (YoY) Growth: Calculated using SAMEPERIODLASTYEAR to compare monthly sales between 2019 and 2020.
