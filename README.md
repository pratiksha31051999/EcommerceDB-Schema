# EcommerceDB Schema

This project contains the database schema design for an e-commerce system.

## Entities
- Customers
- Products
- Orders
- OrderDetails
- Payments

## Relationships
- Customers → Orders (One-to-Many)
- Orders → Products (Many-to-Many via OrderDetails)
- Orders → Payments (One-to-One)

## Tools Used
- MySQL Workbench

## Deliverables
- SQL script (`schema.sql`)
- ER diagram (`EcommerceDB_ERD.png`)
