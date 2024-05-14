# Introduction 
This project is an assignment for the AI/ ML certification course offered by UC Berkeley. In this project, I am analyzing the data set using various analytical tools to answer the question "Will a customer accept the coupon"

# Pre-requisites 
The libraries used in the code are:
Pandas, Numpy, Seaborn, Matplotlib.pyplot

# Data
The data set is survey data that describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

# Code
The link to the actual code is: https://github.com/mimibhatt/customer_coupon_data_analysis/blob/main/prompt.ipynb

The link to the data file is: https://github.com/mimibhatt/customer_coupon_data_analysis/tree/main/data

# Summary of Findings
Over all the number of drivers that accepted any coupon exceeded the number that did not accept
As per the historgram, most of the drivers were driving in a warm weather around a temperature of 80

## Analysis on the bar coupons
1. About 41% of the drivers going to the bar accepted the bar coupon
2. The Acceptance rate for drivers who went to bar 3 or fewer times is almost half of those who went more than 3 times
3. The acceptance rate for drivers who go to bar more than once a month and 25 years or older is more than double that of the rest
4. The acceptance rate for coupon is pretty high for drivers who go to bar more than once a month, have passangers who are not kids and the occupation is not 'Farming, Fishing & Forestry'
5. Drivers who have income less than 50K and go to the cheap restuarants tend to not accept the coupon that often. The majority who accepted the bar coupons are the drivers who go to bar more than once a month and who do not have kid passenger and not widowed OR they are under the age of 30 and go to bar more than once a month
### In conclusion, bar coupons have more chances of getting accepted for age group of 25 year or older, no kids as passanger, and who tend to visit the bar more frequently.
## Analysis on the coffee coupons
1. Almost 50% of the drivers who go to coffee house accepted the coupon
2. The acceptance rate for the coffee coupon for people who went to coffee house more than 3 times is more than that of people who went 3 or less than 3 times
3. The proportion of female drivers versus male drivers who accepted coffee coupon are pretty close
4. From the above histogram, it looks like the drivers below the age of 30 go to coffee house more than 30 plus
5. The 3 occupations with most coffee house drivers are - Unemployed, Student and Computer & Mathematical occupation, but the occupations with the highest acceptance rate for coffee coupons is Healthcare Practioners and Technical
6. The acceptance rates between those drivers who: go to coffeehouse more than once a month, had passengers that were not a kid, and were not widowed OR go to coffeehouse more than once a month and are under the age of 30 OR go to cheap restaurants more than 4 times a month and income is less than 50K are pretty similar
### In conclusion, it may be said that the acceptance rate for coffee coupons would be higher if we target the right age group and occupations
