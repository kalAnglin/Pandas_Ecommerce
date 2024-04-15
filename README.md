# Pandas-Challenge-1

I worked with a LA on AskBSC-307849

## Overview

Use Python's Pandas library to explore, analyze and transform the dataset from fictional e-commerce company. Identify top customers, popular product categories, and calculate profits.

## Purpose
To become more familiar with the aspects of data analysis related to examining, cleaning, processing and extracting useful information from large datasets to gain a better understanding of the data exploration, transformation, and analysis

## Business Advantage [^1]

![E-Commerce](images/Ecommerce.jpeg)

Data analytics are extremely valuable to online retailers because they provide advanced insights into what customers are likely to buy, the best product mix, and at what price point retailers should be selling in order to maximize profits

## Landscape
Most ecommerce companies are using data analytics to help build a robust supply chain and forecasting inventory, fraud detection, determining future trends,
personalizing recommendations and shopping experience, evaluation marketing strategies, and optimizing pricing.

## Results

### Explore the Data
1.  Identify three item categories had the most entries.
2.  For the category with the most entries, identify which subcategory had the most entries.
3.  Identify which five clients had the most entries in the data and store the client IDs in a list.
4.  Calculate how many total units (qty column) were ordered by the client with the most entries.

### Transform the Data
1.  Create a column that calculates the subtotal for each line using the unit_price and qty
2.  Create a column for shipping price, assuming a shipping price of $7/lb for orders over 50lbs and $10/lb for items 50lbs and under
3.  Create a column for total price using the subtotal and shipping price along with a sales tax of 9.25%
4.  Create a column for the cost of each line using the unit cost, qty, and shipping price (assume the shipping cost is exactly what is charged to the client).
5.  Create a column for the profit of each line using the line cost and line price.

### Confirm Work
 -Confirm work based on the following emails receipts for order ids 2742071, 2173913, 6128929 the respective total price for each order id, remembering each orer has multiple lines.

 ### Summarize and Analyze
 1. Determine how much each of the top 5 clients spent by quantity.
 2. Create a summary dataframe showing the totals of the top 5 clients along with the following information: total units purchased, total shipping price, total revenue, and total profit. Sort by total profit.
 3. Format the data and rename the columns to names suitable for presentation, with currency in millions of dollars. Summarize your findings.
Data analysis showed the out of the five top clients, the most profit was generated from client id 24741 with $36.58 million in total profit. This was calculated by considating the original data into a dataframe that represented the total revenue of the orders for the top five clients and the total cost/expense incurred by fulfilling their orders. The the method used to calculate the total revenue for the top five clients was based on similar method used to calculate revenue for a specific order. The revenue was based on the line subtotal for every order plus the shipping cost, with the shipping cost varying due to the weight of the order. The line subtotal was calculated by multiplying the price of the unit in the order by the quantity. based  id for each client was confirmed based on receipts we based on the the purchased the mostthe five clients which the most orders in the data set, 

## Recommendations

[^1]: https://www.comtecinfo.com/rpa/9-benefits-of-analytics-in-ecommerce-industry/
