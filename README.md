# (FordGoBike - Trip Data)
## by (Subrat Kumar Singh)


## Dataset

For this project, I have selected FordGoBike-Trip Data. There are 183412 records in the dataset with 16 features/columns duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_longitude, start_station_latitude, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, and after handling the missing values the number of records remains 174592

First loaded the dataset, and had a look on the top 5 records, what sort of values are presents, if there any missing value or not. Then looked on the shape of the dataset to identify the no.of rows and columns. Now want to know the datatype of each columns and found there are 9 integer/float columns, 2 datetime columns and 5 object/str type columns. Then identified target columns according to area of exploration. Finally drop all the null values from the target columns to perform analysis


## Summary of Findings

The univariate analysis showed that most bike rides were short-duration trips, indicating that the bike-sharing system is mainly used for daily commuting. Subscribers contributed the highest number of rides, male riders dominated the dataset, and most users belonged to the 20–40 age group. The start and end station analysis also showed that only a few stations handled most of the bike traffic.

The bivariate analysis revealed that user type had the strongest relationship with trip duration, where Customers generally took longer rides than Subscribers. Age showed only a weak relationship with trip duration, while trip duration patterns across genders remained relatively similar. Start and end stations also showed noticeable variation in ride durations.

The multivariate analysis further showed that Customers consistently took longer rides across different age groups and gender categories, while Subscribers mainly used the service for shorter commuting trips.

## Key Insights for Presentation

1. Most bike rides are short-duration commuting trips.
2. Subscribers contribute the majority of rides on the platform.
3. Customers generally take longer rides than Subscribers.
4. Male riders and users aged 20–40 dominate the dataset.
5. Age shows only a weak relationship with trip duration.
6. Trip duration patterns across genders are relatively similar.
7. Customers consistently show longer ride durations across different demographic groups.