# LITA_Sales-Performance-Analysis
----

### Project Title: LITA_Sales Performance Analysis using Microsoft Excel, SQL, and Power BI
---

### Objective
---
The main objective of this project is to analyse the sales performance of a retail store by exploring its sales data to uncover key insights such as top-selling products, 
regional performance, and monthly sales trends. Microsoft Excel formulars will be utilized for calculating key metrics and Pivot Tables for data summarization and visualization. SQL Queries were generated and data validated. Power BI was also used to analyse and vitualise the data and produce  interactive Power BI dashboard presentation 

### Data Overview
---
Order ID: Identification code for each product sale 
Customer ID: Unique identification code for each customer in the sales data 
Product: The items sold
Region: The location where each sale was made
Order Date: The date the sales transaction was made
Quantity: The amount of each item sold
Unit Price:  The unique selling price for each item
Total Sales: The total amount realised from the sale of all the products

### Key Metrics
---
Quantity:  Sum of Quantity sold grouped per product, Sum of Quantity sold grouped per Region
Average Sales: Calculated as Sum of Total Sales /Total Quantity sold for each product per Region. Average Sales grouped by product
Total Sales: Calculated as Sum of Total Sales column grouped by Product 
Total Revenue: Sum of the Total Sales column grouped by Region - Total Revenue grouped by Region to measure the Sales performance 

### How Data was used in Excel
---
1. Total Sales by Product: Sum the Total Sales Column and group by Product
2. Total Sales by Region: Sum the Total Sales Column and group by Region
3. Total Sales by Month: Sum the Total Sales Column and group by Month 
4. Total Revenue by Region: Sum the Total Sales Column which is also equal to the Total Revenue and Group by Region
   to identify the most performing Region in terms of the product sold. 

To obtain the Total Sales or Total Revenue, use the formular:
### Total Sales or Total Revenue = Sum (Total Quantity * Total Unit Price)

5. Average Sales per Product: To obtain the Average Sales made per product, use the formular: 
### Average Sales per product = Total Sales per Product / Unit Price per product

![image](https://github.com/user-attachments/assets/f3027f2e-a48e-4e8a-acb4-8600abdf332f)

### Tools and Method Utilised
1. Data Analysis: The Sales Data was analysed with Microsoft Excel with the by generating Pivot Tables which were used to organise, 
summarize, and filter the data for easy understanding. 

2. Data Visualization: Bar charts and Pie Charts were created in Excel for visual representation of key insights and report presentation.

### Steps and Methodology

### Data Preparation
* Import the Sales Data into Excel,
* Clean the Sales Data by checking for any missing values or irregularities. 

### Visual Analysis and Inferences
---
### 1. Total Sales by Product
![image](https://github.com/user-attachments/assets/7ca0fa0f-d311-4e94-be33-2fecfd522d07)

### 2. Total Sales by Region
![image](https://github.com/user-attachments/assets/65d9eac5-510d-4cc6-b180-e7225610bbd0)

### 3. Total Sales by Month
![image](https://github.com/user-attachments/assets/5ecbf28b-1677-488a-b140-b3cd742911ba)

### 4. Total Revenue by Region
   ![image](https://github.com/user-attachments/assets/bf38f856-bec6-4f4b-8ce8-ec155ecd276a)
   
### 5. Average Sales by Product
![image](https://github.com/user-attachments/assets/f28e2a8c-48b4-4f83-97fc-6e754ee40728)

![image](https://github.com/user-attachments/assets/21e9db4e-fdf7-4792-9bf1-327dec30827d)

### How Data was used in SQL
Queries were written to validate the Sales Data

### Tools & Method Utilised in SQL
1. Data Analysis: A LITA_SalesDataPRJ database was first created and the Sales Data inported via the task bar in the database as a flat file (Microsoft Excel Comma Separated Values file) into SQL. The Sales Data was validated by different Query commands as shown below:
    
![image](https://github.com/user-attachments/assets/2f7b46b5-84ef-4e95-a23d-9e73d2795303)

### Steps and Methodology in SQL

### Data Preparation
* Create database
* Import flat file as Microsoft Excel Comma Separated Values file
* Write Queries to validate the following

SQL Query
---
create database LITA_SalesDataPRJ;
![image](https://github.com/user-attachments/assets/1d3a5290-3441-4b66-a501-39ed3b06cc05)
![image](https://github.com/user-attachments/assets/97ddeb04-89ea-4ea0-8755-c4fcdb349e97)

select * from [dbo].[Sales Data]
![image](https://github.com/user-attachments/assets/630e86a5-7e01-4b93-8ec6-f086121399bf)

1. Retrieve the total sales for each product category.
![image](https://github.com/user-attachments/assets/de6660ab-2b49-4f0a-b79b-56eb8077fc2d)

The output of this query is a list of Product categories and their corresponding Total Sales amount. From the output, the revenue from the sale of each product was obtained. The sale of Shoes and Shirts returned the highest revenue, the company should seriously consider review of products sale and consider sales promotions, more adverts and other incentives that can help promote the shirts and shoes more while also finding out what the challenges are with the sale of Socks where the least Revenue was recorded.

2. Find the number of sales transactions in each region.
![image](https://github.com/user-attachments/assets/a545a844-93f5-4e49-8715-24c810239117)
This query gave an output where each Region returned the same count of Sales Transactions. This is a valuable information for understanding the Sales Distribution across different Regions, furthermore it will help the company take strategic decisions in future.

3. Find the highest-selling product by total sales value.
![image](https://github.com/user-attachments/assets/d3f99767-2e56-4026-88fb-6dce5aa01af9)
The sale of Shoes returned the highest revenue for this query, the company should seriously consider a review of product sale and consider sales promotions, more adverts and other incentives that can help promote the shoes more and more.
   
4. Calculate total revenue per product.
![image](https://github.com/user-attachments/assets/041cc0a2-007a-4c02-9c96-eb38addd3dbd)

   
5. Calculate monthly sales total for the current year.
![image](https://github.com/user-attachments/assets/1bd7330a-3715-42ae-bffa-1093881eb673)
![image](https://github.com/user-attachments/assets/064b1451-682d-4129-bbda-6888b93a3af9)


6. Find the top 5 customers by total purchase amount.
![image](https://github.com/user-attachments/assets/3a48bae6-85ad-4b1e-9335-1be14488a686)


7. Calculate the percentage of total sales contributed by each region.
![image](https://github.com/user-attachments/assets/78ba1315-b515-42fb-8067-ca7d40ea4228)


8. Identify products with no sales in the last quarter.
![image](https://github.com/user-attachments/assets/75a3b6c8-cc9e-44b5-8211-c6dd4bce1644)


### How data was used in Power BI
Power BI was used to convert the Microsoft Excel Sales Data into visuals on an interactive dashboard and build a business intelligent report 

### Steps and Methodology in Power BI

### Data Preparation
* Import Microsoft Excel Sales Data Worksheet
![image](https://github.com/user-attachments/assets/edcbec31-b1e6-4aca-bf3c-119c12e9c114)

* Clean data and query
* Model data
* Carry out data Visualization
* Present a Business Intelligent Report

  



   










