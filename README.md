### Project : What's the Weather Like?


Whether financial, political, or social - data's true power lies in its ability to answer questions definitively. We used Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"


![Equator](Images/equatorsign.png)

## WeatherPy

In this project, we created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, we utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

The objective was to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The final notebook has following:

* Selected 500 unique (non-repeat) cities based on latitude and longitude.
* Performed a weather check on each of the cities using a series of successive API calls.
* Included a print log of each city as it's being processed with the city number and city name.
* Saved both a CSV of all data retrieved and png images for each scatter plot.

Used the following to do this project:

* Jupyter notebook.
* Matplotlib plotting libraries.
* Pandas.
* Citipy.

## Highlights

* The city data is generated based on random coordinates; as such, the outputs were not an exact match to the provided starter notebook.

* Used this link to do the analysis [geographic coordinate system](http://desktop.arcgis.com/en/arcmap/10.3/guide-books/map-projections/about-geographic-coordinate-systems.htm).

* Next, we spend the requisite time necessary to study the OpenWeatherMap API. Based on our initial study,we were able to answer  basic questions about the API: Where do we request the API key? Which Weather API in particular will I need? What URL endpoints does it expect? What JSON structure does it respond with? Before we write a line of code, we were aiming to have a crystal clear understanding of our intended outcome.

* We used citipy: [citipy Python library](https://pypi.python.org/pypi/citipy). Before we tried to incorporate the library into our analysis, we started by creating simple test cases outside our main script to confirm that we are using it correctly. 


* In building our script, we paid attention to the cities we are using in our query pool. In fact,we Consider the full range of latitudes. It was a project where I learned a lot about how to work with APIs.



