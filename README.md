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
Data analysis showed the item category of consumables had the most orders with 6,424 orders for bathroom supplies. Analysis also showed out of the five top clients, the most profit was generated from client id 24741 with $36.58 million in total profit. Total profit was calculated by considating the original data into a dataframe that represented the total revenue of the orders for the top five clients and the total cost/expense incurred by fulfilling the orders for the top five. 

The method used to calculate the total revenue for the top five was based on similar method used to calculate revenue for a specific order. In the case of the top five, a loop function which included a "find_client_price" function was used to identify the client and return the sum of units, shipping cost, total revenue and cost, and the total profit for each of the top five. The "find_client_price" function was confirmed by using the equivalent "find_order_price" function to calculate the total price for orders ids 2742071, 2173913, 6128929. The totals for each were compared to emailed receipts provided for the respective order ids.

The calculation for revenue was based on the line subtotal for every order plus the shipping cost, with the shipping cost varying due to the weight of the order. The line subtotal was calculated by multiplying the price of the units in the order by the quantity. The calculation for cost was based on the cost of the units in the order, multiplied by the quantity of units plus the shipping price. 

## Recommendations
To utilize the results of the data analysis to present personalized recommendations to the top five clients would helpful establishing a customer rapport, forecasting future inventory, and optimizing profits.

[^1]: https://www.comtecinfo.com/rpa/9-benefits-of-analytics-in-ecommerce-industry/
