### **Day 2 – RDD Basics**

#### 📌 Topics
- What are **RDDs** (Resilient Distributed Datasets)?
- Difference between **Transformations** vs **Actions**.
- Creating RDDs.
- Common operations: `map`, `filter`, `reduce`, `collect`.

---

#### ⚡ Example 1 – Creating an RDD
```python
from pyspark.sql import SparkSession

# Create Spark Session (entry point to PySpark)
spark = SparkSession.builder \
    .appName("RDD Example") \
    .master("local[*]") \
    .getOrCreate()

# Access SparkContext from SparkSession
sc = spark.sparkContext
# Create RDD from a Python list
data = [1, 2, 3, 4, 5]
rdd = spark.sparkContext.parallelize(data)

print("RDD Elements:", rdd.collect())