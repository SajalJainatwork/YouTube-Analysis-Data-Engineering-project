# Youtube Data Analysis End-To-End Data Engineering Project using Python and AWS.

## Introduction 
This is a End-To-End Data Engineering Project using Kaggle Youtube Trending Dataset.
We intially had data onto the Kaggle.com.We build a landing area and uploaded all the raw data using AWS CLI that got stored into s3 bucket.Once uploaded into s3 bucket we started analyzing the data .So we created glue crawler to understand how the data is built.So we found out that we had some errors in our JSON version files.We start processing that JSON file using AWS lamda and storing that particular data inside the second s3 bucket(cleansed/enriched).So we have to transform that data into Apache format and put that data onto the cleansed version bucket.Now we need to work with CSV file which contain our actual data.We will build a crawler on top of CSV file to understand the data.We start processing that CSV version files using AWS Glue and storing that particular data inside the second s3 bucket(cleansed/enriched).So we have to transform that data into Apache format and put that data onto the cleansed version bucket.After that we ran query and did some ETL run on top of the cleaned/enriched version and making sure all the data get properly transformed and securily built on top of data warehouse.and build a final reporting version based on that data.We can easily visualize that data into quicksight.

## Architecture 
![yar](https://user-images.githubusercontent.com/106689439/212522730-cc2a3c6c-8dba-46b3-8c5d-40e4840c1e23.jpg)

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka

## Visualisation(Quicksight)
![ss](https://user-images.githubusercontent.com/106689439/212527366-8b561833-0efa-45ba-9f69-ef1e2488b3b2.jpg)



 
