#FordGo Bike System Data Exploration

## Dataset

The data consists of information regarding 183412 bike rider in this dataset 
with 16 features that held various informations about each row, including
duration, start_time, start_station_name, and other features related to 
informations about bike and users like Id's, user_type, age and gender.



## Summary of Findings

In the exploration data analysis step, I have investigated about 'duration' and
then about the most frequent start_hour and start_dayofweek, and I found that 
hours from 8am to 9am and from 17pm to 18pm are rush hours and Thursday is the 
most frequent day in term of bike usage.
When investigate the relationship between of each of start_time features and
'duration', I found that majority of trip durations during rush hours fall in the
range of time [1, 15] minutes and most of longets trip durations are indicated 
after midnight. On the other hand, 'duration' feature variate moderately by the
the 'member_gender' features, the result say that female gender have more important
durations than male althogh male gender seems to be much more important in term of 
frequency of bike usage, and by 'user_type' customers have generaly the longest trip
durations in our dataset, while subscribers present the shortest trip durations.
After exploring the frequency by each of the most 10 start_station_name, I found that
some of stations were more important in term of frequency, which may help to ask
more further questions about bike availability and usage frequency in order to 
improve the bike system is these stations.

Outside of the main variables of interest, I verified the linear relationships
between all features but I found that does not make a sense, and majority of 
scatter plots have shown a weak relations, which maybe explained by the nature of 
each feature in our dataset, even for features with numeric type like 'longitude'
and 'latitude', linear relation does not make a sense.


## Key Insights for Presentation

For the presentation, I focus on determine the most frequent hour and day
in term of bike usage and the distribution of trip duration also how does 
the trip duration variate function of other features (start_time, categories).
Features related to location were leaved out. I start by exploring the duration
variable, and then I have determined most frequent start_hour, start_dayofweek
and start_station_name.

Afterwards, I have entered categorical variables 'user_type' and 'member_gender'
into the analysis. I have used barplots and pointplot and color encoding for 
each categories to show especially the variation of trip duration by each of 
user_type and by each gender.
