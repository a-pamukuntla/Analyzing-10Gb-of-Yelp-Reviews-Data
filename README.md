# Analyzing-10Gb-of-Yelp-Reviews-Data

Analyzing 10Gb of Yelp Reviews Data is about applying what I have learned about configuring and provisioning infrastructure using the AWS Elastic Map Reduce ecosystem.

I provisioned a Spark cluster on AWS EMR and connected it to a Jupyter Notebook. I performed data analysis with PySpark to deal with large [Yelp Dataset](https://www.kaggle.com/yelp-dataset/yelp-dataset). 

## Analysis
### Part I: Installation and Initial Setup
In this portion, I imported the necessary dependencies (pandas, matplotlib, seaborn, scipy) and loaded the dataset as a pyspark dataframe.
### Part II: Analyzing Categories
For this part, I analyzed categories of business data. I split categories into unique categories and created a bar chart of top 20 categories.
### Part III: Do Yelp Reviews Skew Negative?
I analyzed review and business datasets to compare the written reviews given by users and the overall business rating. I calculated and plotted the skew of Yelp Reviews.
### Part IV: Should the Elite be Trusted?
Similar to part III, I calculated and plotted the skew of Elite User Reviews to find out it Elite Users are honest with their reviews.
## Cluster and Notebook Configs
![notebook](assets/cluster_configuration.png)
![cluster](assets/notebook_configuration.png)
