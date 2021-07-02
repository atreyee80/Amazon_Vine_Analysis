# Amazon_Vine_Analysis
## Overview of the analysis: Explain the purpose of this analysis.
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project we need to analyze product reviews if there is any bias or not, I choose the dataset of "Amazon_reviews_us_Health_Personal_Care" and using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.






## Results: Using bulleted lists and images of DataFrames as support, address the following questions:






. How many Vine reviews and non-Vine reviews were there?
![](Vine_reviews_yes.png?raw=true)
![](Vine_reviews_no.png?raw=true)


. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![](Five_star_vine_yes.png?raw=true)
![](Five_star_vine_no.png?raw=true)

. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![](Percentage_five_star_vine_yes.png?raw=true)
![](Percentage_five_star_vine_no.png?raw=true)


## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
There is no bias in the vine program.The percentage of vine reviews with 5 stars is 44% and the percentage of non-vine reviews with 5 stars is 62%.

![](Percentage_five_star_vine_yes.png?raw=true)
![](Percentage_five_star_vine_no.png?raw=true)

Vine resluts for star rating 4 shows that 
![](Five_star_vine.png?raw=true)
![](Percentage_four_star_vine.png?raw=true)
