# DP-203-Lab5

# Analyze Data in a Data Lake with Spark 🌊🔍

Apache Spark is an open-source engine for distributed data processing and is widely used to explore, process, and analyze huge volumes of data in data lake storage. Spark is available as a processing option in many data platform products, including Azure HDInsight, Azure Databricks, and Azure Synapse Analytics on the Microsoft Azure cloud platform. One of the benefits of Spark is its support for a wide range of programming languages, including Java, Scala, Python, and SQL, making it a very flexible solution for data processing workloads, including data cleansing, manipulation, statistical analysis, machine learning, and data analytics and visualization. ⚡📊

## 📝 Purpose
This lab demonstrates how to analyze data files using Apache Spark in Azure Synapse Analytics. You'll learn how to load data from files, transform it using Spark DataFrames, and perform queries and visualizations. 🔄📂

## 🚀 Key Concepts
- **Data Analysis**: Reading and analyzing file-based datasets with Spark 📈
- **DataFrame Operations**: Transforming and filtering data 🛠️
- **Aggregations and Grouping**: Performing aggregations and filters 🧮
- **Spark SQL**: Querying data with Spark SQL 🧑‍💻
- **Data Visualization**: Visualizing data using Spark’s built-in chart options and Python libraries 📊

## 🛠️ Technologies Used
- **Azure Synapse Analytics**: Data platform and analytics service 🌐
- **Apache Spark / PySpark**: Distributed data processing engine 🧠
- **Spark SQL**: Data querying and analysis 🔍
- **Pandas**: Data manipulation and analysis library 📑
- **Matplotlib & Seaborn**: Python libraries for advanced visualizations 📉

## 📂 Lab Workflow Summary
1. **Read Data from File** 📂
   - Load structured data into a Spark DataFrame using Synapse.

2. **DataFrame Operations** ⚙️
   - Select specific columns.
   - Filter rows based on conditions.
   - Count total and distinct values.

3. **Aggregations and Grouping** 📊
   - Use .groupBy() and .sum() to compute totals.
   - Extract and group by year using Spark functions.

4. **Spark SQL Queries** 🔎
   - Register DataFrames as temporary views.
   - Use SQL queries (spark.sql(...)) to retrieve and analyze data.
   - Use %%sql magic to run SQL directly in notebook cells.

5. **Visualization** 📈
   - Switch from table to chart view in Synapse notebooks.
   - Create charts using matplotlib and seaborn.

6. **Cleanup** 🧹
   - Delete Azure Synapse resources to avoid extra costs.

## 📊 Sample Visuals Created
- **Bar Chart**: Total product sales 🛍️
- **Yearly Revenue Trends**: Yearly revenue trends (bar & line charts) 💵
- **Pie Chart**: Orders per year 🥧

## ✅ Learning Outcomes
By completing this lab, you will:
- Understand how to work with file-based data using Spark in Synapse.
- Gain skills in DataFrame transformations and SQL-based queries.
- Learn to visualize data with built-in and external libraries. 🎓

## 🧹 Cleanup Reminder
Don't forget to delete your Azure resource group after finishing the lab to prevent unnecessary charges. 🔥
