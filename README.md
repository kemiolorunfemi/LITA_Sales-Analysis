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
---
1. Data Analysis: The Sales Data was analysed with Microsoft Excel with the by generating Pivot Tables which were used to organise, 
summarize, and filter the data for easy understanding. 

2. Data Visualization: Bar charts and Pie Charts were created in Excel for visual representation of key insights and report presentation.

### Steps and Methodology
---

### Data Preparation
---
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

### How Data was used in SQL
---
Queries were written to validate the Sales Data

### Tools & Method Utilised in SQL
---
1. Data Analysis: A LITA_SalesDataPRJ database was first created and the Sales Data inported via the task bar in the database as a flat file (Microsoft Excel Comma Separated Values file) into SQL. The Sales Data was validated by different Query commands as shown below:
    
![image](https://github.com/user-attachments/assets/2f7b46b5-84ef-4e95-a23d-9e73d2795303)

### Steps and Methodology in SQL
---

### Data Preparation
* Create database
* Import flat file as Microsoft Excel Comma Separated Values file
* Write Queries to validate the following

1. Retrieve the total sales for each product category.
   ![image](https://github.com/user-attachments/assets/e3def7b7-0222-45dd-b986-906073b95046)

2. Find the number of sales transactions in each region.
![image](https://github.com/user-attachments/assets/61ce6b4a-9b5e-40ee-8e49-18181b6e325f)

3. Find the highest-selling product by total sales value.
![image](https://github.com/user-attachments/assets/ff9bc9ce-b2ce-4488-b0c6-f8acc3a340f1)
   
4. Calculate total revenue per product.
![image](https://github.com/user-attachments/assets/6098e830-09d4-4fb4-9629-6060d90278fa)
   
5. Calculate monthly sales total for the current year.
![image](https://github.com/user-attachments/assets/48605ade-999b-48fc-b8c8-29ce7d588ae2)
![image](https://github.com/user-attachments/assets/3fc67383-f73e-4848-889e-91169fc7b145)

6. Find the top 5 customers by total purchase amount.
![image](https://github.com/user-attachments/assets/d4a34850-8d4b-429d-8d63-0046c164defd)

7. Calculate the percentage of total sales contributed by each region.
![image](https://github.com/user-attachments/assets/63cc8778-0a13-4de7-8921-fd383bc63f0d)

8. Identify products with no sales in the last quarter.
![image](https://github.com/user-attachments/assets/19400848-f36c-42ae-a14f-a0c4aeff0d55)

### How data was used in Power BI
---
Power BI was used to convert the Microsoft Excel Sales Data into visuals on an interactive dashboard and build a business intelligent report 

### Steps and Methodology in Power BI
---

### Data Preparation
* Import Microsoft Excel Sales Data Worksheet
* Clean data and query
* Model data
* Carry out data Visualization
* Present a Business Intelligent Report


  



   










