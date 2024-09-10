# Home Sales Analysis with SparkSQL: Results Report

## Overview

This report summarizes the key results and performance findings from the Home Sales Analysis using PySpark and SparkSQL. The primary objective of this analysis was to compute essential metrics related to home sales, such as average prices for homes with specific features. The analysis also involved optimizing query performance by caching tables and partitioning the dataset. This report covers all the steps taken, along with the outcomes, to highlight the results of the assignment.

## Data Overview

The data used in this analysis is from the `home_sales_revised.csv` dataset, which contains information on various homes, including their price, number of bedrooms, bathrooms, floors, living area (in square feet), and the date the home was built. The dataset was loaded into a Spark DataFrame, and the `home_sales` temporary table was created for querying using SparkSQL.

## Objective

The goal of the assignment was to:
1. Calculate the average price of homes based on specific characteristics (e.g., number of bedrooms, bathrooms, floors, square footage, and view ratings).
2. Optimize query performance using table caching.
3. Compare runtime performance between cached and uncached data.
4. Partition the data by the year the home was built and use it to improve query performance.

## Conclusion

This analysis demonstrated the power of SparkSQL in processing and analyzing large datasets. Key takeaways from the analysis include:

### Average Prices: 
Homes with specific features, such as a higher number of bedrooms, bathrooms, and floors, as well as a better view, tend to have higher average prices.
### Optimization: 
Caching and partitioning are highly effective in reducing query runtime, especially when querying large datasets repeatedly.
### Data Trends: 
The housing market's trends, as reflected in this dataset, showed that newer homes and homes with better views command higher prices.
### This project showcased the practical use of SparkSQL for data analysis and optimization in a real-world scenario involving home sales data.
