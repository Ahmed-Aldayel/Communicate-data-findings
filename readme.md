# Ford Go bike Data year - 2017
## by (Ahmed Aldayel)


## Dataset
I have choosen the Ford Go Bike Data year - 2017

The shape of the dataset is (519700, 10) and there is not any null value.

i have drop these column ('start_station_latitude','start_station_longitude', 'end_station_latitude', 'end_station_longitude') so the columns in my dataset now is :

1-duration_sec
2-start_time
3-end_time
4-start_station_id
5-start_station_name
6-end_station_id
7-end_station_name
8-bike_id
9-user_type
10-day


## Summary of Findings

first i have started on Univariate Exploration: i have look to the look to the distribution for duration_sec, distribution bike id, distribution user type, and distribution day.

then i have looked on Bivariate Exploration : i have do the relation between day and user_type, relation between bike_id and duration_sec and relation between Duration and User Type.

finnaly i have looked on Multivariate Exploration : i have do the relation between Trip Duration(sec), user_type and Day so in this exploration we have known the customers are using the bike much longer duration in day than the subscribers.

## Key Insights for Presentation
From that insight we know that the Subscribers are higher than Customer, but the customer ride the bike most than subscribers in the day and have much longer trip duration than subscribers, so we can get benefit from this data to how encourage the subscribers and give some encouragement offer to the customer too.