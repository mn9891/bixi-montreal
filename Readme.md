![bixi](https://upload.wikimedia.org/wikipedia/commons/5/53/Bixi_logo.svg)
# BIXI Montreal - Data Preprocessing, Visualization and Analysis

This project includes:
- a first notebook detailing a series of exploratory data analysis of the data describing the use of  BIXI Montreal bike sharing system.
- a second notebook where venues around end stations have been used as features to cluster stations using k-means classifier. 

The goals of this project includes:
* Visualizing the bike sharing data 
* Finding some interesting observations and insights behind the data/ bike use trends to provide recommendations.

### Data sources
- The bike trips data could be found directly in the [the open data](https://montreal.bixi.com/en/open-data) section of BIXI Montreal official website. It contains data from April 2014 to this day.
- Weather information for the same period has been collected from [weather.gc.ca](http://climate.weather.gc.ca/) using this [previous project](https://github.com/mn9891/weather-scrap-selenium/blob/master/Weather_data_mtl_from_weather_gc_ca.ipynb).
- Venues around the end stations are collected using the [Foursquare API](https://developer.foursquare.com/)
