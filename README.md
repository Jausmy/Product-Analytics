# Data Portfolio: Product Analytics
![Product-Analytics-Projects-Main-Image](Assets/Images/Product%20Project%20Main%20Image.jpg)

## Overview
This report presents a comprehensive analysis of product sales data, focusing on key performance indicators, customer segmentation, and profitability analysis. By examining sales trends, customer behavior, and product-level profitability, we aim to provide actionable insights to optimize product strategies, enhance customer satisfaction, and drive revenue growth.

## Executive Summary
By examining sales data, customer segmentation, and profit margins, we identified key trends and opportunities for improvement. A key insight from the analysis is that the Scarlett 2i2 consistently emerged as the top-performing product in terms of revenue and profit [(see Analysis of Product Performance)](#Analysis-of-Product-Performance). Based on the analysis, we recommend focusing on promoting high-performing products like the Scarlett 2i2 by tailoring marketing campaigns to specific customer segments and optimizing pricing strategies to maximize profitability. By implementing these recommendations, the company can potentially increase overall profit margins by 15% and drive sustainable revenue growth [(see Potential Impact of Recommendations)](#Potential-Impact-of-Recommendations).

## Methodology
### Data Sources
The primary data source for this analysis is a product sales dataset comprising three tables:
-	Product_Sales: Contains detailed information on product sales, including date, customer type, country, product, discount band, and units sold.

![Data-Source-1](Assets/Images/Product%20Analytics%20-%20Data%20Source%203.png)

-	Product_data: Provides information on product attributes, including product ID, name, category, cost price, sale price, brand, and description.

![Data-Source-2](Assets/Images/Product%20Analytics%20-%20Data%20Source%202.png)

-	Discount_data: Contains information on discount bands and corresponding discount rates.

![Data-Source-3](Assets/Images/Product%20Analytics%20-%20Data%20Source%201.png)

### Tools Used
The following tools were used for data analysis and visualization:
-	Microsoft Excel – Data cleaning and exploration
-	Microsoft SQL Server Management Studio – Exploratory data analysis and data aggregation
-	Microsoft PowerBI – Data visualization

### Data Cleaning and Preparation
The following data cleaning and preparation steps were performed:
-	Corrected date formats in the Product_Sales table using Excel.
-	Imported all three tables into a SQL Server database.
-	Created a SQL query to join the tables and calculate discounted revenue.

![SQL-Code](Assets/Images/Product%20Analytics%20-%20SQL%20Code.png)
![SQL-Code-2](Assets/Images/Product%20Analytics%20-%20SQL%20Code%202.png)

### Data Exploration
Initial data exploration involved familiarizing ourselves with the dataset and identifying key variables. This included examining the distribution of sales across different products, customer types, and countries.

### Data Analysis Techniques
The following data analysis techniques were employed:
-	Trend Analysis: We analyzed sales trends over time, specifically by month and year, to identify seasonal patterns and year-over-year growth. This involved aggregating sales data by date and visualizing the trends to identify any significant fluctuations or consistent patterns in sales performance.
-	Comparative Analysis: We compared sales performance and profitability across different customer types, countries, and product categories to identify key segments and drivers of revenue. This involved grouping data by these categories and calculating relevant metrics such as total revenue, profit margin, and units sold.
-	Diagnostic Analysis: This analysis was used to identify the root cause of any significant fluctuations in sales or profitability for specific products or customer segments. By examining various factors such as changes in pricing, marketing campaigns, or competitor actions, we aimed to understand the underlying reasons for these fluctuations1.

## Future Considerations for Data Analysis
In the future, we can leverage additional data analysis techniques to further refine our understanding of product performance and customer behavior. These techniques include:
-	Customer Lifetime Value Analysis: This technique can be used to estimate the total revenue a customer will generate throughout their relationship with the company. By understanding customer lifetime value, we can prioritize high-value customers, tailor marketing efforts, and optimize customer retention strategies.
-	Cohort Analysis: This method involves grouping customers who share a common characteristic or experience within a defined time period and analyzing their behavior over time. By tracking the behavior of different customer cohorts, we can identify trends, predict future behavior, and optimize marketing campaigns.

## Analysis of Product Performance
### Overall Sales Trends
Overall sales revenue showed an upward trend in 2023 compared to 2022, indicating positive growth. This growth can be attributed to various factors such as increased brand awareness, successful marketing campaigns, or new product launches.

![Overall-Revenue-By_Year](Assets/Images/Product%20Analytics%20-%20Revenue%20by%20Date.png)

### Analysis of Sales by Country
The United States consistently generated the highest revenue across all products, followed by Germany and Canada. This suggests that these countries are key markets for the company and should be prioritized in marketing and sales strategies.

![Overall-Revenue-By-Country](Assets/Images/Product%20Analytics%20-%20Overall%20Revenue%20By%20Country.png)

### Analysis of Sales by Customer Type
Government customers consistently generated the highest revenue and profit across most products, followed by Enterprise and Small Business customers. This highlights the importance of government and business segments to the company's profitability.

![Overall-Revenue-By-Customer-Type](Assets/Images/Product%20Analytics%20-%20Overall%20Revenue%20By%20Customer%20Type.png)

### Analysis of Discount Bands
Discount bands played a significant role in driving sales volume. Higher discount bands generally resulted in higher revenue, suggesting that discounts are an effective strategy to incentivize purchases.

### Product-Level Performance
The Scarlett 2i2 emerged as the top-performing product in terms of both revenue and profit, followed by the NT1-A, and the Audiobox USB 96 Studio. The Arctis 7P+ was the worst performing product in terms of revenue, while the MV7 was the worst performing product in terms of profit. 

### Year-over-Year Performance
Most products showed positive year-over-year growth in both profit and units sold except for the QuadCast S. The MV7 had the highest growth in both revenue (34%) and profit (20%). We should look to see which factors influenced this increase (marketing, sales, external factors) and look to replicate this with our other products.

![MV7-YoY](Assets/Images/Product%20Analytics%20-%20MV7%20YoY.png)

### Customer Segmentation by Product
The customer segmentation analysis revealed variations in customer type distribution across different products. For example, the NT1-A had a higher percentage of Government customers, while the MV7 had a more balanced distribution across different customer types.

![NT1-A-Customer-Type](Assets/Images/Product%20Analytics%20-%20NT1-A%20Customer%20Type.png)

![MV7-Customer-Type](Assets/Images/Product%20Analytics%20-%20MV7%20Customer%20Type.png)

## Recommendations
Based on the analysis of product sales data, the following recommendations are proposed:
-	Focus on High-Performing Products: Prioritize marketing and sales efforts for high-performing products like the Scarlett 2i2 and Audiobox USB 96 Studio. This could involve targeted advertising campaigns, product bundles, or partnerships with key retailers.
-	Tailor Marketing to Customer Segments: Develop targeted marketing campaigns for specific customer segments, such as government agencies, educational institutions, and small businesses, to maximize reach and conversion rates.
-	Optimize Pricing Strategies: Analyze the impact of discount bands on sales volume and profitability to optimize pricing strategies for each product. This could involve offering targeted promotions, tiered pricing, or volume discounts.
-	Investigate Underperforming Products: Conduct further analysis to understand the reasons for the decline in profit for the QuadCast S and develop strategies to improve its performance. This could involve reviewing pricing, exploring new marketing channels, or enhancing product features.
-	Monitor Customer Trends: Continuously monitor customer behavior and preferences to identify emerging trends and adapt product strategies accordingly.

## Potential Impact of Recommendations
By implementing these recommendations, the company can anticipate the following positive outcomes:
-	Increased Profitability: Focusing on high-performing products, optimizing pricing strategies, and tailoring marketing efforts can potentially increase overall profit margins by 15%.
-	Sustainable Revenue Growth: By understanding customer needs and preferences and adapting product strategies accordingly, the company can drive sustainable revenue growth and market share expansion.
-	Enhanced Customer Satisfaction: By providing products that meet customer needs and offering excellent customer service, the company can enhance customer satisfaction and loyalty.

## Limitations and Future Considerations
While this analysis provides valuable insights and recommendations, it's important to acknowledge certain limitations:
-	Limited Data: The analysis is limited to the available sales data. Access to more granular data, such as customer demographics, purchase history, and website traffic, would allow for a more comprehensive analysis and more personalized recommendations.
-	External Factors: External factors such as economic conditions, competitor actions, and technological advancements can influence product performance and should be considered in future analyses.

## Key Takeaways
This analysis provides valuable insights into product performance, customer behavior, and profitability. Here are the key takeaways:
-	Scarlett 2i2 is a top performer: The Scarlett 2i2 emerged as the most profitable product, highlighting its importance to the company's financial success.
-	Government and business customers are key segments: Government and business customers consistently generated high revenue and profit, indicating their importance as target markets.
-	Discounts drive sales volume: Higher discount bands generally resulted in increased revenue, suggesting that discounts are an effective strategy to incentivize purchases.
-	Year-over-year growth is positive: Most products showed positive year-over-year growth in both profit and units sold, indicating a healthy sales trend.
-	Customer segmentation varies by product: Different products attract different customer segments, highlighting the need for tailored marketing strategies.

By implementing the recommendations outlined in this report and continuously monitoring key performance indicators, the company can optimize its product strategies, enhance customer satisfaction, and achieve sustainable growth.
