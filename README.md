# Retail Store Inventory Management System

## Project Overview
The **Retail Store Inventory Management System** is a **data-driven solution** designed to optimize and automate retail inventory operations. This project integrates **real-time data tracking**, **automation**, and **advanced analytics** to enhance supply chain efficiency, prevent overstocking or stockouts, and support **data-informed decision-making** for retail managers.  

By leveraging **MySQL**, **NoSQL (MongoDB)**, and **Python-based analytics**, the system provides a unified platform for efficient inventory control, order tracking, and stock forecasting across multiple retail stores and warehouses.

---

## Key Objectives
- Automate inventory monitoring and replenishment to minimize manual errors.  
- Optimize stock levels using real-time data and analytics.  
- Improve supply chain efficiency through seamless integration of warehouses, suppliers, and retail stores.  
- Provide actionable insights for better decision-making and forecasting.  
- Enable interactive visualization and data access using Python integration.

---

## Features
- **Automated Reordering System:** Triggers purchase orders when inventory reaches a predefined threshold.  
- **Real-Time Stock Monitoring:** Tracks product movement across warehouses and stores.  
- **Multi-Database Integration:** Uses both **MySQL** and **MongoDB** for structured and unstructured data management.  
- **Data Analytics & Visualization:** Python and Pandas used for data analysis; Matplotlib for visual insights.  
- **Scalable Design:** Supports multiple locations, warehouses, and suppliers.  
- **Reduced Human Error:** Automated processes minimize manual interventions.  

---

## Conceptual Design

### 1. EER and UML Models
The system was designed using:
- **Enhanced Entity-Relationship (EER) Model**
- **Unified Modeling Language (UML) Diagrams**  
These models define relationships among customers, orders, warehouses, stores, products, employees, and suppliers to ensure a normalized database schema.

### 2. Mapping to Relational Model
The relational schema includes entities such as:
- **Customer** (`CustomerID`, `CustomerName`)  
- **Order** (`OrderID`, `Quantity`)  
- **RetailStore** (`StoreID`, `StoreLocation`)  
- **Warehouse** (`WarehouseID`, `WarehouseLocation`)  
- **Product** (`ProductID`, `WarehouseID`, `InventoryID`, `ProductName`)  
- **Supplier** (`SupplierID`, `SupplierName`)  
- **Payment** (`PaymentID`, `PaymentType`)  
Foreign key constraints ensure referential integrity across all relationships.

---

## Implementation

### 1. MySQL Implementation
The database was implemented in **MySQL Workbench** using relational queries for:
- Fetching customer and order details  
- Calculating total order quantities and averages  
- Joining tables for relational insights  
- Performing aggregate and filtering queries  

