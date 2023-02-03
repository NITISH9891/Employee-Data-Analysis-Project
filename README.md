# Employee Data Analysis Project
An end to end data engineering project on employee data which includes performing tasks such as Data modeling, Data Engineering and Data Analysis.

## Objective
To create an End-to-End Data pipeline using various Big data technologies which include the Hadoop ecosystem, SparkSql, Hive, Sqoop, etc to analyze and come up with a solution to the organization needs. To perform Exploratory Data Analysis on the given data to come up with patterns and meaningful insights. With the help of Machine Learning model to analyze the employee retention rate of the organization.

## Data description
The dataset consists of six csv files and are uploaded in the (/Data) folder.  The files are namely :

1. titles.csv - This file contains different job titles with respect to the employees.
2. employees.csv - Contains all data related to individual employee, such as employee id, name, age, sex, date of hiring, etc.
3. salaries.csv - Employee salary.
4. departments.csv - List of various departments in the company.
5. dept_manager.csv - Talks about which employee manages which department.
6. dept_emp.csv - The department to which each employee belongs.


![\[pic link\]](https://github.com/NITISH9891/Employee-Data-Analysis-Project/blob/main/DATA-MODEL.png)

## Technology Stack
- MySQL
- Linux Commands
- Sqoop
- HDFS
- Hive
- SparkSQL
- SparkML

## Overview
The data is initially present in the form csv, then imports the CSVs into a SQL database, and then analyze the data. The three phases include
- Data Modeling
- Data Engineering
- Data Analysis   

### Data Modeling
Looking at the CSVs data and build an Entity Relationship Diagram of the tables. The Data Modeling folder contains the ER diagram and the schema code to build it.

### Data Engineering
- Using the information given to create a table schema for each of the six CSV files. Specify the data types, primary keys, foreign keys, and other constraints.
- Imports each CSV file into the corresponding SQL table.

### Data Analysis
After completing the database , do the required data analysis using Spark SQL and open the 'DATA-ANALYSIS-USING-SPARKSQL' and run all Queeries to do the anlysis.

### File Execution
1. LOCAL-to-MYSQL-USING-JDBC
2. MYSQL-to-HDFS-USING-SQOOP
3. IMPORT-DATA-USING-SPARK
4. DATA-ANALYSIS-USING-SPARKSQL

### Challenges Faced
- Data fromat related challenges.
- Collecting the data and transferring to HDFS.
- Debugging alot of errors.
- Technology related issues.

