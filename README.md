# Analyzing 10Gb of Yelp Reviews Data

In this project I analyzed yelp data from [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset)
I accomplished this by first uploading data to S3, then provisioning spark cluster on AWS EMR, pointed it to S3 and finally using jupyter notebook and pyspark, conducted some analysis on it.



## Analysis
The dataset consists of five tables: business, users, reviews, checkin and tip. This project makes use of user, business and review tables to answer the questions like: what are the most popular businesses? how accurate are star ratings assigned to businesses? how big are the differences between elite and normal users and their reviews? what are considered useful reviews? 
Project makes use of spark and specifically pyspark to handle aggregations between massive data and pandas to visualize the data.
The analysis consists of 4 sections:
* Installing required packages
* Analyzing businesses by categories
* Determining business rating credibility
* Elite and non-elite yelp user comparison

