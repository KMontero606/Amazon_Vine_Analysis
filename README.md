# Amazon_Vine_Analysis
## Overview of the analysis: 
The team was tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, approximately 1600 datasets were reviewed and the reviews analyzed were from the digital video game category. PySpark was used to perform the ETL process to extract the dataset, transform the data, connected to an AWS RDS instance, and loaded the transformed data into pgAdmin. PySpark was further utilized to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results: 
### Vine Reviews:
![image](https://user-images.githubusercontent.com/106962921/193285582-65789541-4e19-4cbb-85b7-3a6f90e7b595.png)

![image](https://user-images.githubusercontent.com/106962921/193285764-57178628-fccd-4702-b777-af82d8e13a91.png)

### Non-Vine Reviews:
![image](https://user-images.githubusercontent.com/106962921/193285851-2e6b737c-f991-4252-a70f-b342af7cf31c.png)

![image](https://user-images.githubusercontent.com/106962921/193285950-8dd3b057-f4b8-4583-80dc-3f6a049ae5a1.png)

- How many Vine reviews and non-Vine reviews were there?

  - There were 0 vine reviews and 1685 non-Vine reviews

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  - There were 0 5-stars vine reviews and 631 5-star non-Vine reviews

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

  - There were 0% 5-stars vine reviews and 37% 5-stars non-Vine reviews

## Summary: 
Considering there were no Vine reviewers who left a 5-star review, a negative bias occurred. Only non-Vine reviewers left 5-star reviews at 37%. With this in mind, there does not seem to be positivity bias for reviews in the Vine program for the digital video game category. Also, there were ~1600 total reviews which is 63% who may have unfavorable reviews.

One additional analysis that can be done with the given dataset would be NLP analyses analysing the context of the reviews itself to separate the positive reviews from the negative reviews. There may be positive bias reviews within eventhough the rating system conflicts with the written reviews. Often times reviewers are content with the purchase they made and they would impart the reasoning for the low score rating.
