# market
### Black Friday 
**motivation** :

Simple Pyspark implementation for black friday datasets for practicing distributed computing framework 
for large-scale data processing

**Problem Statement** : 

A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) 
against various products of different categories. They have shared purchase summary of various customers for selected high 
volume products from last month. The data set also contains customer demographics (age, gender, marital status, city_type, 
stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month.

**result** :

from heatmap it shows correlation betweens different categorized of products
the result is to use machine learning to predict the purchase amount based on other column's value
Linear regression shows the best score in all metrics, followed by XGB and randomforest

dataset source is from https://www.kaggle.com/datasets/sdolezel/black-friday

### Retail Store Sales Transactions
**motivation** :

this notebook shows the work of categorizing different customer groups of clients by using pandas and pyspark

**Problem Statement** : 

There are thousands of customers with hundred of purchase behaviors, finding the patterns and categorizing them into
different level could help sellers to better make marketing strategies to follow on main groups of customers

**result** :
Kmeans cluster and rfm categorization (recency , frequency and monetary value) are used for comparison
In the result of RFM cluster , itshow that tier 1 and 2 should be main target due to its frequency and monetary value
