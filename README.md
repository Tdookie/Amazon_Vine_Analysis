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
<img width="647" alt="Screen Shot 2021-07-22 at 1 40 39 AM" src="https://user-images.githubusercontent.com/77812423/126594354-d8f9aa0d-0e11-4fe0-8ac2-d093f5f5bfe3.png">

- Non-Vine Reviews
<img width="686" alt="Screen Shot 2021-07-22 at 1 41 40 AM" src="https://user-images.githubusercontent.com/77812423/126594425-462c9535-7cfe-4418-9067-a10d810f4733.png">

## Percentage of 5 Star Reviews
- Vine Reviews
<img width="679" alt="Screen Shot 2021-07-22 at 1 43 40 AM" src="https://user-images.githubusercontent.com/77812423/126594553-915ea0fe-ece9-4b11-8a50-05c7ec804ab0.png">

- Non-Vine Reviews
