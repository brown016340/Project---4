# Project---4


This is the final project of the MSU Data Analytics Boot Camp. Group members were Benjamin Brown, Donald Ricumstrict, Drew Doran, and Khrystyne Hatt. 

The goal of this project was to build a machine learning model with at least 75% classification accuracy or 0.80 R-squared. For this we discovered a datset containing used car listings that was scraped from Craigslist postings. The information regarding th dataset can be seen here: https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data


Initally data discovery was done with SQL using pyspark by Donald. Data cleaning was required as craigslist postings are not standardized and allow varying amounts of information listed. Due to the large size of the dataset we felt confortable dropping any row containing null values, then removing columns we felt weren't helpful for the analysis. Afterwards the model names needed to be standardized. Using a dataset which contained this standardized informaion, https://www.kaggle.com/datasets/jahaidulislam/car-specification-dataset-1945-2020, Benjamin worked on method of matching these values. After a cleaned dataset was made, Drew worked on created the machine learning model. We were able to feed out cleaned data to create a model capable of reaching an r^2 value of .88 indicating a fairly accurate model. Furthere cleaning improved our model further to .90 r^2 value. Khrystyne worked on creating a Tableau dashboard to further tell the story of our data, highlight trends, and visualize important metrics. View the dashboard here: 

Tableau:
https://public.tableau.com/app/profile/khrystyne.clifton/viz/Project4_17096847947830/TransmissionCounts

Presentation:
https://docs.google.com/presentation/d/e/2PACX-1vSq71ocC0v_dUKIhSIrLdEbHGT_vQIrCHA9axqX6NlmWd4n9DfhfEbfExVEW7SviNt0MfwHtTWAj3Ve/pub?start=false&loop=true&delayms=60000
