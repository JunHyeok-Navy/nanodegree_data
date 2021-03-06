# Boston Airbnb Analysis
Project of Nanodegree in Udacity

## Motivation
This project (Write a Data Science Blog Post) is part of Udacity's Data Scientists Nanodegree Program. Detailed analysis with all needed code is posted in this Github repository.

At first, airbnb is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities.
I used airbnb many times. At that time, I felt so comfortable to tour and book rooms! So I chose this 'Airbnb Boston Data' to my project. There are 3 business questions and answers with following CRISP-DM methodology.

Here are my business questions!

1. Which neighbourhood have high prices (Basic Clustering)?
2. Which street is richest? - By our data, we can analyze which streets are Top 5 richest!
3. Relationship between Positive & Negative words in review data & review_scores, price

Medium blog path : https://junhyeokpark.medium.com/analysis-of-boston-airbnb-data-5f82b556c12f

## Used Library

* **Pandas** - Handling Dataframe
* **Numpy**  - Handling Array
* **tqdm**   - Visualization of progress
* **Seaborn & Matplotlib** - Visualization of data

## Data Set

* **listings.csv** : Including full descriptions and average review score
* **reviews.csv**  : Including unique id for each reviewer and detailed comments

## CRISP-DM

1.  Business understanding
2.  Data understanding
3.  Data preparation
4.  Modeling
5.  Evaluation
6.  Deployment

## Result & Conclusion

1. Which neighbourhood have high prices (Basic Clustering)?
*   **The richest neighbourhood is Leather District! And we can see the clustering of roomtype - price. Type - entire home/apt is most expensive roomtype!**
2. Which street is richest? - By our data, we can analyze which streets are Top 5 richest!
*   **Boston Wharf Road, Congress Street, 8th Street, Edgerly Road, West 1st Street are Top 5 richest street! By google map, these streets are near by ocean!**
3. Relationship between Positive & Negative words in review data & review_scores, price
*   **The most sensitive to review words is review_scores_cleanliness! It means that most of reivewer left a review of room cleanliness.**

We can use CRISP-DM Method to analyze any data! This method can be a pipline of data analysis.
I hope my skill getting improved to analyze various data even if these are being complicated!

There are many variables related to price.
We can analyze those features to predict future target.

In next version, I wanna use many algorithms to make my own model!

## Acknowledgements

This project's data is from Boston_Airbnb_Data [data-link](https://www.kaggle.com/airbnb/boston).

## Thanks.
