# Amazon_Vine_Analysis

## Overview 

The purpose of this analysis was to use our knowledge of PySpark and Google Colab Notebooks along with SQL to extract data from a website, put into a dataframe and then upload that data in SQL through AWS. 

## Results 

### Total Reviews For Vine
<img width="653" alt="Screen Shot 2021-10-12 at 8 08 45 PM" src="https://user-images.githubusercontent.com/48080598/137049611-7b8bf5dc-5ed5-4339-ab52-867f27e8ee5e.png">

### Total Reviews For non-Vine 
<img width="721" alt="Screen Shot 2021-10-12 at 8 09 35 PM" src="https://user-images.githubusercontent.com/48080598/137049649-43ad9bb4-2467-4f21-ad2c-e2cecf108049.png">

### Total 5 Star Vine Reviews
<img width="710" alt="Screen Shot 2021-10-12 at 8 10 08 PM" src="https://user-images.githubusercontent.com/48080598/137049678-ab6d04a2-45b9-4a86-ad6c-05418fe30263.png">

### Total 5 Star non-Vine Reviews
<img width="776" alt="Screen Shot 2021-10-12 at 8 10 49 PM" src="https://user-images.githubusercontent.com/48080598/137049718-d2f5b894-cdb8-41cb-81a0-430bcfb23a59.png">

### Percentage of 5 Star Vine Reviews
<img width="588" alt="Screen Shot 2021-10-12 at 8 12 01 PM" src="https://user-images.githubusercontent.com/48080598/137049795-aa9d09fb-e5c9-43bd-a2d7-0c9e7a6e2094.png">

### Percentage of 5 Star non-Vine Reviews
<img width="693" alt="Screen Shot 2021-10-12 at 8 12 25 PM" src="https://user-images.githubusercontent.com/48080598/137049822-2e42c888-9a6c-4be9-9f1a-e3d51ee5fd8c.png">

## Summary 
From looking at the results, we see that the number of Vine reviews are far less than the number of non-Vine reviews (613 to 64986). When looking at the number of 5 star reviews for each category, about 36% of the Vine reviews were 5 star reviews while about 47% of the non-Vine reviews were 5 star reviews. This shows that there isn't a positivity bias in this data because the non-Vine reviews have more of a percentage of 5 star reviews than the Vine reviews (regardless of the total number of reviews). An additional test we could do is project the number of 5 star reviews for Vine if they had a lot more reviews because they have a lot less in this dataset. If Vine had a total more close to 60,000, how would the percentage of 5 star reviews change and would that show if there is a bias towards Vine or not?


