# Enterprise Change Data Capture Pipeline

## Project Overview
This project involves building an automated data pipeline to capture and process change data efficiently using Azure Data Factory (ADF) and Databricks. The pipeline extracts only changed data from SQL Server tables to minimize ETL load and improve processing speed for downstream analytics.

## Features
- Normalized SQL Server tables with optimized query performance.
- Secure JDBC connections between SQL Server and Azure Data Factory.
- Automated ADF pipeline utilizing Change Data Capture (CDC) techniques.
- Scheduled Databricks notebooks to process incremental data feeds hourly.
- Reduced data latency for real-time business metrics.

## Technologies Used
- SQL Server
- Azure Data Factory (ADF)
- JDBC Connector
- Databricks
- Python (for automation scripts)
- CDC (Change Data Capture)

## Getting Started
### Prerequisites
- Azure subscription with Data Factory and Databricks workspace.
- Access to SQL Server with CDC enabled on relevant tables.
- Git installed on your local machine.

### Setup Instructions
1. Clone this repository:
