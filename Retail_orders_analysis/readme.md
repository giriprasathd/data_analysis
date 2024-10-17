# Retail Orders Analysis

This project involves the extraction, cleaning, and analysis of global mart sales data. The data is sourced from Kaggle and analyzed using a combination of Python and Microsoft SQL Server. The project is inspired by a tutorial from Ankit Bansal's YouTube channel.

Watch the tutorial here: [Ankit Bansal - Retail Orders Analysis](https://www.youtube.com/watch?v=uL0-6kfiH3g&t=719s&ab_channel=AnkitBansal)

## Project Overview

The key steps in this project include:

1. **Data Extraction**:
   - Use the Kaggle API in Python to fetch retail orders data from Kaggle.

2. **Data Transformation**:
   - Clean and prepare the raw data for analysis using the pandas library in Python.

3. **Data Loading**:
   - Load the cleaned and transformed data into a Microsoft SQL Server database for efficient querying and analysis.

4. **Data Insights**:
   - Perform SQL queries to uncover trends and insights from the retail orders data in Microsoft SQL Server.

## Technologies Used

- **Python**: For data extraction, transformation, and manipulation.
- **pandas**: For cleaning and transforming the data.
- **Kaggle API**: To extract data from Kaggle.
- **Microsoft SQL Server**: For loading and analyzing the data.

## How to Run the Project

1. **Data Extraction**:
   - Install the Kaggle API and configure your credentials following the [Kaggle API documentation](https://www.kaggle.com/docs/api).
   - Run the Python script to fetch the retail orders dataset.

2. **Data Transformation**:
   - Use the pandas library to clean and format the data as needed.

3. **Data Loading**:
   - Set up a Microsoft SQL Server database on your local machine or cloud server.
   - Load the transformed data into the SQL Server database using Python.

4. **Data Analysis**:
   - Perform SQL queries on the Microsoft SQL Server database to analyze the trends and patterns in retail orders.

## Prerequisites

- Install the required Python libraries:
   ```python
   pip install pandas kaggle pyodbc
```
Install and configure Microsoft SQL Server on your system. You can also use Azure SQL Database for cloud hosting.

# Acknowledgment
This project was inspired by the tutorial provided by @ankitbansal6 on his YouTube channel.


