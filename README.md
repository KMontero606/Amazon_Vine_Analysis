# Amazon_Vine_Analysis
## Overview of the analysis: 
The team was tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, approximately 50 datasets was reviewed and the reviews analyzed were from the video game category. PySpark was used to perform the ETL process to extract the dataset, transform the data, connected to an AWS RDS instance, and loaded the transformed data into pgAdmin. PySpark was further utilized to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results: 
Using bulleted lists and images of DataFrames as support, address the following questions:
- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Summary: 
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
