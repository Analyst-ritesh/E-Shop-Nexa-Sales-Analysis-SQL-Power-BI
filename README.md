# Nexa-Sales-Analysis-SQL-Power-BI

This project aims to analyze sales data, store information, sales team data, regional data, product information, and customer data to provide insights for informed business decisions. The dataset includes a Fact Table with sales data and multiple dimension tables. The objective is to derive meaningful insights to optimize sales strategies and assess the impact of geographical factors and sales teams on business performance.

## About the Dataset:

This project aims to analyze sales data, store information, sales team data, regional data, product information, and customer data to provide insights for informed business decisions. The dataset includes a Fact Table with sales data and multiple dimension tables. The objective is to derive meaningful insights to optimize sales strategies and assess the impact of geographical factors and sales teams on business performance.

The dataset comprises several tables:

1. Fact Table:
OrderNumber: A unique identifier for each order.
Sales Channel: The channel through which the sale was made (e.g., In-Store, Online, Distributor).
WarehouseCode: Code for the warehouse where products were procured.
ProcuredDate: Date when the products were procured.
OrderDate: Date when the order was placed.
ShipDate: Date when the products were shipped.
DeliveryDate: Date when the products were delivered.
CurrencyCode: Currency code for the transaction.
_SalesTeamID: A unique identifier for the sales team associated with the sale.
_CustomerID: A unique identifier for the customer.
_StoreID: A unique identifier for the store.
_ProductID: A unique identifier for the product.
Order Quantity: The quantity of products ordered.
Discount Applied: The discount applied to the order.
Unit Price: The unit price of the product.
Unit Cost: The cost per unit of the product.

2. Store Table:
_StoreID: A unique identifier for the store.
City Name: The name of the city where the store is located.
County: The county where the store is situated.
StateCode: The code for the state where the store is located.
State: The full name of the state.
Type: The type of area (e.g., City).
Latitude: The latitude coordinate of the store's location.
Longitude: The longitude coordinate of the store's location.
AreaCode: The area code for the store's location.
Population: The population of the city where the store is located.
Household Income: The average household income in the city.
Median Income: The median income in the city.
Land Area: The land area of the city.
Water Area: The water area of the city.
Time Zone: The time zone of the city.

3. Sales Team Table:
_SalesTeamID: A unique identifier for the sales team.
Sales Team: The name of the sales team.
Region: The region to which the sales team belongs.

4. Region Table:
StateCode: The code for the state.
State: The full name of the state.
Region: The region to which the state belongs.

5. Products Table:
_ProductID: A unique identifier for the product.
Product Name: The name of the product.

6. Customers Table:
_CustomerID: A unique identifier for the customer.
Customer Names: The name of the customer.

## Key Objectives:

The primary objectives of the project are as follows:
1. Sales Analysis: Analyze sales data to understand sales trends, sales channels, product performance, and the impact of discounts.
2. Geographic Analysis: Assess the influence of geographic factors such as city, state, and region on sales, including population demographics.
3. Sales Team Performance: Evaluate the performance of sales teams, their contribution to sales, and regional sales trends.
4. Product Analysis: Analyze product sales and identify top-performing products.

## Data Processing in SQL:

Data Import: Loaded the dataset into a SQL database.
Data Cleaning: Address any missing values, errors, or inconsistencies in the data.
Data Transformation: Created relationships between tables using primary and foreign keys to enable comprehensive analysis.

Data Analysis:
* Conducted SQL queries to perform sales analysis, geographic analysis, sales team evaluation, and product analysis.
* Aggregate and join data from various tables to derive meaningful insights.

## Data Processing in Power BI:
Data Visualization: Connect Power BI to the SQL database to create interactive visualizations for presenting the findings effectively.
Design dashboards, charts, and tables to represent insights in an intuitive and informative manner.

## Insights:
