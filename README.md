# Amazon_Vine_Analysis
[Vine Review Analysis File](https://github.com/pranavspatel/Amazon_Vine_Analysis/blob/main/Vine_review_analysis.ipynb)
For this project, we have been asked to pick one dataset from the Amazon Review datasets and submit it to an ETL process. We will use technologies such as Pandas, Google Colab, Jupyter notebook, PostgreSQL, AWS to mine the dataset. By doing so, we intend to meet this challenge's requirements, namely:

1 extract the dataset,
2 transform the data,
3 connect to an AWS RDS instance, and
4 load the transformed data into pgAdmin. Finally, using PySpark, Pandas, or SQL we will determine whether there 
  exists any bias toward "favorable reviews from Vine members in the chsen dataset".

## Objective
Using PySpark, Pandas, or SQL, We’ll determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis, We'll determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

## Results
1. There are 61 paid vine reviews out of this 20 are 5 star reviews so the total percentage of 5 star review for paid vine reviews comes out to be 32.78 %

![alt text](https://github.com/pranavspatel/Amazon_Vine_Analysis/blob/main/resources/1.jpg)


2. There are 28287 unpaid vine reviews out of this 15689 are 5 star reviews so the total percentage of 5 star review for unpaid vine reviews comes out to be 55.46 %

![alt text](https://github.com/pranavspatel/Amazon_Vine_Analysis/blob/main/resources/2.jpg)

## Summary

1. We can say from the above results that there is negative bias with respect to the vine purchase. The people who bought the vine are having less 5 star rating(22.68 % difference) as compared to the people who did not purchased the vine.

2. So people purchasing the vine are not happy with the quality or are not pleased with the vines they purchased. One of the solution to thiscan be to improve the quality or provide more options to the customers. Getting a feedback from the customes can also help.