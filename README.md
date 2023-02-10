# Amazon_Vine_Analysis
## Overview: 
The project involves analyzing Amazon Vine program reviews to determine any bias towards favorable reviews. 50 datasets containing reviews for various products will be selected from S3 and processed through PySpark ETL. The transformed data will be loaded into an AWS RDS instance through pgAdmin, and analyzed using PySpark. The results will be summarized and submitted to the SellBy stakeholders through Jennifer.

## Results: 

### Number of 5 star reviews there were from both Vine and non-Vine
![Image 1](https://github.com/Sergg99/Amazon_Vine_Analysis/blob/390ab312e7afd635e650cb30675c29b9841a59fa/Resources/How%20many%205%20star%20reviews%20there%20were%20from%20both%20Vine%20and%20non-Vine%20members.jpg)

- The 5-star reviews ratio among both Vine and non-Vine members was analyzed, with Vine users accounting for 35.88% and non-Vine members accounting for 58.37%. These figures highlight the positive sentiment of the customers who have used these beauty products, regardless of whether they were part of the Vine program or not.

### Percentage of 5 star reviews from both Vine users and non-Vine members
![Image 2](https://github.com/Sergg99/Amazon_Vine_Analysis/blob/390ab312e7afd635e650cb30675c29b9841a59fa/Resources/Percentage%20of%205%20star%20reviews%20from%20both%20Vine%20users%20and%20non-Vine%20members.jpg)

- The number of 5-star ratings received from both Vine and non-Vine members was analyzed and it was found that a total of 224 reviews were given a 5-star rating. Out of these, 40525 were from non-Vine members, highlighting the favorable nature of these beauty products among a broad audience.

### Number of Vine and non-Vine reviews
![Image 3](https://github.com/Sergg99/Amazon_Vine_Analysis/blob/390ab312e7afd635e650cb30675c29b9841a59fa/Resources/Number%20of%20Vine%20and%20non-Vine%20reviews.jpg)

- The data reveals that there were 616 reviews that were part of the paid Vine program, while there were 69,432 reviews that were not part of the Vine program. The analysis of these reviews shows a favorable response to the beauty products, with 36% of Vine reviews and 47% of non-Vine reviews giving a 5-star rating. Despite the disparity in numbers, the results indicate that the positive feedback given to these products are a result of both organic and paid reach.

## Summary: 

Summary:
In this assignment, two datasets of beauty product reviews were analyzed - one consisting of records that were part of the Vine program (paid) and the other consisting of records that were not part of the Vine program (unpaid). The data showed that 36% of records that were part of the Vine program gave a 5-star rating, while 47% of records that were not part of the Vine program also gave a 5-star rating. This indicates that the positive feedback given on these beauty products is favorable both by organic reach and paid reach. Additionally, there were significantly fewer records that had Vine, meaning there is less possibility of bias in the Vine/Star-Rating reviews. The results suggest that the beauty products have received positive feedback from a large number of both organic and paid sources.
