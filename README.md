# AirBNB_SQL_Project

This is a simple project to showcase my SQL skills using a Seattle AirBnb dataset. After loading in the data, [which is publicly available](https://www.kaggle.com/airbnb/seattle), I created my own rating system to classify Air BnB Listings as Positive, Negative, or Neutral. I then grouped and ranked each listing to determine how good or bad (or neutral) they were. At the end I had a little Christmas themed fun practicing other SQL skills.

##Table of Contents:
1. [Loading in Data](https://github.com/lalark/AirBNB_SQL_Project/tree/master/create_table_load_data)
2. [Identifying Reviews as Positive, Negative, or neutral](https://github.com/lalark/AirBNB_SQL_Project/tree/master/identify_review_quality)
3. [Evaluate listings and reviews together with a left join](https://github.com/lalark/AirBNB_SQL_Project/tree/master/join_listings_reviews)
4. [Grouping the reviews for each listing by quality](https://github.com/lalark/AirBNB_SQL_Project/tree/master/group_review_quality_by_listing)
5. [Comparing the average rating of each listing to the mean](https://github.com/lalark/AirBNB_SQL_Project/tree/master/rating_variance_from_mean)
6. [Seattle Christmas 2016 Availability](https://github.com/lalark/AirBNB_SQL_Project/tree/master/christmas_2016_availabiliy)
7. [Listings in Even Months](https://github.com/lalark/AirBNB_SQL_Project/tree/master/union_even_months)

##A Note on my Data:
* I did need to make a few slight alterations to the downloaded dataset in order to properly load:
  * Modified  the listings.csv file to relace "" with nothing for NULLs.
  * Fixed one line where there was a carriage return that split a number value.   There are lines where there is a carriage return in the some of the text values but that seems to not cause a problem for the create and load script so I left those.  It means there will be carriage returns in the values of some of the columns in the listings table in your database but presumably that will not cause a problem.
