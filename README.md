# API- WeatherPy

# Background

Data's true power is its ability to definitively answer questions. So in this Python Analysis is done by  Python requests, APIs, and JSON traversals 
to answer a fundamental question: "What is the weather like as we approach the equator?"
Now, we know what : “That’s obvious. It gets hotter.” But, if pressed for more information, to prove that!

This Analysis is broken down into two deliverables, WeatherPy and VacationPy

# Part 1: WeatherPy


In this deliverable, a Python script is created to visualize the weather of over 500 cities of varying distances from the equator. 
Fot this ,the citipy Python library Links to an external site., the OpenWeatherMap API Links to an external site., 
and  e a representative model of weather across cities have created to solve this.
 Python coding is used to develop a solution to address the required functionalities.

First generated random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

# Findings

The findings of these analysis showed that there is a higher temperature for cities that found near to the equator (Latitude 0), 
however, when we go farther from the equator towards the north the temperature decreases highly.

In this  data, plots, and the regression line shows there is no significant results  between humidity and cloudiness of cities nearer or farther to the equator (latitude 0) . The correlation between humidity and latitude for both northern and southern hemisphere cities is very week, a negative correlation, and the result for cloudiness and latitude also very week and negative.
Therefore, We can infer that humidity can be fairly distributed in both northern and southern hemisphere cities regardless of their distance from the equator

# Table of Contents:

Part I - WeatherPy

# Scatter Plotting

# Latitude vs. Temperature Plot
# Humidity (%) vs. Latitude
# Cloudiness (%) vs. Latitude
# Wind Speed (mph) vs. Latitude
# linear regression & Scatter Plotting

# Northern Hemisphere - Temperature (F) vs. Latitude
# Southern Hemisphere - Temperature (F) vs. Latitude
# Northern Hemisphere - Humidity (%) vs. Latitude
# Southern Hemisphere - Humidity (%) vs. Latitude
# Northern Hemisphere - Cloudiness (%) vs. Latitude
# Southern Hemisphere - Cloudiness (%) vs. Latitude
# Northern Hemisphere - Wind Speed (mph) vs. Latitude
# Southern Hemisphere - Wind Speed (mph) vs. Latitude


For The bove analysis first converted city data file to a pandas dataframe 

<img width="693" alt="image" src="https://user-images.githubusercontent.com/116701851/214665571-101ee280-fdc2-4dc1-bf89-8c8e1b189962.png">


. Scatter Plotting

<img width="778" alt="image" src="https://user-images.githubusercontent.com/116701851/214665789-4ecc5d0b-3140-4d1b-adb0-faf78f432abb.png">



<img width="691" alt="image" src="https://user-images.githubusercontent.com/116701851/214665939-77dccb3d-a49b-4f13-b1dd-0c86553474ca.png">


<img width="706" alt="image" src="https://user-images.githubusercontent.com/116701851/214666139-f33ca6d2-7543-4234-af7a-3ef5b78df923.png">


<img width="763" alt="image" src="https://user-images.githubusercontent.com/116701851/214666282-ce1cacbb-ce1f-4a58-90c9-390dd71020f9.png">











