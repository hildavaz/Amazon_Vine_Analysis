# Amazon_Vine_Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay 
a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Using Google Colab and PySpark 
will perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

## Results

- There were 61 Vine Reviews and 28287 non-Vine reviews

![image](https://user-images.githubusercontent.com/105381777/190047663-36e48c91-0596-465b-8562-3adbf83aa4fd.png)

![image](https://user-images.githubusercontent.com/105381777/190047715-45e9b2be-0ddd-4eec-9c73-9cbf13cb8703.png)


- There were 20 five starts Vine reviews and 15689 five starts non-Vine reviews

![image](https://user-images.githubusercontent.com/105381777/190047881-e27b568c-99e3-48e0-9bfe-31c65d5a8fe7.png)

![image](https://user-images.githubusercontent.com/105381777/190047921-fa94b7e8-998c-49f0-bad7-1903fab05cbe.png)


- There were 32.78% five starts Vine revies and 55.46 five starts non-Vine reviews 

![image](https://user-images.githubusercontent.com/105381777/190048009-72cc0693-d572-4bc3-8ca4-7bfc2e1c8d8a.png)

![image](https://user-images.githubusercontent.com/105381777/190048023-780948a5-4e33-4db0-9716-0973ce96782e.png)


## Summary

The results from the Vine vs Non-Vine revies demonstrate that there is not a foregone conclusion for reviews in the Vine program.  The number of    
Vine reviews totals in comparison to the Non-Vine reviews is significantly less.  Also as it shows above, the percentage of the 5 start Vive reviews
is 33% vs. the 5 start Non-Vine reviews been 55%.

An additional analysis to support the statement could be identifying the percentage of 5 start reviews from customers purchased these items (57%).  

![image](https://user-images.githubusercontent.com/105381777/190048586-eedf732d-86cf-473f-b461-a0b88958e34e.png)






