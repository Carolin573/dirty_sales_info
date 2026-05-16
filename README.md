# Data Analyst Project (Portfolio) : Cafe Shop Sales
# Problem Statement
This dataset aim to know the key metrix information of sales of a coffee shop.
# 📐 Objectives
There's several business question need to identify based on dataset, as follows :
1. Generate report that shows all key metrics of the business.
2. What is the total revenue generated for each items.
3. What is the distribution of sold items across location.
4. Which three (3) products generate the highest revenue.
6. Calculate the total sales per month and the running total of sales over time to analyze the trend.
7. Analyze the monthly performance of products by comparing each products sales to both its average sales performance and the previous month's column.
8. Analyze the monthly performance of products by comparing each products sales to both its average sales performance and the previous month's column.
9. Which Items contribute the most to overall sales.
10. Segment product into cost ranges and count how many products fall into each segment.
# 📢 Data Sources
This dataset taken from Kaggle, specifically the "dirty_cafe_sales". It provides information as needed to answer the business metrix. 
# 🧹 Data Cleaning
Dataset need to execute by inspecting duplicate, consistency also standardize and normalize the data then handling missing data so could be get better dataset ready for the better insigh. 
Here's few things applied to clean the dataset : 
1. Remove duplicate if exist. Using Row_number() to remove the duplicate.
2. Data standardization and normalization. Applying Upper just in case mixed-case values appear later in column. Then applying Trim just in case spaces appear later in coloumn.
3. Handling missing data. Filling the blanks by adding a default value. 
# 🔭 Data Exploration
| _Q.1 Generate report that shows all key metrics of the business._

This question able to give the highlight of store's performance. In this context, it measured by quantity, total_spent, item, and transaction id. The result is shown in table below.
 
<img width="316" height="193" alt="image" src="https://github.com/user-attachments/assets/695060d3-09a9-4157-bfa4-1b53e1ec099d" />

Insight :

1. Within one year, the store able to generate sales about $ 88,952.


| _Q.2 What is the total revenue generated for each items._

This question is determine the item with the highest and the least sales. Measured by sum of total spent. 


<img width="530" height="334" alt="image" src="https://github.com/user-attachments/assets/fe5c23b8-4335-4ecb-bccf-3ab1f8561d4b" />

Insight :
1. Salad emerged as item with the highest sales.
2. Cookie contributed with the least of sales.

| _Q.3 What is the distribution of sold items across location_

This question aim to inform the most customer preference when they purchase items. According to the dataset the location between take away and in-store.


<img width="472" height="257" alt="image" src="https://github.com/user-attachments/assets/07d2a260-2a56-4e8c-b929-aa938d51314a" />

Insight :
1. 




