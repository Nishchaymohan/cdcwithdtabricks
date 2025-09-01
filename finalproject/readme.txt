 Change Data Capture ETL Pipeline Using Azure Data Factory and Databricks
 Project Overview
This project showcases an end-to-end ETL (Extract, Transform, Load) pipeline for Change Data Capture (CDC) using:

SQL Server for source data (Customer, Product, Order, Inventory tables)

Azure Data Factory (ADF) for orchestrating data movement

Azure Databricks for CDC data processing

Email notifications with updated data attachment

Scheduled execution every hour

The goal is to detect changes from SQL Server, process them in Databricks, and generate timely outputs with automated email notifications.