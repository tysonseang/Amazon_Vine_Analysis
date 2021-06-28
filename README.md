# Amazon_Vine_Analysis

## Overview of the Analysis
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

In order to conduct this analysis, PySpark was used to perform an ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. PySpark was then used to determine if any bias toward favorable reviews was present among Amazon Vine members. 

## Results

**Number of Reviews:**
- Vine:
- Non-Vine:

![# of Reviews](https://github.com/tysonseang/Amazon_Vine_Analysis/blob/main/Imagery/Total%20Paid%20%26%20Unpaid%20Votes.png)

**Number of 5-Star Reviews:**
- Vine:
- Non-Vine:

![# of 5 Star Reviews](https://github.com/tysonseang/Amazon_Vine_Analysis/blob/main/Imagery/Number%20of%205%20star%20votes.png)

**Percentage of Reviews that were 5 Star:**
- Vine:
- Non-Vine:

![% That Were 5 Star](https://github.com/tysonseang/Amazon_Vine_Analysis/blob/main/Imagery/%25%20that%20were%205%20star.png)


## Summary



In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.