# Amazon_Vine_Analysis
Big Data using PySpark, Google Collab, Postgres, pgAdmin, AWS (RDS, S3 Buckets)

## Overview 
***Background***
The Amazon Vine program is a company that allows manufacturers and publishers to receive reviews for their products. Companies can pay a small fee to Amazon and provide products to Amazon Vine members so they will publish a review for their product. 

***Purpose***
The purpose of this challenge is to analyze if there is bias for Amazon reviews written by members of the paid Amazon Vine program by: 
- Using Pyspark for the ETL process by first extracting the dataset and transforming the data. 
- Connect to the AWS RDS Instance to load the transformed data into pgAdmin 
- Use PySpark, Pandas or SQL to determine if there is any bias toward favorable reviews from Vine Members in the dataset 
- Write a summary 


## Resources 
- Original Data Source: [Electronics Dataset from Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
- Software: PySpark, Google Collab, Postgres, pgAdmin, AWS (RDS, S3 Buckets)


## Results
- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Summary 
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
