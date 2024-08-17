# SQL-Sales-Analysis
## Table of Contents
- [1.Introduction](#1Introduction)
- [2.Specifications](#2Specifications)
- [3.Data Schema](#3Data-Schema)
- [4.Modeling](#4Modeling)
- [5.Lesson Learned](#5Lesson-Learned)
## 1.Introduction
The main objective of this project is to solve ad hoc problems from customers and our business department using SQL queries. It involves common SQL statements such as SELECT, JOIN, WHERE, GROUP BY, etc., to extract and analyze data from different tables and categories. Additionally, some more complex requirements have been achieved using subqueries and Common Table Expressions (CTEs).
## 2.Specifications
 
## 3.Data Schema
The project utilizes a dataset with the following main tables:

**Customer:** Contains information about customers, including CustomerID, FirstName, LastName, CompanyName, and EmailAddress.

**Address:** Holds address details such as AddressID, AddressLine1, AddressLine2, City, StateProvince, CountyRegion, and PostalCode.

**CustomerAddress:** Contains information about customers' addresses, including CustomerID, AddressID, AddressType.

**SalesOrderHeader:** Contains sales order information, including SalesOrderID, OrderDate, CustomerID, ShipToAddressID, SubTotal, TaxAmt, and Freight.

**SalesOrderDetail:** Contains the details of each sales order, including SalesOrderDetailID, OrderQty, ProductID, UnitPrice, and UnitPriceDiscount.

**Product:** Contains product details like ProductID, Name, Color, ListPrice, Size, Weight, ProductModelID, and ProductCategoryID.

**ProductModel:** Holds information about different product models and their names.

**ProductCategory:** Provides product category information, including ProductCategoryID, ParentProductCategoryID, and Name.

**ProductDescription:** Contains descriptions of product models in different cultures.

**ProductModelProductDescription:** Associates product models with their corresponding descriptions.
## 4.Modeling 
![20240811034654](https://github.com/user-attachments/assets/4f58b234-dfad-4eef-b1a2-7495d0da9797)

## 5.Lesson Learned
In this project, I leveraged my expertise as a business analyst working with SQL and large datasets, focusing on optimizing SQL performance, ensuring data quality, and applying business understanding. By implementing techniques such as indexing and query optimization, I enhanced SQL efficiency and resource utilization. I also emphasized the importance of maintaining data cleanliness, accuracy, and consistency to support meaningful analysis. Additionally, I demonstrated my ability to understand business context and requirements, translating them into actionable SQL queries that provide relevant insights.
