### **– Introduction & Setup and Fundamentals**

---

#### **Day 1: Intro to Spark & Setup**
- **What is PySpark? Why use it?**
  - PySpark = Python API for Apache Spark, a **distributed computing framework**.
  - Handles **big data** across clusters with ease.
  - Use cases: ETL pipelines, Data Analytics, Machine Learning at scale.

- **Install PySpark (local & in Jupyter/Colab)**
  ```bash
  pip install pyspark

- **Spark Architecture Basics**
  - **Driver**: The main program that controls the Spark application and sends tasks.
  - **Executors**: Worker nodes that run tasks and store data.
  - **Cluster Manager**: Allocates resources (Standalone, YARN, Mesos, Kubernetes).

- **Core PySpark Component**
  - **SparkSession**: The entry point for programming with the DataFrame and SQL API.
    ```python
    from pyspark.sql import SparkSession
    # Create Spark Session
    spark = SparkSession.builder.appName("HelloWorld").getOrCreate()
    # Test
    spark.version
    ```