**SQL Sales & Inventory Management Project**
📌 Overview

This project is a SQL-based Sales and Inventory Management System designed to analyze business performance using structured queries. It models suppliers, categories, products, customers, employees, orders, and order details, then performs Business Intelligence (BI) style analysis through SQL queries.

The goal is to provide insights into:

Customer behavior

Product performance

Sales and order trends

Supplier contribution

Employee efficiency

🗂️ Database Schema

The database consists of 7 main tables:

supplier – Supplier information

categories – Product categories

employees – Employee details

customers – Customer information

products – Products with supplier & category links

orders – Orders placed by customers, processed by employees

order_details – Order line items (product, quantity, price, total)

🔑 Relationships

Each product belongs to a supplier & category.

📊 Key Insights & Queries

The project includes ready-to-run SQL queries to analyze the data.

🔹 Customer Insights

Unique customers who placed orders

Top customers by total orders & purchase value

Average spend per customer

🔹 Product Performance

Products per category

Average price by category

Best-selling products (by quantity & revenue)

Sales by category and supplier

🔹 Sales & Order Trends

Total orders placed

Average order value

Monthly sales & revenue trends

Weekday vs weekend patterns

🔹 Supplier Contribution

Total suppliers

Top suppliers by product count

Supplier revenue contribution

🔹 Employee Performance

Employees processing the most orders

Total sales value handled per employee

Average order value per employee

🔹 Deep Dive (Order Details)

Relationship between quantity & total price

Average quantity ordered per product

Unit price variations across orders

📈 Possible Extensions

Add sample data inserts for demo purposes

Create views for reusable aggregations

Build dashboards in Power BI/Tableau or Python for visualization

Implement stored procedures for automated reports

🛠️ Tech Stack

Database: MySQL / MariaDB

Language: SQL

Tools: MySQL Workbench, CLI, or any SQL client
Each order is linked to a customer & employee.

Each order_detail links products with orders.
