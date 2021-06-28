# Amazon_Vine_Analysis

## Overview of the Analysis
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

In order to conduct this analysis, PySpark was used to perform an ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. PySpark was then used to determine if any bias toward favorable reviews was present among Amazon Vine members. 

Amazon's grocery dataset was chosen for this analysis.  

## Results

### Number of Reviews:
- **Vine:** 61
- **Non-Vine:** 28,287

![# of Reviews](https://github.com/tysonseang/Amazon_Vine_Analysis/blob/main/Imagery/Total%20Paid%20%26%20Unpaid%20Votes.png)

### Number of 5-Star Reviews:
- **Vine:** 20
- **Non-Vine:** 15,689

![# of 5 Star Reviews](https://github.com/tysonseang/Amazon_Vine_Analysis/blob/main/Imagery/Number%20of%205%20star%20votes.png)

### Percentage of Reviews that were 5 Star:
- **Vine:** 33%
- **Non-Vine:** 55%

![% That Were 5 Star](https://github.com/tysonseang/Amazon_Vine_Analysis/blob/main/Imagery/%25%20that%20were%205%20star.png)


## Summary

Based on an analysis of paid and unpaid reviews, it does not appear that Amazon Vine reviews are biased toward positive responses. While roughly 1/3 of paid reviews received a 5-star review on the platform, more than 55% of unpaid reviews received a similar rating. In order to further analyze review content, natural language processing analysis can be conducted to gauge the positive, neutral, and negative sentiment of responses and determine if paid reviews are more likely to skew positive in nature. 