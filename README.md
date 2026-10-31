E-Commerce Order Data Processing - SQL Use Case

overview:
This project demonstrates basic SQL concepts using an E-Commerce Order Processing dataset.

The solution includes:
1)Creating database and tables
2)Inserting customer, product, and order data
3)Using joins to combine data
4)Performing aggregations and reporting
5)Identifying business insights using SQL queries

Database Name:sqlusecase

Tables:
Customers:

Column	      Description
customer_id	  Unique customer ID
customer_name	 Customer name
city	         Customer city

Orders:

Column	Description   order_id	Unique order ID
customer_id          	Customer ID
product_id	           Product ID
quantity	              Quantity ordered
status	                Order status


Tasks performed:
1. Display All Orders with Customer and Product Names

Uses INNER JOIN to combine:

Orders
Products

2. Calculate Total Order Amount for Each Customer
      SUM(quantity * price)
   to calculate customer spending.

   
3. Find Number of Orders by Status:
  COUNT(*)
and GROUP BY status.

4. Find Product with Highest Sales Amount
 SUM(qua*tity * price)
and sorts results in descending order.

5. Find Customers Who Have Not Placed Any Orders
LEFT JO*N
Customersand checks for NULL values.









