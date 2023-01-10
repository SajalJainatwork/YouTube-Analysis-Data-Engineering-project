# dataengineering-youtube-analysis-project
Data Engineering YouTube Analysis Project  
This is a End-To-End Data Engineering Project using Kaggle Youtube Trending Dataset.
Data is coming from Kaggle.All the raw data uplooaded using AWS CLI that got stored over s3 bucket.Once data stored in s3 bucket ,start processing that JSON file using AWS lamda and storing that particular data inside the second s3 bucket(cleansed/furiched).
Intially had data on Kaggle.com .downloaded that data and uploaded that data onto s3 bucket.Once uploaded into s3 bucket we started analyzing the data .So we created glue crawler to understand how the data is built.So we found out that we had some errors in our JSON files.So we have to transform that data and put that data onto the cleansed version bucket.Now we need to work with CSV file which contain our actual data.We will build a crawler on top of CSV file to understand the data and run some ETL on top of it.Need some transformation and based on that we will go further and build our final product.
CSV version and JSON version converted into Apache version and uploaded into cleansed version bucket.
We ran a query and did ETL on top of the cleansed version and making sure all the data get properly transformed and securily built on top of data warehouse.
