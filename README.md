# What's the Weather Like?
--------------------------------------


Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: "Duh. It gets hotter..."

But, if pressed, how would you prove it?

![Equatorial Cities](/images/equatorsign.png)

## Weather
----------------------------------------

In this example, a Python script is created to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

The objective is to build a series of scatter plots to showcase the following relationships:


Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

![Equatorial Cities Temperatures](/images/TemperatureEquatorialCities.png)

The final notebook:


Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.
Performs a weather check on each of the cities using a series of successive API calls.
Includes a print log of each city as it's being processed with the city number and city name.
Save both a CSV of all data retrieved and png images for each scatter plot.



![Equatorial Cities Cloudiness](/images/CloudinessEquatorialCities.png)

