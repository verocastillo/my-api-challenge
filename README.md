# my-api-challenge
Repository for my fifth homework using Python, Pandas and working with APIs, where I use the data from two different APIs in order to determine the tendencies in a place's climate as they get nearer or further from the equator.

<img width="1440" alt="Screen Shot 2021-04-29 at 4 51 41 PM" src="https://user-images.githubusercontent.com/77795761/116633941-609ece80-a920-11eb-827c-9fe83afe18a0.png">

**Which APIs will I be using?**

I am working with two APIs:
- OpenWeatherMap API: they collect and process weather data from different sources such as global and local weather models, satellites, radars and a vast network of weather stations in order to obtain the current weather in a certain place.
- Google Maps APIs: The Places API is one of the APIs that Google Maps offers, and it is a service that returns information about places using HTTP requests. Places are defined within this API as establishments, geographic locations, or prominent points of interest.

**What do my notebooks do?**
These homework consists of two challenges: WeatherPy and VacationPy. 

  **WeatherPy**
  In *WeatherPy* I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. I created a series of scatter plots to showcase the following relationships:
  - Temperature (F) vs. Latitude
  - Humidity (%) vs. Latitude
  - Cloudiness (%) vs. Latitude
  - Wind Speed (mph) vs. Latitude
  
  Then I ran a linear regression on each relationship, but I  separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
  - Northern Hemisphere - Temperature (F) vs. Latitude
  - Southern Hemisphere - Temperature (F) vs. Latitude
  - Northern Hemisphere - Humidity (%) vs. Latitude
  - Southern Hemisphere - Humidity (%) vs. Latitude
  - Northern Hemisphere - Cloudiness (%) vs. Latitude
  - Southern Hemisphere - Cloudiness (%) vs. Latitude
  - Northern Hemisphere - Wind Speed (mph) vs. Latitude
  - Southern Hemisphere - Wind Speed (mph) vs. Latitude
  
  My code also exports the CSV with the city data for further analysis and each of the plots was saved as a png file. Comments and insights are included within and after each section in the code.
