# Amazon_Vine_Analysis

## Overview

The purpose of this project is to help BigMarket, optimize its marketing strategies and efforts through data analysis. One of its main clients, Sellby, is going to share some valuable products and information on its website, however, they asked us to do an analysis of how its products' reviews compare to other's companies and based on that give new programs and rewards to its customers. 

We will complete the analysis by using AWS, Spark, PgAdmin and and more importantly Google Colaboratory. The following are the results of the analys

## Results

1. The total amount of Vine reviews and non-Vine reviews are:

+ Vine Reviews 9paid program )= 613

![paid review](https://user-images.githubusercontent.com/115424156/232235500-9f77988b-b771-4c80-a068-2fb1d8fea7dc.png)


+ Non-Vine Reviews 9unpaid progarm) = 64,968

![unpaid reviews](https://user-images.githubusercontent.com/115424156/232235716-ac3358c3-b963-45f4-8f99-6fee56e76852.png)


2. The total amount of Vine reviews and Non-Vine reviews that got 5 stars are:

+ Vine Reviews 5 Stars = 222

![5 stars paid review](https://user-images.githubusercontent.com/115424156/232236147-6f8f394d-dc78-4a4c-be1b-01cca07068c8.png)

+ Non-Vine Reviews 5 Stars = 30,543

![5 -star unpaid](https://user-images.githubusercontent.com/115424156/232236722-ee04193d-820a-4bf8-86e6-02b06b414a11.png)


3. The total percentage of Vine and Non-Vine reviews that got 5 stars are:


+ Percentage of Vine Reviews 5 Stars = 36.2%

![perecentage of paid 5 star review](https://user-images.githubusercontent.com/115424156/232237059-6fbcf061-5368-416d-9e95-a584417ca3d4.png)

+ Percentage of Non-Vine Reviews 5 Stars = 47.0%

![percentage of 5 star unpaid](https://user-images.githubusercontent.com/115424156/232237120-c53ec114-17f9-4155-a431-4b05f061c3ae.png)


## Summary

There is a larger pool of participants in the non-paid program which will make their opinion more credible than that of the vine program, which indirectly can be viewed as seller of reviews. The paid program also tends to give lower 5-star rating (36%) compared to non-vine reviewer (47%). Although I don't want to overread based on this one set of data, it seems vine program members are hesitant to give 5-star rating as if they were afraid to be positive raters since they are paid for their  review. 
From the results, there appears to be a bias, implied or explicit, in the review with the vine program members. 

To validate these findings, I would conduct another review based 1/ another category of items or 2/ ask for reviews but without the reviewer being in either group. Basically, the reviewer might be paid or might not be paid after their review. This, i believe will help get a better reading on the level of bias or the authenticity of the review. 

