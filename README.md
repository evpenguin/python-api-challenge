# Challenge 6 - Python API's
WeatherPy.ipynb describes a number of randomly selected cities and weather data applicable to each of them. From this data we want to ascertain the relationship if any between weather patterns and latitude values.

Once that step is complete, VacationPy.ipynb identifies cities with favourable weather conditions and locates a hotel in the area.

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Installing](#installing)
- [Usage](#usage)
- [Contributing](#contributing)

## About
This analysis first generates 1500 random lat-long coordinates, and then identifies the nearest city to that point. This usually creates a list of about 600 unique cities. The code obtains weather data for each city from openweathermap.org and tags each city with 8 data points (latitude, longitude, maximum temperature, humidity, clouds, wind speed, country, date). A dataframe is then created for the user to view and exported to a csv. the analysis creates scatter plots with regression lines and draws some conclusions based on the data it has retrieved.

VacationPy.ipynb imports the results of WeatherPy.ipynb and outputs the table of information as before and then produces a world map showing the cities and how humid they are. Then cities with unfavourable conditions are dropped and the table is shown again with eligible cities only, before using Geoapify to identify the closest hotel to the original lat-long coordinate of each city. A new table is shown with the name of the hotel and finally a map with the hotels marked.

## Getting Started
To run this program download and run the files. Note that the user will need their own api keys.

## Installing
Download Weather.ipynb and VacationPy.ipynb. 

## Usage
Gives suggestions for cities to visit with nice weather and hotels to stay at in those cities.

## Contributing
Evangeline Allan
