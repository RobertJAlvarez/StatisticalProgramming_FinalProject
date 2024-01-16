# Statistical Programming Final Project

Download the four datasets (stations.csv, status.csv, trips.csv, weather.csv) from the
Kaggle website https://www.kaggle.com/datasets/benhamner/sf-bay-area-bike-share.

## Please do the following using the Python programming language.

```
a. From trips.csv data, which records each and individual trips, construct an
aggregated data that includes daily rides for subscriber and daily rides for
customers for each day and each station id. For other numerical variables such
as duration, please compute their daily averages for each day and station id.
Please name this data as “dailyrides”.

b. Convert the status.csv to daily data by creating new variables
“avg_no_of_bikes_available” (daily averages of # bikes_available for each
station_ id) and “avg_no_of_docks_available” (daily averages of #
docks_available for each station_ id). Please name this data as “dailystatus”

c. Merge “dailyrides” with “dailystatus” and with the other datasets and create a
consolidated single dataset.

d. Create new variables “weekday”, “month”. From the variable
“installation_date”, please create a variable “timesinceinstall” which is the time
difference (in days) from the time of installation to current date.

e. Using the longitude and latitude, please plot the location of the stations on the
map.

f. Please plot the total number of rides (in log(x+1) scale) for different visibility
levels for both subscribers and customers. Interpret the plot.

g. Please plot the total number of rides (in log(x+1) scale) for different weather
events for both subscribers and customers. Interpret the plot.

h. Plot the daily rides (as a time series plot) for both subscribers and customers.
Interpret the plot.
```

## Please do the following using R programming language

```
a. From trips.csv data, for the city San Francisco, please draw a network diagram to
show the busiest bike riding routes on the map. For example, please see the
below picture. Can you identify the top 2 busiest routes?

b. Please repeat step (a) for the remaining cities.
```
