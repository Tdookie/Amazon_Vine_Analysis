# Amazon_Vine_Analysis
# Analysis Overview
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

# Resources
- Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt
- Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

# Results
## Total number of reviews 
- Vine Reviews
<img width="422" alt="Screen Shot 2021-07-22 at 1 37 04 AM" src="https://user-images.githubusercontent.com/77812423/126594146-c1d6f84c-e086-48d9-a2a8-1d9e4dd81408.png">

- Non-Vine reviews
<img width="361" alt="Screen Shot 2021-07-22 at 1 38 42 AM" src="https://user-images.githubusercontent.com/77812423/126594259-bf7aba9c-d589-40df-9c09-47bd51a99be8.png">

## Total number of 5-star reviews
- Vine Reviews
