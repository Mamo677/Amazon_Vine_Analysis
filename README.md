# Overview of Project
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.
# Results: Using bulleted lists and images of DataFrames as support, address the following questions:

# How many Vine reviews and non-Vine reviews were there?
  Total Number of Reviews PAID and 'helpful': 136.000000
   Total Number of Reviews NON-PAID and 'helpful': 18019.000000

# How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
447716.000000

# What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
   Number of 5-Star Furniture Reviews PAID: 1356.000000
   Percent of 5-Star Furniture Reviews PAID: 0.003029
   Number of 5-Star Furniture Reviews NON-PAID: 446360.000000
   Percent of 5-Star Furniture Reviews NON-PAID: 0.996971
# SUMMARY
   The majority of reviews for Furniture product are almost nothing or lower results from Vine participants: 99.6% are Non-Vine.
  And overall of all 5 Star reviews are also the same as the Furniture, all are from Vine participants: 99.7% of all 5-star reviews are non-Vine.
   But we need to highlight that not all of the 5 Star reviews are coming from Vine participants.
