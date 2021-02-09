# python-api-challenge

This exercise is designed to practice the use of Python requests, APIs and JSON traversals. The question overarching question being answered is - What is the weather like as we approach the equator? The follow-up question being - what hotel can we stay at in locations with our ideal weather conditions?

Part 1 = WeatherPy

This exercise will use a Python script to randomly select 500+ cities across the world to highlight possible weather trends based on a city's location relative to the equator. To accomplish this, you'll be utilizing a [simple Python library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

We begin by creating a series of scatter plots to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Each graph is followed by a description of what the code is analyzing.

The second step is to study the relationships based on whether the city is located in the Northern or Southern hemisphere. The linear regression model will output an r-value that will help demonstrate whether or not there is a linear relationship between the predicted and actual values. 
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

Each pair of plots is followed by an explanation of what the linear regression is modeling and a description of any noticeable relationships.

Lastly, include a written description at the beginning of the exercise of at least 3 observable trends based on the data.

Part 2 = VacationPy

This exercise answers the second overarching question - Where can one stay when visiting locations with the ideal weather conditions? We answer this question using jupyter-gmaps and the Google Places API. 

First, create a heat map that displays the humidity from every city in Part 1.

Then select specific cities that meet desired criteria. For example, cities that meet the following requirements:
  * A max temperature lower than 75 degrees but higher than 65.
  * Wind speed less than 10 mph.
  * Zero cloudiness.

Finally, use Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
Plot the hotels on top of the humidity heatmap with each pin containing the following:
   * Hotel Name
   * City
   * Country

Save a screenshot of the final plot. 









