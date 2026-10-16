# E-commerce ETL Pipeline (PySpark + Spark SQL)

End-to-end batch pipeline using the medallion pattern (raw → silver → gold).

## Pipeline
- **Raw:** 50K+ synthetic orders CSV with duplicates, nulls, inconsistent city names
- **Silver:** deduplication, null handling, standardization, derived columns, Parquet partitioned by month
- **Gold:** monthly revenue, category performance, top customers (window functions), best category per city

## Tech
Python, PySpark, Spark SQL, Parquet, Google Colab

## Note
Dataset is synthetic, generated in the notebook.
