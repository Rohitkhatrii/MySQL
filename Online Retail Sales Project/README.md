
Online Retail Sales Database Design – Project Report

Objective: The goal of this project is to design and implement a normalized SQL schema for an e-commerce platform. The schema manages customers, products, orders, payments, and order details while supporting queries and reports like sales summaries.

Tools Used: MySQL

Diagramming: dbdiagram.io (for ER diagram)

SQL Scripts: DDL & DML for table creation and data insertion

Key Entities & Relationships:
Customers: Stores customer information.

Products: Maintains product details with pricing and stock.

Orders: Represents customer orders with status and dates.

Order Items: Links orders and products, tracking quantities and prices.

Payments: Records payment details for each order.

Normalization: The schema is normalized up to 3rd Normal Form (3NF) to avoid redundancy.

Deliverables
ER Diagram:

Showed relationships:

One customer can have many orders.

One order can have many products (via order_items).

Each order has one or more payment records.

SQL Schema:

Created five tables: customers, products, orders, order_items, payments.

Added Primary Keys, Foreign Keys, and Unique Constraints.

Sample Data:

Inserted 8 customers, 12 products, 15 orders, 30 order_items, and 15 payment records.

Queries:

JOIN Query: Generates a consolidated sales report showing order details, products, and payment method.

Aggregate Query (GROUP_CONCAT): Combines multiple product names for each order.

Views:

product_sales_summary – Summarizes total units sold per product.

Key SQL Features Used
JOINs (INNER JOIN): To combine data across multiple tables for reporting.

GROUP_CONCAT: To list all products per order.

Aggregate Functions (SUM, MAX): For total amount and unit sales calculations.

Views: For reusable sales summaries.

Outcome
The database is structured, normalized, and query-optimized for order tracking and sales reporting.

Created a sales summary view for quick reporting of best-selling products.

The schema can be easily expanded (e.g., shipping details, returns, discounts).
