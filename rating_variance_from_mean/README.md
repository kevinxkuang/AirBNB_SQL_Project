# Comparing the Average Rating of Each Listing to the Mean
* Beyond simply [classifying listings as good or bad by the positive or negative experiences of past guests](https://github.com/lalark/AirBNB_SQL_Project/tree/master/group_review_quality_by_listing), I wanted to see how good or bad each listing was
* In order to do this, I built a subquery that evaluated how close the average ranking of each listing was to the total average ranking of all listings - also known as the variance of each listing from the mean
* A large variance from the mean indicated that a listing as extreme - either way more positive, way more negative, or way more neutral
* This allowed me to see which good and bad listings were actually not far from average, and which were exceptional
