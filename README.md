# SQL DataWareHouse Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀 This project showcases a complete data warehousing and analytics workflow, covering everything from constructing the data warehouse to deriving meaningful insights. These were divided into multiple phase from pulling the dataset from customer Env to sending reports to stakeholders.

Phase I (Collecting dataset from Customer Env to our Locals):
1. Dedicated folder assigned to the Customers Dataset.
2. Data pulled from Customers SharePoint to our dedicated folder using python Script and Apache Nifi Processors.
3. Validating that dataset pulled successfully.


Phase II (Bronze Layer):
1. Inspecting the Data at source.
2. Creating Bronze Table with respective columns.
3. SQL Procedure to pull the data from folder to the MySQL Schema as Bronze Table.
4. Validating Bronze table are filled with Data.


Phase III (Silver Layer):
1. Analysing the data at Bronze and ticking what cleanup required.
2. Creating Silver Table with analysed and cleaned columns.
3. SQL Procedure to extract from Bronze and collect to Silver Table.


Phase IV (Gold Layer):
1. Analysed and validated data from Silver layer.
2. Converted into the VIEW
