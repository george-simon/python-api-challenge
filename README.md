# python-api-challenge

## Objective
### Part I - WeatherPy
I was tasked to creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

### Part II - VacationPy
I was then tasked to use jupyter-gmaps and the Google Places API to create a heat map that displays the humidity for every city from the part I of the homework. Locate ideal weather conditions. Then utilize the Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

## Final Analysis Observations
### Northern Hemisphere vs Southern Hemisphere - Max Temp vs. Latitude Linear Regression 
#### Observation 1
After looking over the below linear regression models and r-values of the northern and southern hemispheres as compared to the max temp. The R-values point and the graphing shows that as the latitude values approach the equator the temperature (F) rises.

![N Temp](/output_data/LReg_MaxTemp_NHemi.png)
![S Temp](/output_data/LReg_MaxTemp_SHemi.png)

### Northern Hemisphere vs Southern Hemisphere -  Humidity (%) vs. Latitude Linear Regression
#### Observation 2
Looking at the relationship between humidity and latitude, the r-values and graphing show there is no relationship between the two. Both in the southern and northern hemisphere. It would seem that as one approaches the equator it doesn't necessarily mean it will be an increase in humidity %.
![N Humidity](/output_data/LReg_Humidity_NHemi.png)
![S Humidity](/output_data/LReg_Humidity_SHemi.png)

### Northern Hemisphere vs Southern Hemisphere -  Cloudiness (%) vs. Latitude Linear Regression
#### Observation 3
Looking at the relationship between cloudiness and latitude, the r-values and graphing show there is little relationship between the two. Both in the southern and northern hemisphere. It would seem that as one approaches the equator the cloud coverage doesn't increase and is quite random.
![N Cloudiness](/output_data/LReg_Cloudiness_NHemi.png)
![S Cloudiness](/output_data/LReg_Cloudiness_SHemi.png)
