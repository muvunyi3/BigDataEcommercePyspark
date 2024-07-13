# Ecommerce Prediction with Pyspark
Bigdata Ecommerce Recommendation Prediction Engine

## Project Description
A brief description of your project, its purpose, and its functionality.

## Prerequisites
Ensure you have the following installed:
- Java JDK 8 or later
- Hadoop
- mysql
- Hive
- Spark
- Python 3.7 or later

## Setup Instructions

### Step 1: Clone the Repository
```bash
git clone https://github.com/muvunyi3/BigDataEcommercePyspark
cd BigDataEcommercePyspark
```

### Step 2: Hadoop commands

```bash
start-all.sh
jps
hdfs dfs -mkdir /ecommerce
hdfs dfs -ls /ecommerce
hdfs dfs -put EcommerceCustomers.csv /ecommerce
```

### Step 3: Hive
```bash
- install mysql
- download Hive
- configure hive-site.xml
- initiate schema

hive --service schematool -dbType mysql -initSchema 
- start metastore
hive --service metastore
hive 
- create database tradedb
- create external table sessions
- load data from hdfs project_files/2019-Nov.csv
```
### step 4 Py
```bash
- open ecommerce.ipynb in jyupter
```