# Amazon_Vine_Analysis

## Overview
The purpose of this analysis was to review Amazon reviews that were written by members of the paid Amazon Vine Program. Ultimately, I wanted to determine if there was any bias from the paid reviews compared to the non-paid reviews of the same product and it's effect on a product's 5 star rating. To conduct the analysis, I analyzed Amazon reviews of different video games. I utilized Pyspark to perform ETL on data that was stored in an AWS RDS database and then load my cleaned data into PGAdmin. Once I had my clean data neatly stored in a clean database, I was able to export it into a CSV to perform further analysis. I finsihed my analysis by using Pandas to test my hypothesis and see if there was more bias from the paid reviews. 

## Results

![image](https://user-images.githubusercontent.com/84791455/136713055-c4de4d67-68e7-43ec-a7ae-7a78972be952.png)


How many Vine reviews and non-Vine reviews were there?

-- Overall, there were 15,742 Vine sponsored reviews and 49,637 non-sponsored reviews

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

-- There were 4,704 5 star reviews from the Vine reviewers and 15,783 from the non-vine reviewers.

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

-- The % of Vine reviews that were 5 stars was 29.8% and the % of non-vine reviews that were 5 stars was 31.7%.

## Summary
Based on my analysis, I cannot statistically say there is a bias from the paid reviews compared to the non-paid reviews. It turns out, based on this dataset, consumers of video games are more likely to naturally give the product a 5 star rating because the % of ratings was 2% higher for the non-paid reviews.

## Additional Analysis
I could have ran a similar analysis for the average star rating and see if the paid vs. non-paid reviews showed any statistical difference. I could have also analyzed the helpful to total vote ratio to see if that showed any bias as well. 

![image](https://user-images.githubusercontent.com/84791455/136713283-95f66daa-107e-4db8-aac0-71e9ee51020a.png)

![image](https://user-images.githubusercontent.com/84791455/136713287-f8e487c7-61e6-44b2-b574-7caabd22fe4a.png)


