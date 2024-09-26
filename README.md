# Home Sales Analysis with PySpark and Spark SQL

This project demonstrates the use of PySpark and Spark SQL to analyze a dataset of home sales. It covers data loading, transformation, querying, and performance optimization techniques like caching and partitioning.

## Key Features

- **Spark Setup**: Establishes a Spark environment within a Colab notebook, including Spark installation and session creation.
- **Data Loading**: Reads home sales data from an AWS S3 bucket into a Spark DataFrame.
- **SQL Queries**: Utilizes Spark SQL to perform various analyses on the home sales data, including:
  - Calculating average prices based on different criteria (number of bedrooms, bathrooms, square footage, etc.).
  - Grouping and filtering data based on specific conditions.
  - Measuring query execution time to assess performance.
- **Caching**: Demonstrates the use of caching to improve query performance by storing data in memory.
- **Parquet Partitioning**: Showcases how to partition Parquet data by a specific column (date_built) for optimized querying and storage.

## Dependencies

- PySpark
- Spark (version 3.4.3 or compatible)
- Java (OpenJDK 11 or compatible)
