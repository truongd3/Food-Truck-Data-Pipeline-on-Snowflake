# Food Truck Data Pipeline on Snowflake

_Members: Truong Dang, Snowflake Solution Engineers_

This project demonstrates an _end-to-end data pipeline_ built for a **food truck** brand (**Tasty Bytes**) using the **Snowflake Data Cloud**. It automates data ingestion, transformation, analytics, and monitoring: turning raw data into actionable business insights for better decision-making.

## What It Does
The pipeline is divided into three key parts:

1. **Load & Transform**: Ingest data from shared Snowflake Tasty Bytes documents into Snowflake Stages and transforms it into tables using SQL and Streams.
2. **Python Powered Analytics**: Use Snowpark for Python to run advanced data analysis and build predictive models directly inside Snowflake without data movement.
3. **Scheduling & Monitoring**: Automate workflows using `Tasks` and `Stored Procedures`, integrates Notification Services, and enables performance tracking for reliable and auditable data operations.

## Technologies

- Snowflake
  - Data Cloud
  - Streams
  - Tasks & Procedures
  - Notification Integrations
- Python
  - `snowflake.snowpark`
  - `snowflake.connector`
  - `pandas`
  - `modin`
  - `requests`
- SQL
- JSON
