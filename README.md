# Amazon-fine-food-reviews

## Introduction

Amazon reviews are often the most publicly visible reviews of consumer products. As a frequent Amazon user, I was interested in examining the structure of a large database of Amazon reviews and visualizing this information so as to be a smarter consumer and reviewer.

## Machine Learning Formulation

Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).


[Q] How to determine if a review is positive or negative?

[Ans] We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.

## Data set

I've taken data set from kaggel(https://www.kaggle.com/snap/amazon-fine-food-reviews) . In the dataset there are 10 columns which are described below.

1.) Id

2.) ProductId - unique identifier for the product

3.) UserId - unqiue identifier for the user

4.) ProfileName - Customer name

5.) HelpfulnessNumerator - number of users who found the review helpful

6.) HelpfulnessDenominator - number of users who indicated whether they found the review helpful or  not

7.) Score - rating between 1 and 5

8.) Time - timestamp for the review

9.) Summary - brief summary of the review

10.) Text - text of the review


## Performance Metric
 we will use the Accuracy as a Performance Metric
