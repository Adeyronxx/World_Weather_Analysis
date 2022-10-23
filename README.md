# World_Weather_Analysis

# Project Overview

 This project is for a top travel technology company called PLANMYTRIP which specializes in internet-related services in the hotel and lodging industry.
 The goals for this analysis included:
 
 1. Retrieving Weather Data from 2000 Cities.
 2. Creating a Customer Travel Destinations Map.
 3. Creating a Travel Itinerary Map.

 

# Resources
  Data Source: citipy, jupyter-gmaps, OpenWeatherMap API, Google Maps and Places API, Google Maps Directions API

# Results

# Retrieving Weather Data

To achieve this, first we needed to generate the coordinates for 2000 cities, then we used the openweather API to get the current weather data for each of those cities. Next we extracted the data for the coordinates, weather description, temperature, humidity, cloudiness, windspeed and the country for each city and put this in a dataframe. We saved this into a csv file

<img width="913" alt="cities by weather data" src="https://user-images.githubusercontent.com/109445468/197369167-d0858452-cdea-4069-a80c-d1f72aa40b6a.png">

# Customer Travel Destination Map

Using our file from the weather data and using inputs based on preferrable temperatures we created a new dataframe of cities we would love to visit. we then added a new column to hold the names of the hotels within 5000 m radius. This is shown in the image below

<img width="909" alt="generating hotel info" src="https://user-images.githubusercontent.com/109445468/197369252-180ad8ba-b85e-47d8-88d2-2eda15b6dba1.png">

We then added a map to show each location with an info box containing vital information such as; the name of the hotel, the city, the country and current weather description.

<img width="1027" alt="info box" src="https://user-images.githubusercontent.com/109445468/197369302-b1f5cdb9-8a59-4340-b411-f74ced84f45b.png">


# Travel Itenary Map

Here we selected 4 cities based on our preferable temperature which can be reached by driving, bicycling or walking. The trip starts and ends at the same city but with 3 other stops. We also have our selected hotels in each of those cities with the current weather desription of each city.

This is shown in the images below;
<img width="1022" alt="Screen Shot 2022-10-22 at 8 05 31 PM" src="https://user-images.githubusercontent.com/109445468/197369422-8ed9351b-330b-4e28-9ad5-ddbf2c200319.png">
<img width="1022" alt="travel itinery map" src="https://user-images.githubusercontent.com/109445468/197369433-c234210b-f143-43d5-96fb-d9fbc4cc9821.png">

<img width="909" alt="generating hotel info" src="https://user-images.githubusercontent.com/109445468/197369252-180ad8ba-b85e-47d8-88d2-2eda15b6dba1.png">
<img width="1022" alt="Screen Shot 2022-10-22 at 8 05 49 PM" src="https://user-images.githubusercontent.com/109445468/197369440-1ca919ab-0f0f-41d7-afd6-c1b627a69b07.png">
