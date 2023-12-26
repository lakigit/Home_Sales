# Home_Sales
Module 22 Challenge

![image](https://github.com/lakigit/Home_Sales/assets/138610916/80d1598e-4aae-42e6-b25f-74c37f5200cb)

## Introduction
In this challenge, use knowledge of SparkSQL to determine key metrics about home sales data. Then use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Results
01.
![image](https://github.com/lakigit/Home_Sales/assets/138610916/0efc7ceb-1c62-435b-99ed-6389d3b16031)

Based on the output provided, it can be observed that the maximum average price was recorded in 2021, while 2019 had a comparably lower average price. Conversely, 2020 and 2022 had average prices that were relatively similar to each other. 

02. 
![image](https://github.com/lakigit/Home_Sales/assets/138610916/daa640e8-3c92-4443-9d1b-61d9a3b68e24)

Based on the output, it can be inferred that the average price of a property does not exhibit significant variation for the number of bedrooms(3) and bathrooms(3).

03.
![image](https://github.com/lakigit/Home_Sales/assets/138610916/0d427343-fed0-4341-bfb7-b429f60e7ae0)

The following data depicts the average price of houses with three bedrooms, three bathrooms, and two floors, where the total square footage of the living area is greater than or equal to 2000, for each year. The results suggest that there are fluctuations in the average price across the years. 

04. It is advisable to compute the mean price based on the number of views, which should be carried out for the primary data, cached data, and partition data.
   
- Original Data
    
![image](https://github.com/lakigit/Home_Sales/assets/138610916/f51879e4-f5f3-41e3-8d1a-7f1280ea6e34)

- Cached Data

![image](https://github.com/lakigit/Home_Sales/assets/138610916/368f37ad-f252-4e96-8949-5a54ad9ecd51)

- Partitioned Data

![image](https://github.com/lakigit/Home_Sales/assets/138610916/a587931e-3930-4dd1-9316-8d8b7a44ab8b)

Based on the runtime results, it's evident that both the cached data and the partitioned data have faster runtimes compared to the original data. This can be attributed to the optimizations and benefits offered by caching and using the Partitioning data format.
