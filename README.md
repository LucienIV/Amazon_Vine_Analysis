# Amazon_Vine_Analysis

## Overview
The purpose of this analysis is to take a dataset of Amazon reviews for listed video games, create dataframes from the dataset, and then analyze the data on the basis of number of stars and whether the review was part of a Vine program.

## Results

All reviews used in the analysis were taken from a larger dataset and filtered to only include reviews for products that had at least 20 reviews and, of said reviews, the majority were marked as Helpful reviews.

![image](https://user-images.githubusercontent.com/92831138/158032653-d03c76a1-2b7f-4191-866c-625eb0922acb.png)

- There were 94 Vine reviews and 40471 non-Vine reviews.

![image](https://user-images.githubusercontent.com/92831138/158032662-6a1862c6-bf90-4e9c-a66b-cbb81f8a79e5.png)

- There were 48 total Vine reviews with 5-star ratings and 15663 total non-Vine reviews with 5-star ratings.

![image](https://user-images.githubusercontent.com/92831138/158032677-756ba614-d6ba-420e-a302-a5615e7d9d58.png)

- Roughly 51% of the Vine reviews were 5-stars and roughly 38.7% of the non-Vine reviews were 5-stars.

## Summary

The initial results would indicate a positivity bias for reviews through the Vine program. Roughly 12% more of the Vine reviews were 5-stars than those of the non-Vine reviews. However, this must be weighed against the number of reviews in each dataset. There were more than 430 times as many non-Vine reviews as Vine reviews, making comparisons more difficult. There being less than 100 Vine reviews in the dataset also makes analysis more difficult, but with the data present a positivity bias can be inferred. An additional analysis that could be performed would be to run a similar analysis on other star reviews, specifically 1-star reviews to see if anything further can be inferred for the rate of positive versus negative reviews. 
