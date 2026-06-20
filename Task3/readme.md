# SQL Data Analysis Using SQLite3 on Cleaned Dataset for Data Analytics

## Project Overview

This project demonstrates SQL-based data analysis using SQLite3 and Python within Jupyter Notebook. The cleaned dataset was imported into a SQLite database, and various SQL queries were executed to retrieve, filter, group, summarize, and analyze data.

The project showcases how SQL can transform structured data into meaningful insights and support data-driven decision-making.


## Objectives

- Create a SQLite database for storing the dataset.
- Import the cleaned dataset into a database table.
- Retrieve data using SQL queries.
- Filter records using SQL conditions.
- Group records using aggregation techniques.
- Calculate summary statistics using aggregate functions.
- Generate meaningful insights from the dataset.

## Dataset Information

### Dataset Name
**Cleaned Dataset for Data Analytics**

### Dataset Source

The dataset used in this project was originally obtained from a previous dataset. It was cleaned and preprocessed to improve data quality, and the cleaned data was then exported to a new Excel file. This exported dataset was imported into a SQLite database and analyzed using SQL queries to generate meaningful insights.

### Dataset Details

| Attribute | Description |
|------------|-------------|
| File Format | Excel (.xlsx) |
| Database | SQLite3 |
| Domain | Data Analytics |
| Purpose | SQL Data Analysis |


## Technologies Used

- SQLite3
- SQL
- Python
- Pandas
- Jupyter Notebook
- Microsoft Excel

---

## Methodology

### Step 1: Dataset Loading
Loaded the cleaned dataset into Jupyter Notebook using Pandas.

### Step 2: Database Creation
Created a SQLite database using the SQLite3 library.

### Step 3: Data Import
Imported the dataset into a SQLite table for analysis.

### Step 4: Query Execution
Executed SQL queries to retrieve information from the database.

### Step 5: Data Filtering
Applied `WHERE` clauses to filter records based on specific conditions.

### Step 6: Data Grouping
Used `GROUP BY` clauses to categorize records and generate summarized results.

### Step 7: Aggregation Analysis
Applied aggregate functions including:

- COUNT()
- SUM()
- AVG()

### Step 8: Result Sorting
Used `ORDER BY` clauses to sort records in ascending and descending order.

### Step 9: Interpretation
Analyzed query results to derive meaningful business insights.


## SQL Operations Performed

### Data Retrieval

- Retrieved all records using SELECT statements.
- Retrieved specific columns for analysis.

### Data Filtering

- Applied WHERE conditions.
- Extracted records matching specific criteria.

### Data Grouping

- Used GROUP BY clauses.
- Generated category-wise summaries.

### Aggregate Functions

- COUNT() – Total number of records.
- SUM() – Total values.
- AVG() – Average values.

### Data Sorting

- Sorted records using ORDER BY.
- Displayed results in ascending and descending order.


## Sample SQL Queries

### Retrieve Records

'''sql
SELECT * FROM sales LIMIT 5;
'''

### Filter Records

'''sql
SELECT CustomerID, OrderStatus
FROM sales
WHERE PaymentMethod = 'Online';
'''

### Group Records

'''sql
SELECT Product, SUM(Quantity) AS Total_Quantity
FROM sales
GROUP BY Product;
'''

### Total Revenue

'''sql
SELECT SUM(TotalPrice) AS Total_Revenue
FROM sales;
'''

### Average Revenue

'''sql
SELECT AVG(TotalPrice) AS Average_Revenue
FROM sales;
'''

### Total Orders

'''sql
SELECT COUNT(*) AS Total_Orders
FROM sales;
'''

## Results

The SQL analysis successfully generated meaningful information from the dataset, including:

- Efficient retrieval of records.
- Accurate filtering of relevant data.
- Category-wise summaries.
- Statistical calculations using SQL functions.
- Improved understanding of business data through structured queries.

## Key Observations

- SQL simplifies data retrieval and analysis.
- SQLite3 provides an easy-to-use database environment.
- Aggregate functions efficiently summarize large datasets.
- Grouping operations provide meaningful insights.
- Filtering operations enable focused analysis.

## Skills Gained

- SQLite Database Management
- SQL Query Writing
- Data Import and Export
- Data Filtering using WHERE Clause
- Data Grouping using GROUP BY Clause
- Aggregate Functions (COUNT, SUM, AVG)
- Result Sorting using ORDER BY Clause
- Data Analysis and Interpretation


## Challenges Faced

- Understanding SQL syntax and query structure.
- Importing datasets into SQLite databases.
- Writing accurate filtering conditions.
- Interpreting aggregated results.
- Managing large query outputs.

## Conclusion

This project successfully demonstrated how SQLite3 and SQL can be used to analyze structured datasets efficiently. SQL operations such as SELECT, WHERE, GROUP BY, ORDER BY, COUNT(), SUM(), and AVG() were applied to extract meaningful insights from the dataset. The project strengthened practical knowledge of database management and SQL-based data analysis.

## References

1. SQLite3 Documentation
2. SQL Documentation
3. Pandas Documentation
4. Jupyter Notebook Documentation
5. DecodeLabs Industrial Training Kit
6. Data Analytics Learning Resources

## Author

**N.Chinmai Sai Chandana**

**RGUKT-ONGOLE**
