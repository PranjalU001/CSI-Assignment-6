# 🚀 Week 6 - Spark Architecture & Performance Optimization

## 📌 Project Overview

This repository contains my **Week 6 Assignment** completed during the **Celebal Technologies Internship**.

The project focuses on understanding **Apache Spark Architecture**, **PySpark DataFrame operations**, **Lazy Evaluation**, **DAG execution**, **schema handling**, **performance optimization**, and building a complete **ETL pipeline** using Spark.

The assignment demonstrates how Spark efficiently processes large datasets using distributed computing and optimized execution plans.

---

# 🎯 Objectives

The objectives of this assignment are:

* Understand Apache Spark Architecture
* Learn Driver, Cluster Manager, and Executor roles
* Understand Lazy Evaluation and DAG (Lineage Graph)
* Read data from CSV files
* Handle DataFrame schemas
* Perform filtering and selection
* Rename columns
* Change data types
* Add new columns
* Handle null values
* Understand Transformations and Actions
* Learn Wide Transformations and Shuffle
* Compare CSV and Parquet file formats
* Understand Predicate Pushdown
* Build an end-to-end Spark Data Pipeline
* Save processed datasets

---

# 🛠 Technologies Used

* Apache Spark
* PySpark
* Python
* Google Colab / Jupyter Notebook

---

# 📂 Repository Structure

```
Week6-Spark-Architecture-and-Performance-Optimization

│── Assignment-6.ipynb        # Complete Spark assignment
│── Sample - Superstore.csv   # Input dataset
│── Output.csv                # Processed output dataset
│── README.md                 # Project documentation
```

---

# 📊 Dataset

The project uses the **Sample Superstore Dataset**, which contains retail sales information.

The dataset includes:

* Order Details
* Customer Information
* Product Information
* Sales
* Profit
* Region
* Category
* Discount
* Quantity

---

# 📚 Topics Covered

### Spark Architecture

* Driver
* Cluster Manager
* Executors
* Spark Execution Flow

### Lazy Evaluation

* Execution Plan
* DAG (Directed Acyclic Graph)
* Lineage Graph

### Data Processing

* Reading CSV files
* Schema Inference
* DataFrame Transformations
* Data Filtering
* Column Selection
* Renaming Columns
* Data Type Casting
* Adding New Columns

### Performance Optimization

* Predicate Pushdown
* Shuffle Operations
* Wide Transformations
* CSV vs Parquet
* Spark Best Practices

---

# ⚙ Implemented Operations

The notebook includes implementations of:

* Reading CSV files
* Displaying schema
* Filtering rows
* Selecting required columns
* Renaming columns
* Casting data types
* Adding calculated columns
* Handling null values
* Performing DataFrame transformations
* Executing Spark actions
* Building a Read → Transform → Filter → Write pipeline

---

# 📁 Data Pipeline

```
Read CSV
     │
     ▼
Infer Schema
     │
     ▼
Filter Required Data
     │
     ▼
Select Columns
     │
     ▼
Rename Columns
     │
     ▼
Cast Data Types
     │
     ▼
Create New Columns
     │
     ▼
Write Output CSV
```

---

# 🚀 Key Spark Concepts Demonstrated

* Spark Architecture
* Driver and Executors
* Cluster Manager
* Lazy Evaluation
* DAG Execution
* Fault Tolerance using Lineage Graph
* Transformations
* Actions
* Wide Transformations
* Shuffle
* Predicate Pushdown
* Schema Handling
* CSV Processing
* Performance Optimization

---

# 📈 Learning Outcomes

After completing this assignment, I gained practical experience in:

* Understanding Spark Architecture
* Working with PySpark DataFrames
* Implementing DataFrame transformations
* Schema management
* Data filtering techniques
* Spark execution model
* Performance optimization
* Building scalable ETL pipelines

---

# 💡 Performance Best Practices

This project follows several Spark optimization practices:

* Used DataFrame API
* Enabled Schema Inference
* Filtered data early
* Selected only required columns
* Used `show()` instead of `collect()` for preview
* Performed type casting before calculations
* Built transformations before triggering actions

---

# 📄 Output

The processed dataset is exported as:

```
Output.csv
```

---

# ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Week6-Spark-Architecture-and-Performance-Optimization.git
```

2. Open the notebook

```
Assignment-6.ipynb
```

3. Install PySpark

```bash
pip install pyspark
```

4. Run all notebook cells.

---

# 📌 Assignment Highlights

✔ Spark Architecture

✔ Lazy Evaluation

✔ DAG Execution

✔ Schema Handling

✔ DataFrame Transformations

✔ Data Filtering

✔ Performance Optimization

✔ CSV Processing

✔ Spark Pipeline

---

# 👨‍💻 Author

**Pranjal Upadhyay**

B.Tech – Computer Science Engineering (Artificial Intelligence & Data Science)

Poornima University

---

⭐ If you found this project useful, consider giving it a star!
