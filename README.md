# Introduction
This repository consists of Practical Assignment 5.1 for "Professional Certificate in Machine Learning and Artificial Intelligence". 
It includes a Jupyter notebook (.ipynb) file and also a data file (.csv) that was used to complete this assignment. 

# Getting Started
To get started with the project, download code, data from below URLs : 

# GIT URL: 
https://github.com/kapilsharma2411/assignment5_1_starter.git

# Data used for this project:
https://github.com/kapilsharma2411/assignment5_1_starter/tree/4350c7e3ceb97ff83868c51ed0dd66d510fe4072/data

# Notebook URL:
https://github.com/kapilsharma2411/assignment5_1_starter/blob/4350c7e3ceb97ff83868c51ed0dd66d510fe4072/PracticalAssignment-5_1.ipynb

# Conclusion and Data Insights: 
- Total of 12576 data entries have no car information on this dataset. It means that Car information is not significantly impacting the coupon usage and can be ignored for cleaning.
- There are very few nulls in the dataset. We can keep these rows without having much impact on the dataset.
- We also can replace "never", "less1" values in Bar, CoffeeHouse, CarryAway, RestaurantLessThan20, Restaurant20To50 columns to 0 and "gt8" to 9
- We have 57% of data entries with coupon used and 43% of entries with coupon not used in current dataset
- The Coupon usage distribution is clearly left-skewed, indicating that coffee house coupons are used more frequently than other types of coupons.
- Alternatively, it also indicates that coffee house coupons are more frequently offered or available in the dataset.
- Finally, bar distibution also shows that restaurant > $20 are the least used coupons in this dataset.
- The temperature distribution is slightly right-skewed, indicating that there are more instances of higher temperatures compared to lower temperatures.

# Bar Coupon Analysis : 
- Most people never visited bar, followed by 1~3 per week. Very few people visit bar more than 4 times a week.
- We can also see that people who visited bar more frequently are 41% more likely to accept Bar coupons compared to people who went to bar 3 or fewer times a month.
- Also, people with high bar visit frequency are more likely to accept Bar coupons.
- As we can see, there are very few entries with age under or equal to 25 in the dataset. So, we cannot confidently compare the acceptance rate of Bar coupons based on age group.
- Acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry is more than 70%
- Drivers with income less than 50K are most likely to accept Bar coupons.
- Also drivers who visited bar more than 4 times a month are more likely to accept Bar coupons.
- Also drivers under age 30 are more likely to accept Bar coupons.
- And drivers with adults passangers who are not widowed are more likely to accept Bar coupons.

# Coffee House Coupon Analysis : 
- Most people never visited Coffee House followed by people who visit coffee house 1-3 times a month, followed by 4-8 times a month. Very few people visit coffee house more than 8 times a week.
- we can see that people who visit bar more frequently are 41% more likely to accept Bar coupons compared to people who went to bar 3 or fewer times a month.
- Also bar chart shows that people with high coffee house visit frequency are more likely to accept Coffee House coupons.
- There are very few entries with age under or equal to 25 in the dataset. So, we cannot confidently compare the acceptance rate of Coffee House coupons based on age group.
- Generated graph clearly shows that people who are traveling "Alone" are more likely to accept "Coffee House" coupon, followed by the ones traveling with "Friend(s)".
- People traveling with "Kid(s)" are least likely to accept a "Coffee House" coupon.

