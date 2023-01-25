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
Therefore, We can infer that humidity can be fairly distributed in both northern and southern hemisphere cities regardless of their distance from the equator and the relationship between wind speed (mph), and latitude showed that the lower wind speed when the cities closer to the equator (latitude 0), and somehow the wind speed increase for the cities farther from the equater. The regression analysis also showed that there is a very week, positive correlation between Wind Speed (mph (%) and Latitude in the Northern Hemisphere cities.



# Table of Contents:


# Part I - WeatherPy


1. Scatter Plotting

 Latitude vs. Temperature Plot
 
 Humidity (%) vs. Latitude
 
Cloudiness (%) vs. Latitude

 Wind Speed (mph) vs. Latitude
 
 linear regression & Scatter Plotting
 
 
 
2. Linear Regression


 Northern Hemisphere - Temperature (F) vs. Latitude
 
 Southern Hemisphere - Temperature (F) vs. Latitude
 
 Northern Hemisphere - Humidity (%) vs. Latitude
 
 Southern Hemisphere - Humidity (%) vs. Latitude
 
 Northern Hemisphere - Cloudiness (%) vs. Latitude
 
 Southern Hemisphere - Cloudiness (%) vs. Latitude
 
 Northern Hemisphere - Wind Speed (mph) vs. Latitude
 
 Southern Hemisphere - Wind Speed (mph) vs. Latitude


For The bove analysis first converted city data file to a pandas dataframe 

<img width="693" alt="image" src="https://user-images.githubusercontent.com/116701851/214665571-101ee280-fdc2-4dc1-bf89-8c8e1b189962.png">


1.  Scatter Plotting

<img width="778" alt="image" src="https://user-images.githubusercontent.com/116701851/214665789-4ecc5d0b-3140-4d1b-adb0-faf78f432abb.png">



<img width="691" alt="image" src="https://user-images.githubusercontent.com/116701851/214665939-77dccb3d-a49b-4f13-b1dd-0c86553474ca.png">


<img width="706" alt="image" src="https://user-images.githubusercontent.com/116701851/214666139-f33ca6d2-7543-4234-af7a-3ef5b78df923.png">


<img width="763" alt="image" src="https://user-images.githubusercontent.com/116701851/214666282-ce1cacbb-ce1f-4a58-90c9-390dd71020f9.png">


2. Linear Regression


 Northern Hemisphere - Temperature (F) vs. Latitude
 
 
 <img width="711" alt="image" src="https://user-images.githubusercontent.com/116701851/214670236-2f2fe93f-3549-4b4d-9054-f267a0b13944.png"> 
 


Southern Hemisphere - Temperature (F) vs. Latitude


<img width="644" alt="image" src="https://user-images.githubusercontent.com/116701851/214670465-84faa447-a4b4-48ca-bc17-c18edfa9862d.png">




Northern Hemisphere - Humidity (%) vs. Latitude


<img width="687" alt="image" src="https://user-images.githubusercontent.com/116701851/214670717-8d6827fb-3f39-4e80-a2c5-f9a07833f3c4.png">



Southern Hemisphere - Humidity (%) vs. Latitude


<img width="739" alt="image" src="https://user-images.githubusercontent.com/116701851/214672345-ee49cfaa-9441-4042-85a8-1aa308bb28aa.png">


Northern Hemisphere - Cloudiness (%) vs. Latitude

<img width="720" alt="image" src="https://user-images.githubusercontent.com/116701851/214672859-e1418d1d-7dff-4728-8a49-5b432c8c2a7b.png">


Southern Hemisphere - Cloudiness (%) vs. Latitude


<img width="652" alt="image" src="https://user-images.githubusercontent.com/116701851/214672987-033b1770-f1b9-4cd9-b750-58d522e7bcd8.png">




 Northern Hemisphere - Wind Speed (mph) vs. Latitude
 
 <img width="668" alt="image" src="https://user-images.githubusercontent.com/116701851/214673454-7c04b266-622b-4ee2-a602-0041f404a961.png">
 
 
 
 Southern Hemisphere - Wind Speed (mph) vs. Latitude
 
 <img width="699" alt="image" src="https://user-images.githubusercontent.com/116701851/214673696-b2027adf-7e93-4ee9-aa33-b26338bd3bf9.png"> 
 
 
 
# Part 2: VacationPy

Created map that displays Humidity for every city in the  DataFrame.


<img width="748" alt="image" src="https://user-images.githubusercontent.com/116701851/214675714-f5eae02f-3018-4f57-889d-772f90c84a4a.png">

A new dataFrame was created by narrow down the weather data to find the ideal weather condition



A map is created for hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.



<img width="990" alt="image" src="https://user-images.githubusercontent.com/116701851/214676301-9b3b2feb-f835-4293-a2c5-f481842b1e3c.png">





