# Amazon Vine Analysis

## Project Overview
This project is intended to determine whether or not the client, $ellby, should invest in the Vine program before selling their products on Amazon. $ellby needs to determine whether or not the cost of the Vine program--which provides gifts to reviewers--is worth the cost. In order to determine the worth of this service, I analyzed data from kitchen product reviews and compared the reviews of Amazon Vine Users to the typical Amazon user. 

### Note:
In order to answer the following questions,. I...
* Cleaned the data by dropping any null values.
* Filtered the data to focus on items with more than 20 reviews.
* Filtered the data to focus on items where more than 50% of the reviews were deemed "helpful." 

The following data frame represents the aggregated data pulled from this filtering process:

![final table](https://user-images.githubusercontent.com/93888037/163578146-e9e5864b-8a5e-4240-95c1-39a137c9a71f.png)

## Questions: 
1. How many Vine reviews and non-Vine reviews were there?
* There were a total of 99,017 reviews in the final clean data set. 
* An overwhelming majority of these reviews (97,810) were provided by traditional Amazon users. 
* A much smaller margin (1,207) were provided by Vine users. 

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* Vine users contributed 509 5-star reviews.
* Non-vine users contributed 45,846 5-star reviews. 

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* 42% of Vine Users' reviews were 5-star ratings.
* Nearly 47% of Non-Vine Users' reviews were 5-star ratings. 


## Summary:
* There does not seem to be any positivity bias among the Amazon Vine reviews. In fact, it appears that Amazon Vine reviewers might be slightly reluctant to provide a 5-star review since the percentage of 5-star reviews among Vine users is lower than that of the traditional Amazon user. 
* At this time, there does not seem to be enough value in the Vine program to invest.
* In order to confirm that the Vine program is not worth the investment, I would want to run the same analysis with different product groups to see if there is a variation in the data among different product groups.
