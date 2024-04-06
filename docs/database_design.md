# Database Schema

This document describes the database schema used in our CRM system.

## Entity-Relationship Diagram (ERD)

![ERD](path/to/your/ERD/image.png)

- **Entities**:
  - Customers
  - Orders
  - Products
  - ...

- **Relationships**:

Leads - Interactions: One lead can have multiple interactions, creating a one-to-many relationship between the Leads and Interactions tables.

SalesRepresentatives - Interactions: Each interaction is associated with one sales representative, creating a many-to-one relationship between the SalesRepresentatives and 
Interactions tables.

Customers - Orders:Each order is associated with one customer, creating a many-to-one relationship between the Customers and Orders tables.

Orders - Order_Items:Each order can contain multiple order items, creating a one-to-many relationship between the Orders and Order_Items 
tables.

Products - Order_Items: Each order item is associated with one product, creating a many-to-one relationship between the Products and 
Order_Items tables.

SalesRepresentatives - Tasks: Each task is assigned to one sales representative, creating a many-to-one relationship between the 
SalesRepresentatives and Tasks tables.
These relationships help establish connections between different entities within the CRM database, enabling efficient data retrieval and 
management.
