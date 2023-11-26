# python-api-challenge

Data's true power is its ability to definitively answer questions. "What is the weather like as we approach the equator?"
Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

Part 1:Weather.py
In this deliverable, I have  created a Python script to visualize the weather of over 500 cities of varying distances from the equator
I have created  a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

The linear regression line, the model's formula, and the r values are generated.

part 2:Vacation.py
In this deliverable, I have used Geoapify API and the geoViews Python library  to create map visualizations.

The following steps are completed.

Create a map that displays a point for every city in the city_data_df DataFrame

The size of the point should be the humidity in each city.

Narrow down the city_data_df DataFrame to find your ideal weather condition.

For example:

A max temperature lower than 27 degrees but higher than 21

Wind speed less than 5 m/s

Zero cloudiness

Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
Add the hotel name and the country as additional information in the hover message for each city on the map .
Hotel map.

