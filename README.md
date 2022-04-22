# Amazon_Vine_Analysis

**Overview of the Analysis**

Our analysis seeks to analyze Amazon reviews by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for the products. Our focus is on database on musical instruments. We deployed PySpark to determine if there is any bias towards favorable reviews for Vine members  in my dataset. We created the tables on SQL usind PGAdmin.

**Results**

* Number of Vine reviews and non-Vine reviews:* 34, 8212 respectively

* Number of 5 star Vine reviews: 60

* Number of non-Vine 5 star reviews: 14477

* Perecentage of 5 star Vine reviews:56.6666%

* Percentage of 5 star non-Vine reviews: 56.72445%


**Summary**

Our analysis did not reveal any real positivity bias in favor of the vine reviews. The percentages of paid to unpaid vine reviews were 56.666 and 56.7244 respectively.
Only 34 paid vine reviews rated 5 star, while 8212 of unpaid reviews rated 5 star. It appears that only a small smaple was utilized for paid vine reviews (total count of 60) compared to the total unmber of unpaid vine reviews of 14477. in summary, one would conclude that the hypothesis is faulty and unreliable.

For better accuracy, the sample size for the paid reviews should be increased to better reflect the population data.
