# Amazon Vine Review Analysis

## Overview of Analysis

### The Amazon review system is an integral part of online shopping and product reviews are often used in a customer's decision making process. This challenge focused on if there was a bias towards favorable reviews from vine members who were paid to promote a selected dataset of products. 

* ### Programs used in this challenge was Google Colab, PgAdmin 4, AWS, and Postgres SQL 12.8.1 R. 
* ### The data we used was focused on Musical-based reviews on Amazon.com

## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

* ### How many Vine (paid) reviews and non-Vine (unpaid) reviews were there?
  * ### There were 60 vine reviews and 14477 non-paid reviews. 
    
* ### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  * ### There were 34 5-star vine reviews and 8212 non-vine 5-star reviews. 
  
* ### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  * ### The percentage of vine reviews at 5-stars was 56.67%. The percentage of non-vine reviews were 56.72%. 


## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

### Based on the summary statistics, there was no statstically significant level of positivity bias between the vine reviews (paid review) and the non vine reviews (unpaid). Vine reviews had a slightly lower 5-star percentage of 56.67%, and the non vine reviews had an average 5-star review of 56.72%. An additional analysis that could be done on this data would be to perform a regression analysis and t-test to ensure there is not any statistically signficance between vine and non vine members. 
