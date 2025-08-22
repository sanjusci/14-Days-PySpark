# 🚀 14-Day PySpark Crash Course

A **14-day fast-track learning plan** to master **PySpark** for Data Engineering and Interview Preparation. This 
roadmap is designed for **Data Engineers & Data Scientists** preparing for projects or interviews.  
Each day includes **theory**, ** ✅ Tasks: coding**, and **interview Q&A**.


---

## 📅 Learning Plan

### **Week 1 – Introduction & Setup and Fundamentals**
### **Day 1: - [Intro to Spark & Setup](docs/day1.md)**
  - What is PySpark? Why use it?
  - Install PySpark (local & in Jupyter/Colab).
  - Spark architecture: Driver, Executors, Cluster Manager.
  - SparkSession, Cluster overview, PySpark installation
  - ✅ [Tasks: Run Spark locally, Explore SparkSession, Hello World](models/Day1.ipynb).

### **Day 2 – [RDD Basics](docs/day2.md)**
- What are RDDs? Transformations vs Actions.
- Creating RDDs.
- `map`, `filter`, `reduce`, `collect`.
- [ ✅ Tasks: Word count example](models/Day2.ipynb).

### **Day 3 – DataFrames Basics**
- Intro to Spark SQL & DataFrames.
- Creating DataFrames.
- Schema, dtypes, show(), select, filter, withColumn, schema.
- ✅ Tasks: Load CSV, Explore schema, Apply filters

### **Day 4 – DataFrame Operations**
- Select, filter, withColumn.
- Sorting, distinct, dropDuplicates.
- ✅ Tasks:: Employee dataset cleaning.

### **Day 5 – Aggregations & Joins & Unions**
- GroupBy, agg, count, sum, avg.
- Joins (inner, left, right, outer, full), Unions.
- ✅ Tasks: Compute average sales, Count unique customers
- ✅ Tasks: Join customers & orders, Union multiple datasets  

### **Day 6 – SQL with PySpark**
- Register DataFrames as SQL tables.
- Run SQL queries with `spark.sql`, createOrReplaceTempView, SQL queries, functions 
- ✅ Tasks: Run SQL on DataFrame, Use SQL aggregations

### **Day 7 – Data Cleaning & Transformation**
- Handling nulls (`dropna`, `fillna`).
- Casting, replacing values.
- Date & string functions.
-  ✅ Tasks:: Transform messy dataset.

### **Day 8 – Window Functions**
- `row_number`, `rank`, `dense_rank`,  `lag`, `lead`.
- Partition & ordering
- ✅ Tasks: Top-N problem.
- ✅ Tasks: Find top 3 sales per region, Calculate moving average

### **Day 9 – UDFs & Performance and Complex data**
- User Defined Functions (UDFs), map, structs, arrays  
- Pandas UDFs.
- When to avoid UDFs.
- ✅ Tasks: Custom transformations.
- ✅ Tasks: Write a UDF, Parse nested JSON fields

### **Day 10 – Data Sources & File Formats**
- Reading/Writing CSV, JSON, Parquet, ORC, Delta.
- Partitioning & bucketing.
-  ✅ Tasks:: Save datasets in Parquet, Compare file sizes.

### **Day 11 – Spark MLlib Basics**
- Intro to Spark MLlib.
- Feature Engineering.
- Train simple ML model.
-  ✅ Tasks:: Logistic Regression on dataset.

### **Day 12 – Streaming with PySpark**
- Structured Streaming basics.
- Reading from Kafka/Socket.
- Writing to console & file.
-  ✅ Tasks:: Streaming word count.

### **Day 13 – Optimization & Tuning and Execution Model & Spark UI**
- Lazy evaluation, Catalyst optimizer, Stages, Tasks, DAG.
- Repartition vs Coalesce.
- Caching & persistence.
- Best practices.
- ✅ Tasks: Run job & check Spark UI, Explain DAG execution

### **Day 14 – Capstone Project + Interview Prep**
- #### Project 1 – Sales ETL Pipeline
  - ETL, cleaning, joins, partitioned writes  
  - ✅ Tasks: Load sales data, Transform & clean, Write to Parquet
- #### Project 2 – User Analytics
  - log parsing, window functions, aggregations  
  - ✅ Tasks: Parse JSON logs, Sessionize user activity, Find top users
- End-to-End ETL with PySpark:
  - Read raw data → Clean → Aggregate → Store in Parquet.
- Mock interview Q&A:
  - Difference between RDD vs DataFrame.
  - How Spark executes a job.
  - Common optimization techniques.

---

## 🛠️ Requirements
- Python 3.8+
- Java 8/11
- PySpark (`pip install pyspark`)
- Jupyter Notebook / VSCode /Pycharm

---

## 📚 Resources
- [Spark Documentation](https://spark.apache.org/docs/latest/)
- [Databricks Learning](https://www.databricks.com/learn)

---

## 🎯 Outcomes
By the end of this crash course, you will:
- Build ETL pipelines with PySpark.
- Perform aggregations, joins, and transformations.
- Work with streaming & batch data.
- Be ready for **Data Engineer / PySpark Interview**.

---
