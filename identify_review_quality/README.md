# Identifying Reviews as Positive, Negative, or Neutral
* In order to build this classification system, I (somewhat arbitrarily) determined the words that an Air BnB guest would use to describe their visit
* I then built CASE that linked words like "perfect" or "beautiful" to positive reviews, and linking words like "bad" or "dirty" to negative reviews
* All reviews not classified as positive or negative were classified as neutral
* When building the CASE statement, I alternated line by line between words that would cast a listing as positive or negative so as to correct for the fact that the query will run in order
  * For instance: if I were to list all positive words first and all negative words second, I would get a much higher count on positive reviews
  * I also used the same number of words associated with positive reviews as words associated with negative reviews to remove further selection bias
* I showed the restuls of my query by counting each review of each type across all listings
