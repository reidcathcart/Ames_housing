# SF_Bike_Share

This is an exercise to help me understand more about data cleansing and visualization in Python.

## About the Data

The [Bay Area Bike Share](http://www.bayareabikeshare.com/) enables quick, easy, and affordable bike trips around the San Francisco Bay Area. This data used is a transformed version of data they made available with their regular open data releases. The data contained the following files:

**station.csv** - Contains data that represents a station where users can pickup or return bikes.

**status.csv** - data about the number of bikes and docks available for given station and minute.

**trips.csv** - Data about individual bike trips

**weather.csv** - Data about the weather on a specific day for certain zip codes

Data and a more detailed description can be found [here](https://www.kaggle.com/benhamner/sf-bay-area-bike-share/data):

## Other info about the data

**Time period** - 2013 - 2015

**Locations** - Mountain View, Palo Alto, San Jose, San Francisco, Redwood City

## Interesting Findings

- San Francisco is by far the most common city in which to rent the bikes
- Data suggests ad hoc users use the service more for leisure trips and compared to subscribers, who use the system for primarily for commuting
- When it is raining there is only a slight decrease in trips for subscribers; relatively bigger difference for customers
- The relative temperature does not cause much difference in ridership
- While subscribers rarely incurred extra costs for their trips, when they did the total per trip averaged up to 50% more than ad hoc customers
- Trips on the weekend were more likely to incur an extra cost

## Interesting Plots
![Trips by hour](images/trips_by_hour.png)

![Station bias](images/station_bias.png)

![Most common routes](images/most_common_routes.png)

## Libraries used:

- pandas
- numpy
- datetime
- calendar
- geopy
- matplotlib
- seaborn
- plotly with mapbox
