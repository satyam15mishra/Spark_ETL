# Spark_ETL

## Summary of the project
An ETL pipeline which is hosting Sparkify user data as a datalake hosted on AWS S3 backed up by PySpark.
The aim of the project is to extract data from S3 using a python script, perform transformation operations and then again host it on S3.
Furthermore, the spark process is deployed on AWS.

## Files in the repository
The python script etl.py is used to perform ETL operations, which is deployed on AWS.
dw.cfg is the configuration file, which will contain the AWS Keys, which allow you to access AWS Account and subsequently the data
Although the data is on S3, the exploring the data folder locally can give you an insight on how the user and log data looks like

## How to run the file
To perform the operations locally, you can run the script on your machine. However, it can also be used on AWS (EMR/Lambda) in order to use the power of PySpark SQL.

