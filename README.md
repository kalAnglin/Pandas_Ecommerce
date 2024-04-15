# Pandas-Challenge-1

I worked with a LA on AskBSC-307849

## Overview

Use Python's Pandas library to explore, analyze and transform the dataset from fictional e-commerce company. Identify top customers, popular product categories, and calculate profits.

## Purpose
To become more familiar with the aspects of data analysis related to examining, cleaning, processing and extracting useful information from large datasets to gain a better understanding of the data exploration, transformation, and analysis

## Business Advantage [^1]

![E-Commerce](images/Ecommerce.jpeg)

Data analytics are extremely valuable to onlin

## Landscape

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

## Recommendations

[^1]: https://www.comtecinfo.com/rpa/9-benefits-of-analytics-in-ecommerce-industry/
