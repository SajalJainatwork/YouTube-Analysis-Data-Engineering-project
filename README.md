# YouTube Data Analysis End-To-End Data Engineering Project using Python and AWS.

## Introduction 
This is an End-To-End Data Engineering Project using Kaggle Youtube Trending Dataset.
I initially had data onto Kaggle.com.I built a landing area and uploaded all the raw data using AWS CLI that got stored into an s3 bucket. Once uploaded into the s3 bucket I started analyzing the data. So I created a glue crawler to understand how the data is built. So I found out that I had some errors in my JSON version files. I start processing that JSON file using AWS lambda and storing that particular data inside the second s3 bucket(cleansed/enriched). So I have to transform that data into Apache format and put that data onto the cleansed version bucket. Now I need to work with a CSV file that contains our actual data. I will build a crawler on top of the CSV file to understand the data. I start processing the CSV version files using AWS Glue and storing that particular data inside the second s3 bucket(cleansed/enriched). So I have to transform that data into Apache format and put that data onto the cleansed version bucket. After that, we ran the query and did some ETL run on top of the cleaned/enriched version and made sure all the data get properly transformed and security was built on top of the data warehouse. and built a final reporting version based on that data. I can easily visualize that data in Quicksight.

✅ Python and PySpark

✅ SQL

✅ How to understand the business problem

✅ AWS Services - Athena, Glue, Redshift, S3, IAM

✅ Building Data Pipeline and Scheduling it



## Architecture 
![yar](https://user-images.githubusercontent.com/106689439/212522730-cc2a3c6c-8dba-46b3-8c5d-40e4840c1e23.jpg)

## Technology Used
✅ Programming Language - SQL, Python, and Pyspark
✅ Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
6. Redshift
7. IAM
8. Lambda
9. Quicksight
✅ Building Data Pipeline and Scheduling it.

## Quicksight Visualisation
![ss](https://user-images.githubusercontent.com/106689439/212527366-8b561833-0efa-45ba-9f69-ef1e2488b3b2.jpg)



 
