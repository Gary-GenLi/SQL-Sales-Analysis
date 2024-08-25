# Sales-Analysis-SQL

## Table of Contents
- [1. Introduction](#1-introduction)
- [2. Specifications](#2-specifications)
- [3. Data Schema](#3-data-schema)
- [4. Modeling](#4-modeling)
- [5. Lessons Learned](#5-lessons-learned)

## 1. Introduction

The main objective of this project is to solve ad hoc problems from customers and our business department using SQL queries. It involves common SQL statements such as `SELECT`, `JOIN`, `WHERE`, `GROUP BY`, etc., to extract and analyze data from different tables and categories. Additionally, some more complex requirements have been achieved using subqueries and Common Table Expressions (CTEs).

## 2. Specifications

### 1. Project Objective
The primary goal of this project is to address specific ad hoc queries and business problems related to sales data using SQL. The queries are designed to extract, manipulate, and analyze data from a relational database consisting of multiple interconnected tables. The project aims to provide actionable insights to customers and business departments by utilizing SQL's robust querying capabilities.

### 2. Functional Requirements
- **Data Extraction:** Efficiently retrieve relevant data from various tables, such as `Customer`, `SalesOrderHeader`, and `Product`, using `SELECT` statements.
- **Data Filtering:** Apply filters using `WHERE` clauses to narrow down datasets based on specific criteria, such as date ranges, customer demographics, or product categories.
- **Data Aggregation:** Use `GROUP BY` clauses to aggregate data and perform calculations like sum, average, and count to derive insights on sales performance, customer behavior, and product popularity.
- **Data Joining:** Perform `JOIN` operations (INNER, LEFT, RIGHT, FULL) to combine data across multiple tables, enabling comprehensive analysis of related data points, such as linking customer information with their purchase history.
- **Advanced Querying:** Implement complex queries using subqueries and Common Table Expressions (CTEs) to solve more sophisticated business questions, such as ranking products by sales or identifying top customers.
- **Data Presentation:** Format the output data in a readable and meaningful way, often requiring the use of `ORDER BY` and `LIMIT` clauses to refine and present the results effectively.

### 3. Non-Functional Requirements
- **Performance:** Queries should be optimized to execute efficiently, particularly when dealing with large datasets. Techniques like indexing and query optimization should be applied to ensure fast response times.
- **Scalability:** The SQL queries should be designed to handle increasing volumes of data without significant performance degradation.
- **Data Quality:** Ensure the accuracy, consistency, and cleanliness of the data by applying data validation techniques and removing duplicates or anomalies before analysis.

### 4. Technology Stack
- **Database Management System (DBMS):** The project is implemented on a relational database system, such as SQL Server or MySQL
- **SQL:** SQL is the primary language used for querying and managing the data. The project extensively uses DML (Data Manipulation Language) and DQL (Data Query Language) commands.

### 5. Reporting & Output
- **Insights Generation:** The results from the SQL queries are intended to provide insights that drive business decisions, such as identifying sales trends, customer preferences, and inventory management.
- **Documentation:** Each SQL query is documented with comments to explain its purpose, logic, and any assumptions made.

## 3. Data Schema

The project utilizes a dataset with the following main tables:

- **Customer:** Contains information about customers, including `CustomerID`, `FirstName`, `LastName`, `CompanyName`, and `EmailAddress`.
- **Address:** Holds address details such as `AddressID`, `AddressLine1`, `AddressLine2`, `City`, `StateProvince`, `CountyRegion`, and `PostalCode`.
- **CustomerAddress:** Contains information about customers' addresses, including `CustomerID`, `AddressID`, `AddressType`.
- **SalesOrderHeader:** Contains sales order information, including `SalesOrderID`, `OrderDate`, `CustomerID`, `ShipToAddressID`, `SubTotal`, `TaxAmt`, and `Freight`.
- **SalesOrderDetail:** Contains the details of each sales order, including `SalesOrderDetailID`, `OrderQty`, `ProductID`, `UnitPrice`, and `UnitPriceDiscount`.
- **Product:** Contains product details like `ProductID`, `Name`, `Color`, `ListPrice`, `Size`, `Weight`, `ProductModelID`, and `ProductCategoryID`.
- **ProductModel:** Holds information about different product models and their names, including `ProductModelID` and `name`.
- **ProductCategory:** Provides product category information, including `ProductCategoryID`, `ParentProductCategoryID`, and `Name`.
- **ProductDescription:** Contains descriptions of product models in different cultures, including `ProductDescriptionID` and `Description`.
- **ProductModelProductDescription:** Associates product models with their corresponding descriptions, including `ProductModelID`, `ProductDescriptionID` and `Culture`.

## 4. Modeling

The data modeling for this project follows a relational schema, where key tables like `Customer`, `SalesOrderHeader`, and `Product` are linked through foreign keys. This structure supports efficient querying and data retrieval, allowing complex joins and aggregations to be performed with minimal redundancy. 

![Data Modeling](https://github.com/user-attachments/assets/4f58b234-dfad-4eef-b1a2-7495d0da9797)

## 5. Lessons Learned

In this project, I leveraged my expertise as a business analyst working with SQL and large datasets, focusing on optimizing SQL performance, ensuring data quality, and applying business understanding. By implementing techniques such as indexing and query optimization, I enhanced SQL efficiency and resource utilization. I also emphasized the importance of maintaining data cleanliness, accuracy, and consistency to support meaningful analysis. Additionally, I demonstrated my ability to understand business context and requirements, translating them into actionable SQL queries that provide relevant insights.
