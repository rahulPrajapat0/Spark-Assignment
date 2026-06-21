 Week 5 - Spark Fundamentals and Data Processing Assignment

-->Objective
To understand Apache Spark fundamentals and perform data cleaning, transformation, aggregation, and analysis using PySpark DataFrames.



-->Technologies Used
- Python
- PySpark
- Google Colab
- Apache Spark


-->Dataset
Dataset Used: data.csv


-->Tasks Performed

1. Spark Setup
- Created SparkSession
- Imported PySpark libraries
- Loaded CSV dataset into Spark DataFrame

2. Data Exploration
- Displayed first few rows using `show()`
- Checked schema using `printSchema()`
- Viewed column names using `df.columns`

3. Data Cleaning
- Checked duplicate records
- Removed duplicate rows using `dropDuplicates()`
- Checked null values in all columns
- Dataset did not contain any null values

4. Data Filtering
Performed filtering operations on:
- Category
- Region
- Sales values

5. Data Transformation
- Renamed columns where required
- Converted data types
- Created additional transformed columns

### 6. Aggregation Functions
Performed:
- Count of records
- GroupBy operations
- Category-wise aggregation

 7. GroupBy Result

| Category | Count |
|----------|-------|
| Office Supplies | 6026 |
| Furniture | 2121 |
| Technology | 1847 |


## Output
- Data loaded successfully into Spark DataFrame.
- Duplicate and null value checks completed successfully.
- Filtering and transformation operations executed successfully.
- Category-wise aggregation results generated.
- Output saved in `output/results.csv`.

 Conclusion
This assignment helped in understanding Apache Spark fundamentals, DataFrame operations, data cleaning, transformations, filtering, and aggregation using PySpark. The data processing pipeline was executed successfully and the results were exported to a CSV file.
