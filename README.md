# SQL-Sales-Analysis
## Table of Contents
- [1.Introduction](#1Introduction)
- [2.Specifications](#2Specifications)
- [3.KPIs](#3KPIs)
- [4.Modeling](#4Modeling)
- [5.Dashboard](#5Results)
- [6.Lesson Learned](#6Lesson-Learned)
## 1.Introduction
The main objective of this project is to solve ad hoc problems from customers and our business department using SQL queries. It involves common SQL statements such as SELECT, JOIN, WHERE, GROUP BY, etc., to extract and analyze data from different tables and categories. Additionally, some more complex requirements have been achieved using subqueries and Common Table Expressions (CTEs).
## 2.Specifications
 
## 3.KPIs
The dataset consists of a total of 9 tables, including 3 source data tables and 6 data mart tables.

**Orders:** This fact table contains information such as customer code, order code, order date, postal code, last product update, and product code

**People:** Provides information about person (cutomer name) and regions

**Returns:** Contains data on order codes and indicates whether a product has been returned

**Calender:** Includes a single record for each date used in the analysis

**Customer:** Generated from the order table, it includes details such as customer code, customer name, and segment

**Date Type:** Specifies the type of date, either order date or ship date

**Last Refresh:** Each time the dashboard is refreshed, this table updates and returns the latest refresh time

**Product:** Generated from the order table with a predefined filter, it includes product details such as product code, category, sub-category, product name, and last product update

**Region:** Generated from the order table, this table contains information about postal code, country, state, city, and region
## 4.Modeling 

## 5.Dashboard

## 6.Lesson Learned
