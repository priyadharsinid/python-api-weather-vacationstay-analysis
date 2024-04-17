# python-api-weather-vacationstay-analysis

## Overview

Data's true power is its ability to definitively answer questions. "What is the weather like as we approach the equator?"
Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

## Part 1: Weather.py

In this deliverable, I have created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I have generated a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

Additionally, separate scatter plots have been created for the Northern and Southern Hemispheres to analyze the relationships between temperature, humidity, cloudiness, and wind speed with latitude. The script also calculates and displays the linear regression line, the model's formula, and the r-values.

## Part 2: Vacation.py

In this deliverable, I have utilized the Geoapify API and the geoViews Python library to create map visualizations. The following steps were completed:

- Created a map that displays a point for every city in the city_data_df DataFrame. The size of the point represents the humidity in each city.
- Narrowed down the city_data_df DataFrame to find ideal weather conditions, such as a maximum temperature lower than 27 degrees but higher than 21 and wind speed less than 5 m/s.
- Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
- Used the Geoapify API to find the first hotel located within 10,000 meters of the coordinates for each city. Added the hotel name and country as additional information in the hover message for each city on the map.
- Zero cloudiness

## Requirements


- Python
- Pandas
- Matplotlib
- GeoViews Python library
- Geoapify API
- NumPy

Feel free to customize the content further to better suit your project's specifics.
