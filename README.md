# api-challenge

# In this challenge, I worked on two sets of code being: WeatherPy and VacationPy.

# In WeatherPy: The starter code came with a script to get a list of random cities with
# given coordinates, so an API key was used to retrieve information from OpenWeatherMap API.

# After the cities were retrieved, a series of scatterplots were created to find potential relationships
# between Latitude vs. Temperature, Latitude vs. Humidity, Latitude vs. Cloudiness, Latitude vs. Wind Speed.

# Next, another series of scatterplots was created to showcase the above mentioned relationships for each hemisphere
# which were northern and southern hemispheres. So the following plots were created with linear regression lines to 
# see if there was any potential effect latitude has on any of the following conditions:
# Northern Hemisphere: Temperature vs. Latitude
# Southern Hemisphere: Temperature vs. Latitude
# Northern Hemisphere: Humidity vs. Latitude
# Southern Hemisphere: Humidity vs. Latitude
# Northern Hemisphere: Cloudiness vs. Latitude
# Southern Hemisphere: Cloudiness vs. Latitude
# Northern Hemisphere: Wind Speed vs. Latitude
# Southern Hemisphere: Wind Speed vs. Latitude

# On VacationPy:

# A dataframe was created from the cities that were pulled from WeatherPy. The starter code helped to pull these cities
# into the dataframe, a map was created with those cities with their information able to be displayed when hovering 
# over the city, to include coordinates, humidity, and name of the city.

# From those cities, a script was applied to retrieve cities with weather conditions ideal to personal liking. Once those
# cities were found with the perfect weather conditions, Geoapify API was used to find hotels in the proximity of 10,000 meters
# of the set coordinates of the city. 

# Lastly, once the names of the hotels were retrieved, the same cities with the ideal weather conditions were mapped again 
# but this time with the coordinates, humidity, city name, country located in, and the name of the hotels found.
