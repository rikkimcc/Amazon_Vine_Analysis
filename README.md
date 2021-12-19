# Amazon_Vine_Analysis

## Overview of the analysis: 
In this analysis, we are analyzing Amazon reviews written by members of the paid Amazon Vine program. Using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, using PySpark to determine if there is any bias toward favorable reviews from Vine members.

## Results:

1. How many Vine reviews and non-Vine reviews were there?
- There were 94 Vine reviews and 40,471 non-Vine reviews

<img width="348" alt="Screen Shot 2021-12-19 at 2 43 24 PM" src="https://user-images.githubusercontent.com/89141436/146688609-56599427-445f-4b9c-87d3-af30ad0f607e.png">

<img width="348" alt="Screen Shot 2021-12-19 at 2 43 47 PM" src="https://user-images.githubusercontent.com/89141436/146688604-a2b2c100-234b-44c9-97be-c7a3482db2a2.png">

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- 48 5-Star reviews were Vine and 15,663 5-Star reviews were non-Vine

<img width="348" alt="Screen Shot 2021-12-19 at 2 45 35 PM" src="https://user-images.githubusercontent.com/89141436/146688678-7f0c5722-23e1-49d7-b900-08750891b9b3.png">

<img width="348" alt="Screen Shot 2021-12-19 at 2 46 40 PM" src="https://user-images.githubusercontent.com/89141436/146688679-73547554-2b41-40b2-9b03-84bf5ec38fe4.png">

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 51% of vine reviews were 5-Stars and 38.7% of non-Vine reviews were 5-Stars

<img width="348" alt="Screen Shot 2021-12-19 at 2 48 33 PM" src="https://user-images.githubusercontent.com/89141436/146688738-8d3f87a3-53c9-4a3f-9a8a-8b5cca681089.png">

<img width="348" alt="Screen Shot 2021-12-19 at 2 48 41 PM" src="https://user-images.githubusercontent.com/89141436/146688739-03f3706b-c8c1-4dd7-9d4c-619596f196b4.png">
