# (Ford GoBike System Data Exploration)
## by (Obichukwu Valentine Nzelu)


## Dataset

>The dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in February, 2019. The original dataset has 183412 rows and 16 columns; after wrangling, the dataset has 174952 rows and 24 columns. 
These variables includes the start and end time of the trip, its duration, the start and end station as well as the characterstics of the users such as gender, age and user type (subscriber or customer). I performed the following wrangling steps for better analysis: conversion of the duration_sec column to minutes, spliting the start time column into date, day, and hour,age, adding new columns for duration in minutes, start date in yyyy-mm-dd format, start hour of the day, and day of week.
I changed the data types to their appropriate formats for accurate analysis.
The original dataset is available in the [Udacity Classroom](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


## Summary of Findings

> While carrying out exploratory analysis, I was able to use a primary variable;duration, which helped me to see the amount of time riders spend on each trip and the factors that influence this duration. 
The majority of rides lasted between 7- 12 minutes and this took place on weekdays between 8am to 5pm

>The age of the users is between 25 and 35.The male users, which were the majority, are older than the female users

>Most riders were male subscribers who did not use bike share for all trip. Customers rode bikes for a longer duration compared to subscribers, while female bike riders had the longest average duration of bike trips for both customers and subscribers Bike trips taken during the weekend were observed to have longer durations. This can be justified by that the subscribers tend to bike the most in the morning at 8 am and afternoon at 5 pm of the weekdays;hours of going and returning from work , while customers use the bike sharing system more at midday and duting the weekends.

>The duration of the trips depends on the users characteristics such as the age and user type and on the day of week and hour of the day the trip was made.

>The trip duration of the younger users are longer than that of the older users trips. Since the female users are younger than the male users, the trips taken by female are longer.
 

Key Insights for Presentation


## Key Insights for Presentation

>For the presentation, I will focus on the influence of the three critical variables;  member_age, user_type, and member_gender on duration of trips.

>I start by showing the distribution of duration_sec variable, followed by the pattern in member_age distribution, the relationship between duration and member age, then the relationship between duration and the categorical variables (user_type and member_gender).

>Then I will demonstrate how duration varies with gender, user type, start hour, and days. I will also demonstrate how bikes were used based on these features.



