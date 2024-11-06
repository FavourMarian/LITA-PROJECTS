# CAPSTONE PROJECT 1

### ABSTRACT
This project aims at getting insights from the sales performance of a retail store and inducing step to take for the betterment of the company. The analysis covers the sales overview for both 2023 and 2024, regional breakdown, product performance based on the quantity sold, and revenue generated and sales gotten over time (monthly and quarterly). The results reveal the top selling products, the regions which certain products sell better and the revenue generated by each product.

## INTRODUCTION
In today's competitive market, businesses are constantly looking for ways to optimize and improve their performance and understand customer behaviors and purchases to gain a strategic edge. this project was initiated to address the need for a comprehensive analysis of sales data, enabling the identification of trends and opportunities within various regions. By diving deep into this sales data, this analysis will uncover patterns that inform effective decision-making for pricing, product promotion and resource allocation.

### Objectives
1. To support the company in making data-driven decisions that will enhance profitability and customer satisfaction
2. The insights derived will ultimately guide to strategies to improve market positioning
3. To identify high potential product
4. To predict and anticipate shifts in customer demand


## DATA INFORMATION
### Data sources
The data used in this project was obtained from the Incubator Hub. It includes detailed records of transactions, customer demographics, product information and regional sales distribution.

### Data Collection
The data used was collected and complied through transaction logging. This ensures that the dataset represents an accurate record of customer interactions and purchasing patterns over a year and eight months.

### Data Characteristics
The dataset includes the following variables:
1. OrderID : Unique identification of each order purchased by the customers
2. CustomerID : Unique identification for each customer
3. Product : Items purchased by the customers
4. Region : The regions where the purchases occured
5. Order Date : Date when the items(products) were purchased
6. Quantity : The amount of items purchased in each transaction
7. Unit Price : The cost price of each item purchased
8. Revenue : The revenue generated when the items were sold
9. Sales : the money gotten when the item were sold
10. Average : The average of sale

## BASIC STATISTICS IN THE DATASET
1. Total Sales: 2.1 Million
2. Average Sales: 211.8
3. Total Customer: 9921
4. Marginal Profit: 1.8 Million
5. Total Quantity: 68.5K

## METHODOLOGY
### Data Preparation
* Removing duplicates
Eliminated duplicated records to ensure Data Quality

* Adding New Columns
Added new columns sales and revenue by multipling the quantity of the product purchased by the respective unit price, added an average column for the sales/revenue of products purchased and also added a calculated column for the Marginal profit made in the company over the space of a year and eight months.

## EXPLORATORY DATA ANALYSIS (EDA)
After cleaning the data in excel and making pivot tables for analysis, it was exported to SQL for further analysis and finally to power BI for creation of dashboard. The following were carried out: 
* Descriptive statistics: Excel was used to calculate average sales, total sales and revenue by region and product, providing a summary of sales volume and revenue distribution. SQL queries calculated total sales and revenue for product, total revenue and sales per region, monthly sales and the most purchased products, establishing overview of the dataset. Summary cards in Power BI displayed key metrics such as total revenue, average sales, marginal profit etc, in a visually concise format.
* Data filtering and segmentation: Excel's filtering and pivot tables allowed segmentation by region, product and year, revealing targeted insights. SQL's WHERE and GROUP BY clauses filtered and grouped by region and product, to isolate specific insights. slicers and filters in Power BI allowed segmentations of region, product and year, enabling dynamic drill-down analysis of specific data groups.
* Dashboard creation: Excel's Pivot table enabled structured summaries, allowing for dynamic updates to analyze various sales dimensions. Aggregated data in SQL formed the foundation for dashboards, supporting seamless integration with other tools for detailed analysis. Power BI's interactive dashboards provided a real-time view with slicers for in-depth analysis across customer and product dimensions.

## TOOLS USED
1. Microsoft Excel: Used for data cleaning, analysis and creating pivot visualization [DOWNLOAD HERE](HTTP://WWW.MICROSOFT.COM/EN-US/MICROSOFT-365/EXCEL)
2. MIcrosoft SQL server (SMSS): Used for pre-processing [DOWNLOAD HERE](HTTP://WWW.MICROSOFT.COM/EN-US/SQL-SERVER/SQL-SERVER-DOWNLOADS)
3. Microsoft Power BI desktop: Used for creating dashboards and visualization [DOWNLOAD HERE](HTTP://WWW.MICROSOFT.COM/EN-US/DOWNLOAD/DETAILS.ASPX?ID=58494)

## ANALYSIS
### Dashboard Overview
![sales 1](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/sales%201.png?raw=true)
![sales 2](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/sales%202.png?raw=true)

## Data Analysis and Insight Generation
This visualization tells us what the customers patronize the most and how they shop. this reveals to us what they purchase the most and the least and at what time and period they shop most and also the regions with the highest revenue generated.
1. REGIONAL BREAKDOWN : The pie cahrt and bar chart visualization on region revealed the rate and revenue generated by each region. The region with the highest rate and revenue is South with a rate of 44.16% with 928K generated, then the East had 23.13% with 486K generated, the North had 18.42% and 387K generated, and lastly the West had 14.29% and 300K generated. The difference between the South and Other regions is a very huge which means that the other regions are underperforming when it comes to certain products, perhaps due to the stores in those regions not having what the customers are more in-need of in relations to their environment.

   RECOMMENDATION : conduct a targeted marheting campaign focusing more on the most popular products for each region and giving didcounts and promotion to the products that are not-so popular to encourage customers to purchase them. it is also recommended to move the most demanded products of a region to that region to control loss of profit in a region, for example shoes are purchased better in the south bringing more than 500K but in the west, it brings just 30K so brings the more shoes to the south where they are more in demand is good for company profit and customer satisfaction.
   
2. PRODUCT PERFORMANCE :  The bar and column charts visualization on sales reveal the revenue generated by each product and that certain products perform better. the product with the highest revenue is Shoe which generated 613K, followed by Shirt with 486K, Hat with 316K, Gloves with 297K, Jacket with 208K and finally Socks with 181K with the lowest revenue. this might also be as a result of customer want in relations to environment.

   RECOMMENDATION : Allocate more marketing resources to the high and better-performing products being shoes and shirts and hats and promote them on digital and social channels. the other can be introduced as complementary products to encourage upselling and analyze trend-basd demand spikes to adjust stock levels in advance to prevent profit loss.
   
 3. SALES TREND OVER TIME : The column and line charts Visualization represent the monthly and quarterly sales repectively. The monthly reveals that febuary has the highest revenue turnover and that september has the lowest revenue turnover. the charts also reveals seasonal spikes during seasons such as Winter and Summer and drop-down during spring and autumn, the charts shows a rise during the Winter months(December, january, February) and a fall during the Spring months(March, April, May), then another rise in the Summer months(June, July, August) and finally a fall in the Autumn months(September, October, November), in a way the monthly trend moved like a wave. The quarterly line graph shows that the highest quarter is the first quarter and the lowest is the last quarter and it also moves like a wave.

    RECOMMENDATION : Plan targeted marketing campaigns around peak sales periods to maximize engagement and offer special discounts or promotions during off-peak periods to drive sales and smooth out fluctuations. prepare contingency plans for significant trend fluctuations, and also track trending products to understand customer preferences and develop new and improved versions.

##  CONCLUSION
The analysis of sales data provided valuable insights into trends, product performance and regional breakdown. key findings highlights the importance of understanding sales dynamics over time, optimizing inventory and leveraging targeted marketing strategies. By recognizing seasonal trends and identifing high-performing products and customer segment, the company can make data-driven decisions to enhance sales performance. in conclusion, this project underscores the potential for growth through infermed decision-making. By strategically responding to identified trends and patterns, the company is well-positioned to boost sales, increase profitability, and achieve sustainable growth in the coming years.

------------------------
-------------------------
----------------------------
---------------------------------
-----------------------------
---------------------------
---------------------------
# CAPSTONE PROJECT 2

 ### ABSTRACT
 This report aims at analyzing customer data and understanding the subscription trends to know the best action to take for the subscription types not doing well. It presents an in-depth analysis of customer subscription service data, focusing on segmentation, cancellation trends, and overall subscription patterns. the analysis aims to understand customer behaviour, track subscription types, and identify key trends in cancellations and renewals. Using a combination of MS Excel, SQL, and Power BI, the data was cleaned, organized, analyzed, and visualized to reveal insights into customer behaviour. 

 ## INTRODUCTION
 In the recent competitive nature of market, understanding customer subscription behaviour is essential for fostering long-term growth and maintaining customer loyalty. Subscription-based businesses rely heavily on data insights to refine their marketing strategies, enhance customer experience, and improve product offerings. this project focuses on analyzing customer subscription data to uncover patterns and factors that influence customer cancellations and retention. the dataset used in this project comprises records of customer transaction and detailing attributes. Through the use of Excel pivot tables, SQL queries and Power BI dashboards, the data was cleaned, analyzed and visualized to offer a clear picture of the company's subscription dynamics.

 ### Objectives
 1. To analyze regional performance
 2. To understand the characteristics and preferences of different customer purchases
 3. To identify key trends in cancellations and renewals

## DATA INFORMATION
### Data sources
The data used in this project was obtained from the Incubator Hub. It includes detailed records of transactions, customer demographics, product information and regional sales distribution.

### Data Collection
The data used was collected and complied through transaction logging. This ensures that the dataset represents an accurate record of customer interactions and purchasing patterns over a year and eight months.

### Data Characteristics
The dataset includes the following variables:
1. CustomerID : A uniques identification of each customer
2. Customer Name : Names of the customers
3. Region : The regions where the subscriptions occured
4. Subscription Type : Type of subscription purchased
5. Subscription Start: The date of subscription
6. Subscription End : the date of subscription expiration
7. Canceled : If the subscription was canceled or not
8. Revenue : The revenue generated from each purchased
9. Subscription Duration : The duration of each purchased subscription

## BASIC STATISTICS IN THE DATASET
1. Total Revenue : 67.5 Million
2. Average Revenue : 1999
3. Average Duration : 365.35
4. Total Customer : 33787
5. Total Order : 33787

## METHODOLOGY
### Data Cleaning
* Removing duplicates
Eliminated duplicated records to ensure Data Quality

* Adding New Columns
Added new columns sales and revenue by multipling the quantity of the product purchased by the respective unit price, added an average column for the sales/revenue of products purchased and also added a calculated column for the Marginal profit made in the company over the space of a year and eight months.


## EXPLORATORY DATA ANALYSIS (EDA)
After cleaning the data in excel and making pivot tables for analysis, it was exported to SQL for further analysis and finally to power BI for creation of dashboard. The following were carried out: 
### Excel Analysis : Used for initial exploration and basic calculations.
1. Data Preparation
* Data cleaning : Eliminated duplicated records to ensure Data Quality.
* New columns calculated : Calculated the time between subscription start and subscription end date for each subscriber.
2. Basic Subscription Statistics
* Summary table : Presented subscriber count, average subscription duration, average monthly revenue, and most popular subscription type.
3. Customer Distribution and Segmentation
* Subscription count by type : Created pivot tables to display counts for each subscription type (e.g., monthly, quarterly, annual)
* Subscriber segmentation : used pivot tables to segment subscribers based on activity (retained, canceled)

### SQL Analysis : Used for in-depth data queries and subscriber insights.
1. Retrieved the total number of customers from each region.
2. Found the most popular subscription type by the number of customers.
3. Found customers who canceled their subscription within 6 months.
4. Calculated the average subscription duration for all customers.
5. Found customers with subscriptions longer than 12 months.
6. Calculated total revenue by subscription type.
7. Found the top 3 regions by subscription cancellations.
8. Found the total number of active and canceled subscriptions.

### Power BI Analysis : Offers interactive dashboards and visuals for exploring subscription trends. 
1. Key Metrics Dashboards 
* KPI Cards : Displayed key metrics()
* Interactive slicers : Added slicers for regions and subscription types, allowing viewers to filter insights by their area of interest.
2. Subscriber Distribution and Segment Analysis
* Subscrption count by region and type : Visualized using interactive bar charts, showing which regions have the highest subscriptions and subscription types are most popular.
* Customer segmentation dashboard : Created visuals to differentiate segments by region and subscription type.
 
## TOOLS USED
1. Microsoft Excel: Used for data cleaning, analysis and creating pivot visualization [DOWNLOAD HERE](HTTP://WWW.MICROSOFT.COM/EN-US/MICROSOFT-365/EXCEL)
2. MIcrosoft SQL server (SMSS): Used for pre-processing [DOWNLOAD HERE](HTTP://WWW.MICROSOFT.COM/EN-US/SQL-SERVER/SQL-SERVER-DOWNLOADS)
3. Microsoft Power BI desktop: Used for creating dashboards and visualization [DOWNLOAD HERE](HTTP://WWW.MICROSOFT.COM/EN-US/DOWNLOAD/DETAILS.ASPX?ID=58494)

## ANALYSIS
### Dashboard Overview

![customer 1](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/customer%201.png?raw=true)
![customer 2](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/customer%202.png?raw=true)

## Data Analysis and Insight Generation
this Visualization reveals some intriguing patterns and trend from understanding customer behavior, tracking subscription types, and identifying key trends in cancellations and renewals of the various subcription types available in the company.
1. SUBSCRIPTION TREND : Subscription numbers showed fluctuations over time, monnthly, quarterly and yearly. There was a steady flow of revenue monthly until it declined in the month of september, it droped from 6.75 Million in August to 3.37 Million in September. Quarterly, there was a steady trend from the first to the second quarter but by the third quarter it declined from 20 Million to 16 Million and to 10 MIllion by the forth quarter. And finally yearly, from 2022 to 2023 there was a decline from 40 Million to 27 Million. This implies the purchases decline after a period of time.

   RECOMMENDATION : Increase marketing efforts during peak periods to capitalize on natural customer interest. And introduce targeted promotions and membership discounts during slower periods to encourage new sign-ups.
   
2. TYPE PERFORMANCE : The bar chart reveals that the basic subscription type which accounts for 50% of all subscriptions emerges as the most sort out by the subscribers generating over 17 Million more than preminum and standard and it is also the subscription type with the no cancellation records. This shows that more subscribers appreciate the simplicity and affordability of the basic subscription type than they do the other types.

   RECOMMENDATION : Perform targeted marketing on the benefits of the basic subscription type while making adjustments to the other subscription types. promotions such as discounts and memberships can be very effective in driving the purchase of other subscription types.
   
3. REGIONAL BREAKDOWN : the Visuals presenting the regions showed two things, the first being that each region had the same amount of revenue generated but with different sales rate with the East having the highest (25.11%) and the North having the lowest (24.90%). the second being that the East unlike every other region where on occations subscribers would cancel their subscriptions, there was no record of cancellations in the East which might be as a result of higher customer engagements or effective local marketing.

   RECOMMENDATION : Strengthen marketing efforts in the other regions, using strategies that have worked in the East region.
   
4. AVERAGE SUBSCRIPTION DURATION : The average subscription duration each year is 365 days which implies that the subscribers are satisfied with the services rendered as they renew their  subscriptions yearly on average.
 
   RECOMMENDATION : Seeing that the average duration per year is good, implement engagement tatics like surveys and periodic check-ins to keep the subscriber engaged over time.

## CONCLUSION
The analysis provides valuable insights into customer behaviour, preferences, and regional trends. Key findings reveal diverse customer needs across regions, varying product preferences, and distinct demographic characteristics that impact purchasing behaviour. In conclusion, the analysis of customer data emphasizes the importance of a customer-centric approach. Adapting strategies to meet the needs of distinct customer segments will position the company for continued success, ensuring it remains responsive to evolving customer expectations and competitive within the market. 

--------------------------
-------------------------
-------------------------
## ADDITIONAL RESOURCES
1. My Excel Worksheet [Click Here](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/My%20LITA%20Capstone%20Dataset.xlsx)
2. My SQL [Click Here for sales data](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/Capstone%201.sql)
          [Click Here for Customer data](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/Capstone%202.sql)
3. My Power BI [Click Here for sales data](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/MY%20PROJECT%201.pbix)
               [Click Here for Customer data](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/PROJECT%202.pbix)
4. The Empty Worksheet [Click Here](https://github.com/FavourMarian/LITA-PROJECTS/blob/main/My%20LITA%20Capstone%20Dataset.xlsx)
