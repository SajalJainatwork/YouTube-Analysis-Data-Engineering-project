# YouTube Data Analysis End-To-End Data Engineering Project using Python and AWS.

## Introduction 
This is a End-To-End Data Engineering Project using Kaggle Youtube Trending Dataset.
I intially had data onto the Kaggle.com.I build a landing area and uploaded all the raw data using AWS CLI that got stored into s3 bucket.Once uploaded into s3 bucket I started analyzing the data .So I created glue crawler to understand how the data is built.So I found out that I had some errors in my JSON version files.I start processing that JSON file using AWS lamda and storing that particular data inside the second s3 bucket(cleansed/enriched).So I have to transform that data into Apache format and put that data onto the cleansed version bucket.Now I need to work with CSV file which contain our actual data.I will build a crawler on top of CSV file to understand the data.I start processing that CSV version files using AWS Glue and storing that particular data inside the second s3 bucket(cleansed/enriched).So I have to transform that data into Apache format and put that data onto the cleansed version bucket.After that we ran query and did some ETL run on top of the cleaned/enriched version and making sure all the data get properly transformed and securily built on top of data warehouse.and build a final reporting version based on that data.I can easily visualize that data into Quicksight.

## Architecture 
![yar](https://user-images.githubusercontent.com/106689439/212522730-cc2a3c6c-8dba-46b3-8c5d-40e4840c1e23.jpg)

## Technology Used
- Programming Language - SQL, Python and Pyspark
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
6. Redshift
7. IAM
8. Lambda
9. Quicksight
- Building Data Pipeline and Scheduling it.

## Quicksight Visualisation
![ss](https://user-images.githubusercontent.com/106689439/212527366-8b561833-0efa-45ba-9f69-ef1e2488b3b2.jpg)



 
