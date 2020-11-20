# Amazon_Vine_Analysis

## Analysis Overview
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.

The Sample dataset we use is Music

    <img src="https://github.com/harryleelhl/Amazon_Vine_Analysis/blob/main/1.png"> 
    
How many Vine reviews and non-Vine reviews were there?
The number of paid Vine reviews were 7 and the number of non paid Vine reviews were 105, 979

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
The number of paid Vine 5 star reviews were 0 and the number of non Vine 5 star reviews were 67,580.

What percentage of paid Vine reviews were 5 stars?
The percent of paid Vine 5 star reviews was 0 %.

What percentage of non-Vine reviews were 5 stars?
The percent of non paid Vine 5 star reviews was 63.76%.


## Summary
0% of the reviews in the Vine program were 5 stars reviews, however this is because the total number for Vine program is too small.

whereas the percentage in the non-Vine reviews is 63%. 
If the sample size is bigger for vine reviewer and the percentage is higher than non-vine reviewer, then it describes a positivity bias for reviews in the Vine program. If the sample size is bigger for vine reviewer and the precentage is lower than non-vine reviewer, then it describes a negative bias for reviews in the vine program.

Another analysis that we could do to check the sample like automobile or video game where the sample size for both reviewer groups are big enough to make more logical explianation.
