# Amazon_Vine_Analysis  
## Resources  
* PySpark
* Amazon Web Service (AWS)
* S3
* Google Colaboratory
* pgAdmin4  
## Overview  
Used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then we used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.  
## Deliverable 1  
WE created an AWS RDS database with tables in pgAdmin, picked a dataset from the Amazon Review datasets, and extracted the dataset into a DataFrame. We then transformed the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Finally, we uploaded the transformed data into the appropriate tables and ran queries in pgAdmin to confirm that the data has been uploaded.  
## Deliverable 2  
Using your knowledge of PySpark, Pandas, or SQL, you’ll determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis, you'll determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.  

## Results  
How many Vine reviews and non-Vine reviews were there?  
* 1685 reviews  
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?  
* zero
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?  
* 37.4% unpaid 5 star reviews
