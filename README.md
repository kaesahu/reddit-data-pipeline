Architecture - 
<img width="824" alt="image" src="https://github.com/kaesahu/reddit-data-pipeline/assets/39849443/b3c2eecc-4949-4eaf-b891-177fce4f68ca">


The pipeline is designed to:

Extract data from Reddit using its API.
Store the raw data into an S3 bucket from Airflow.
Transform the data using AWS Glue and Amazon Athena.
Load the transformed data into Amazon Redshift for analytics and querying.

This project provides a comprehensive data pipeline solution to extract, transform, and load (ETL) Reddit data into a Redshift data warehouse. The pipeline leverages a combination of tools and services including Apache Airflow, Celery, PostgreSQL, Amazon S3, AWS Glue, Amazon Athena, and Amazon Redshift.
