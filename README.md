# World_Weather_Analysis

# Purpose
One of our clients would like assistance answering a question about: How might we provide real-time suggestions for his customers’ ideal hotels (i.e. Hotels that are within a given range of latitude and longitude) that would provide them with a preferred right kind of weather.
We use python in Jupyter Notebook, google map’s API key, and OpenWeatherMap API key to access world’s cities location (via latitudes and longitude), and the world weather data. We will use this data for analysis and create tables and visualize weather data across cities worldwide to make conclusions and recommendations to the clients for their travel planning.

# Results
A set of 2000 random latitudes and longitudes was created, and we performed an API call with the  OpenWeatherMap to retrieve:
*	Latitude and longitude
*	Maximum temperature
*	Percent humidity
*	Percent cloudiness
*	Wind speed
*	Weather description (for example, clouds, fog, light rain, clear sky)

## Scatter plots

We created scatter plots to show the effects of latitude on different weather parameters such as temperature or humidity.

![](https://github.com/ntorenduwayo/World_Weather_Analysis/blob/main/weather_data/Fig1.png)

![](https://github.com/ntorenduwayo/World_Weather_Analysis/blob/main/weather_data/Fig2.png)

![](https://github.com/ntorenduwayo/World_Weather_Analysis/blob/main/weather_data/Fig3.png)

![](https://github.com/ntorenduwayo/World_Weather_Analysis/blob/main/weather_data/Fig4.png)

## Cites and hotels Heat maps

![](https://github.com/ntorenduwayo/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

![](https://github.com/ntorenduwayo/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

![](https://github.com/ntorenduwayo/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
