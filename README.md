
# Big Data Processing Pipeline

A robust data processing pipeline built using **Apache Spark (PySpark)**. This project demonstrates a standard ETL workflow that ingests raw student data containing duplicates, performs data cleaning operations, and outputs a refined dataset for analysis.

## 🚀 Features

* **Data Ingestion:** Reads structured CSV data into a Spark DataFrame.
* **Data Cleaning:** Identifies and removes duplicate records to ensure data integrity.
* **Scalability:** Built on Apache Spark, allowing the logic to scale from small datasets to big data environments.
* **Transformation:** specific transformations defined in `spark_script.py` (e.g., handling null values, type casting).

## 🛠️ Prerequisites

Before running the pipeline, ensure you have the following installed:

1. **Python 3.7+**
2. **Java 8 or 11** (Required for Apache Spark)
3. **Apache Spark** (bundled with PySpark)
---

## 🏃 Usage

You can execute the pipeline using a standard Python command or via `spark-submit` for cluster environments.

### 🔍 Pipeline Logic

1. **Input:** The script reads `student_data_with_duplicates.csv`.
2. **Process:**
* Initializes a `SparkSession`.
* Loads data with inferred schema.
* Performs deduplication and cleaning.
3. **Output:** Saves the clean data to `cleaned_student_data_with_duplicates.csv`.


