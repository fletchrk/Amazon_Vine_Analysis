# Amazon_Vine_Analysis
## Overview of Project
The purpose of this project is pick data set of an amazon review and try to determine if there is an favorable review bias from Vine members of the data set. The data set that I used was regarding pet products that was purchased on Amazon. I used PySpark to perform the ETL process by extracting the data, transforming the data and connecting to the database that was generated through Amazon AWS webserver. My goal is to determine if more Vine members have a favorable review bias of the data set. 

## Results

### Total number of reviews

•	Total Reviews

![totalreview_count]( https://github.com/fletchrk/Amazon_Vine_Analysis/blob/main/Resources/totalreview_count.png)

•	Vine Reviews

![count_of_paid]( https://github.com/fletchrk/Amazon_Vine_Analysis/blob/main/Resources/count_of_paid_5_star.png)

•	Non-Vine Reviews

![count_of_nopd]( https://github.com/fletchrk/Amazon_Vine_Analysis/blob/main/Resources/count_of_nopd.png)

### Total number of 5-star reviews

•	Total 5Star Reviews

![5star_count]( https://github.com/fletchrk/Amazon_Vine_Analysis/blob/main/Resources/5star_count.png)

•	Vine Reviews

![count_of_paid_5_star]( https://github.com/fletchrk/Amazon_Vine_Analysis/blob/main/Resources/count_of_paid_5_star.png)

•	Non-Vine Reviews

![count_of_NoPd_5_star]( https://github.com/fletchrk/Amazon_Vine_Analysis/blob/main/Resources/count_of_NoPd_5_star.png)

### Percentage of 5-star reviews

•	Vine Reviews

![Pd_percent]( https://github.com/fletchrk/Amazon_Vine_Analysis/blob/main/Resources/Pd_percent.png)

•	Non-Vine Reviews

![NoPd_percent]( https://github.com/fletchrk/Amazon_Vine_Analysis/blob/main/Resources/NoPd_percent.png)

### Summary

40% of the reviews in the Vine program were 5-Star reviews where the percentage of the non-Vine reviews is 54%. This is showing that there is a negative bias for reviews in the Vine program for pet products.
I recommend doing a further analyze and show how many stars the other reviews are receiving so that they can try to determine ways to receive better reviews i.e.. improve the product, remove the product from inventory, etc.

