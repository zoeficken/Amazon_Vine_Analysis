# Amazon_Vine_Analysis

## Overview of the Analysis

The purpose of this analysis was to take on the larger project of analyzing Amazon reviews written by members of the paid Amazon Vine program. I picked a dataset on popular Amazon apparel and used PySpark to perform the ETL process. I then used PySpark to determine if there was any bias toward favorable reviews from Vine members in my dataset.

## Results

- How many Vine reviews and non-Vine reviews were there?

<img width="384" alt="Screen Shot 2021-11-28 at 8 54 47 PM" src="https://user-images.githubusercontent.com/88108455/143797087-d861c4bd-01a4-4ac4-a129-d2a86e5c2f6f.png">

127 vine reviews and 85859 non-vine reviews

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

<img width="711" alt="Screen Shot 2021-11-28 at 8 56 36 PM" src="https://user-images.githubusercontent.com/88108455/143797241-4b77fe7b-fe70-48e7-81f7-e037a8c9f8ea.png">

63 5-star vine reviews and 39396 non-Vine 5 star reviews

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

<img width="501" alt="Screen Shot 2021-11-28 at 8 58 02 PM" src="https://user-images.githubusercontent.com/88108455/143797296-a18f7b87-64a1-4d6e-be39-80971675efff.png">

49.6% were Vine reviews that were 5 stars while 45.9% were non-Vine reviews that were 5 stars

## Summary

There is definitely a little bit of bias with the Vine reviews. The percentage of 5 star reviews from Vine users is larger than that of non-Vine users. I think another part of this analysis should have included the amount of 1 and 2 star reviews fron Vine users.
