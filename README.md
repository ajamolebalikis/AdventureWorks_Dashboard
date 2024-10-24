# AdventureWorks_Dashboard


## Introduction
Adventure Works dataset is avaluable collection of sales data that can be used to guide in making strategic business and insights. Adventure Works is a company that specializes in production of sporting products, clothing and accessories. This dataset provides information on customers, products, dates, sales territory, and sales infromation of their day-to-day transaction of this company spanning from 2015-2017. The aim of exploring this dataset with Powerbi is to drive actionable insights with which the company can be able to satisfy the customers need while achieving maximal profit.

**Disclaimer**: The datasets used are purely for demonstration purposes and do not represent any specific company, institution or country.

## Problem Statement
Adventure Works possesses a rich repository of sales and customers data, but it is fragmented and often not thoroughly analyzed, making it difficult to grasp customers need and effectively boost sales. This projects aims to dive deeply into the data to reveal patterns in customer behavior, product profitablity and sales trends. By uncovering these insights, Adventure Works can be more informed to make decision to enchance marketing strategies, refine product offerings, and ultimately drive increased sales.

## Skills Demonstrated
The following Power Bi features are incorporated.
-DAX
-New Measures
-Filters
-Modelling

## Modelling 
The data modelling schema used here is star schema. It has the Facts Table which is the FactSales Table surrounded by the Dimensions table ehich are the remaining table in dataset. Each Dimension table has a one-many relationship with the FactSales Table as it contains the primary key of each dimension table connecting to her.

## Visualizations
The report encompasses four pages:
1. The Overview Page
2. Sales Performance
3. Product Performance
4. Customer Performance.


## Pages and Key Metrics

### 1. Overview
This page contains various KPI Revenue, Profits, Orders and Returns. It also shows various-visualizaton like:

Revenue Trend: This hows a trend analysis of the total revenue of the year with 2016 been the highest peak of the analysis. This implies that sales are the highest at this time of the year and thus seasonal campaigns and new products launches can contribute to this.
  
Product Performance: Here we see the products performance by revenue, orders and profit and with AWC Logo Cap being the highest with 1126  orders, 20,452.18 revenue, 6953.67 profit. This could be as a results of seasons and also having low cost production. Thus sales of these products should be maximized.
  
Category Performance: Here we see the Category performance by orders, revenue and profit and with which accessories is the highest with the 9,429 orders, $204,015.16 revenue, $128, 105.89 profit. This could be as a results of strong customer interest and effective marketing strategies.

Continent Performance: This is the continent performance by orders, revenue and profit with which North America is the highest with 8734 orders, 4,158,428.25 revenue, 1, 740,361.04 profit. North America has the highest orders, revenue and profit hus they have the highest valuable market opportunities. Thus concentrated focus should be made on the country for marketing.

![<img width="650" alt="Overview" src="https://github.com/user-attachments/assets/06718fab-2396-409f-b7e4-8a03cfadfdcb">



### 2. Sales Performance
This page contains various KPIs like Products, Regions, Countries and categories recorded. The page also contains varoius visualization like:

 Orders by Year: This shows a trend analysis of the total orders by year with which year 2016 is the highest of the analysis. This implies that sales were high ain the year 2016 compared to 2017 thus more awarenes and improvement in services hould be encouraged so as to aim high and get more sales.

 Orders by Category Name: This shows the total orders in each categories. The Categoty with the highest sales is Accessories with 9.4K orders.
  
 Orders by Product Name: This shows the total orders by products. The products with the highest orders is Water bottle with 1723 orders and also patch kit with 1485 orders and awc logo cap with 1126 orders.

 Orders by Country: This show the total orders by country. The country with the highest orders is the United States with 7.2k orders. Thus concentrated focus should be made on this country for marketing.

 Revenue and Profit by Month: TThis shows a trend analysis of the total revenue and profit by month May and June being the highest peak of the analysis. This implies that sales are the highest at this time of the year and thus seasonal campaigns and news products launches can contribute to this.

 ![<img width="665" alt="Sales performance" src="https://github.com/user-attachments/assets/d025ca8f-3084-47ce-ac09-687a7d88b1e9">

  

### 3. Products Performance
This page contains various charts and KPIs like Products, OrderQuantity, Profit, ProductCost. It also contains slicer like Year, Products, Country and category.
 *Top 10 Products BY Revenue*: Here we see the top 10 products by revenue and with the Road 150 Red being the highest with $0.64M as Revenue. This could be as a results of the product having low product cost. Thus sales of this products should be maximized.
  
- *Top 5 Products by Orders*: This shows the total orders by products. The products with the highest orders is Water bottle with 1723 orders and also patch kit with 1485 orders and awc logo cap with 1126 orders.

- *Products by Category Name*: This shows the total products in each catagories. The category with the highest numbers of products is components with 132 products, followed by bikes with 97 products, clothing with 35 products and accessories with 29 products.
 
- *Top 5 Products by Region*: This shows the total products in each regions. The region with the highest numbers of products is Canada with 293 products.

- * Top 5 Products by Profit*:  Here we see the top 10 products by revenue and with the Road 150 Red being the highest with $251,484 as Profit. This could be as a results of the product having low product cost. Thus sales of this products should be maximized.

![<img width="675" alt="Products performance" src="https://github.com/user-attachments/assets/bb7ada95-0061-410a-be8c-515fe13cf684">


  

### 4. Customer Performance
This page shows ana analysis of the customer Adventure Works. It answers some questions as to the reason behind the purchasing power of the customers. It shows several KPIs like Customers, Annual Income, Total children and occupation. I coontains several visualizations like 

- *Customers by Marital Status*: Here we that larger amount of the customers are married 54.09% and the remaining customers fall under the single customers with 45.91% .
  Most of the customers were *Married, with a total of **9.81K* customers.

- *Profit and Revenue by Gender*: Here we can see that the female customers generate the highest revenue with 5.4M while the male generated the lowest revenue with 5.2M. However, both  males and females contributed equally to the profit.

- *Customers by Occupation*: Here we can see that most of the customers are Professionals while few customers fall under Manual Occupation. Thus further corroborates that more revenue and profit is generated from the professional and this can be as a result of their income.

- *Profit by Age Group*: We can see here that the Older generation generate the highest profit with 2.17M followed by the Gen-Xers and the millennials generate the lowest amount of profit which is 0.47M.

  
- *Customers by Age Group*: This shows the number of customers we have in each age group with Old people with the highest with 9.29k customers, followed by the Gen-Xers with 6.63k customers ans the millennials with 2.23k customers.


![<img width="662" alt="Customers Performance" src="https://github.com/user-attachments/assets/0ff1f947-1e1d-46ff-8653-6dc5e46a06aa">






## Recommendations

Based on the analysis in the dashboard, the following recommendations are made:

1. Boost Customer Engagement and Personalization: Utilizing the existing segmentation based on generation and occupation, Adventure Works should refine its strategies to personalize customer interactions.Tailored marketing campaigns and recommendations will enhance engagement, boost conversions, and improve retention rates.
   
2. Optimize Product Portfolio: Prioritize the optimization of the product portfolio by focusing on high-margin and high-demand items, such as the Mountain-200 series. By understanding the preferences of different generational and occupational segments, Adventure Works can better align its product offerings with customer needs.
   
3. Expand Geographically: Adventure Works should intensify its marketing efforts in Europe and explore expansion into Africa and Asia to unlock new growth opportunities. Given the strong performance in Australia and the U.S., targeting these new regions can help the company explore additional opportunities.

4. Seasonal Promotions and Bundling: Use seasonal data and insights from customer segmentation to strategically schedule promotions and create product bundles for peak shopping periods. This strategy will help Adventure Works increase the average order value and encourage more purchases during high-demand times.
   
5. Develop Customer Loyalty Programs: Leverage segmented data to create targeted loyalty programs that offer exclusive benefits, such as discounts and early access to new products. This will enhance customer retention and foster greater advocacy among high-value segments.

6. Digital Transformation and Personalization: Upgrade the e-commerce platform to deliver personalized recommendations based on customer segmentation. This enhancement will improve the online shopping experience for each customer segment, boost conversion rates, and drive sales.


 ## Conclusion
 Implementing these recommendations will optimize operations, enchance profitablity, and boost Adventure Works Company competitive edge in the retail landscape and also help the organization move forward.


** THANK YOU!**

