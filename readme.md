# (lyft_gobike_exploration)
## by (Shirley Monge)


## Dataset

There are 131,169 bike and information from San Francisco Bay Area. The dataset constains 16 features (duration (in seconds), start_time, end_time, start_station (id), start_station_name, start_station_latitude, start_station_longitude, end_station_id,end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip ). 
Most variables are numeric in nature, but the variables user type, member gender and station name are categorical in nature.


## Summary of Findings

 I was expecting  that if a customer is a suscriber, she might use it more frequently and for longer distances as well. Plus, I also imagined that younger people use more frequently the service. In the exploration, I found that most users ride their bikes for pretty much short distances and short periods of time. Plus, the data showed that Mondays is the day of the week where users mostly ride their bikes. 

 During the exploration of the variable distance, the histogram is right-skewed and it seemed to suggest that most of the trips have a short distance. There was a great quantity of values that seem to have zero km or "circular trips" (trips start and end at the same station). So, I removed them since this data is irrelevant and safe to drop from the model. I transformed it to be on a logarithmic scale to find more information about the short distances that users were using their bikes. 

 I also look into the most popular hour of the day were riders use the service, and which ranges of age from users was the service most popular. 


## Key Insights for Presentation

For the presentation, I start by introducing the variables that I'm trying to study with univariate exploration, and then focus on the influence of time of day and day of the week to figure out if any of those features influence the distance and amount of time spend on the bike by user type in the bivariate and multivariate exploration. 

I've made sure to use different color palettes for each quality variable to make sure it is clear that they're different between plots.