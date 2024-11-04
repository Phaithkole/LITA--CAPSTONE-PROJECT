## Capstone-Project

### Project Title: Sales Perfomances and Customer Subcription Dataset


### Project Overview For Sales Performance Analysis for a retail store 

The task is to analyze the sales performance of a retail store, It is ideal for analyzing monthly sales trends, top-selling products, and regional performance. 

### Project Overview For Customer Segmentation for Subcription Service 

This project involves analyzing customer data for subscription service toidentify segments and trends. The goal is to understand customer behavior, track subscription types, and identify key trends in cancellations and renewals. 

### Column Descriptions For Sales Data
-	OrderID: A unique identifier for each order.
-	CustomerId: A unique identifier for each customer placing an order.
-	Product: The specific product purchased in each transaction.
-	Region: The geographical location (e.g., North, South, East, West) where the order was placed.
-	OrderDate: The date when the order was made.
-	Quantity: The number of units purchased for each product in an order.
-	UnitPrice: The price per unit of the product.
-	Total Sales: The total_sales value for the order, calculated as Quantity * UnitPrice

### Column Descriptions For Customer Data

-	CustomerID: Unique identifier for each customer.
-	CustomerName: Name of the customer.
-	Region: Geographical area (e.g., North, South, East, West).
-	SubscriptionType: Type of subscription plan customers enrolled in (e.g., Basic, Premium, Standard).
-	SubscriptionStart: Start date of the customer's subscription.
-	SubscriptionEnd: End date of the customer's subscription.
-	Canceled: Indicates if the subscription was canceled (TRUE or FALSE).
-	Revenue: Revenue generated from the customer's subscription.
-	Subscription Duration: Duration of the subscription period

### Data Source:  
The main data sources for this analysis are the "Sales Data.csv" and "Customer Data.csv" files.

### Tools Used 
-Microsoft Excel: Employed for data cleaning and visualization.

-SQL: Utilized for data cleaning through queries.

-Microsoft Power BI: Used for both data cleaning and visualization.

### Data Cleaning and Preparations 
In the intial phase of Data Cleaning and Preparations, we perform the following action;
- Data loading
- Handling missing variables
- Data Cleaning and Formatting 

#### For Sales Data 
1. Retrieve the total sales for each product category.
2. Find the number of sales transactions in each region.
3. Find the highest-selling product by total sales value.
4. Calculate total revenue per product.
5. Calculate monthly sales totals for the current year.
6. Find the top 5 customers by total purchase amount.
7. Calculate the percentage of total sales contributed by each region.
8. Identify products with no sales in the last quarter.

#### For Customer Data
1. Retrieve the total number of customers from each region.
2. Find the most popular subscription type by the number of customers.
3. Find customers who canceled their subscription within 6 months.
4. Calculate the average subscription duration for all customers.
5. Find customers with subscriptions longer than 12 months.
6. Calculate total revenue by subscription type.
7. Find the top 3 regions by subscription cancellations.
8. Find the total number of active and canceled subscriptions.

### Data Analysis 
This is where we include some basic lines of code or queries or even some of the DAX expressions used during your analysis; 

```SQL
select *
From Table Name = SalesData
```
```SQL
select *
From Table Name = CustomerData
```


### Conclusion 
#### For Sales Performance Analysis  
The Sales performance analysis tells a story of what our customers love and how they shop. Shoe as the highest sales, selling over 600,000 quantity sold and becoming our top-selling product. Meanwhile, Socks has the lowest sales at 40,000 quantity sold.
Each month's sales performance shows February has the highest sales, followed by July. 
In each region, the South led the way, making up 44% of our sales, followed by the East at 23%, the North at 18%, and the West at 14%. 

#### For Customer Segmentation Analysis
Our Customer segment analysis shows an interesting pattern, Though we had three types of subscriptions, the "Basic" subscription emerged as the highest subscriber with over 50% subscriptions. Based on the report, we can deduce that "Basic" was the most affordable.
On average, Subscribers choose an average subscription duration of 365 days. This shows customers’ satisfaction and trust, as they renew their plans for a full year on average.
The East Region had the highest number of subscribers unlike other Regions, where some customers occasionally cancel their plans, the East shows a remarkable commitment, with zero cancellations on record. Eastern Region adds a unique view to our customer insights.


