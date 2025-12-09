# Spark SQL – Creating and Managing Hive Tables

## Description

This notebook explores the features of **Spark SQL** using **PySpark** by creating and manipulating Hive databases and tables.  
It was developed in a **Google Colab** environment.

The project follows several key steps:
- Mounting Google Drive to access data
- Initializing a Spark session with Hive support
- Creating and selecting a database
- Defining SQL table schemas
- Creating Hive tables
- Inserting and displaying data from tables

## Technologies

- Python  
- PySpark  
- Apache Spark  
- Hive  
- Google Colab  

## Notebook Structure

1. **Installation & Setup**
   - Installing PySpark  
   - Mounting Google Drive  
   - Initializing the SparkSession  

2. **Database Management**
   - Creating a Hive database named `pearson`  
   - Setting the database as the default  

3. **Hive Table Creation**
   - Creating the `customer` table with the schema:  
     `(id, firstname, lastname, gender, age)`  
   - Additional tables may be defined later in the notebook  

4. **SQL Operations**
   - Running SQL commands through `spark.sql()`  
   - Displaying the contents of databases and tables  

## Author

**Lina Benzemma**

---

