# Projet Dev-Web et SQL MASTERCLASS

## Objectives

Make a website per group that follows the instructions below.

## Instructions
Create a database named "OnlineStore" with the following tables in SQL only:        
Customers (with the columns: CustomerID (primary key), FirstName, LastName, Email, Password)        
Products (with the columns: ProductID (primary key), Name, Description, Price)      
Orders (with the columns: OrderID (primary key), CustomerID (foreign key to Customers), OrderDate)      
OrderItems (with the columns: OrderID (foreign key to Orders), ProductID (foreign key to Products), Quantity, Price)           

Create a website that must be linked to the database, you can use any language of your choise. You will have to takes into account all the queries below:       

Select all customers and display their full name, their email address.      

Add a new customer      

Select all products and display all their informations.     

Create a new order      

Select all orders placed in the chosen year and display the customer name and date.     

Display all the orders by price. You will be able to choose if the filter is acsending or descending.       

Calculate the cost of the order (quantity x price for each order item, then add these amounts for each order).      

Select customers who have placed at least one order.        

Select products that have been ordered at least once.       

Update the price of all products by a certain percentage.       

Display the five customers with the most orders.     