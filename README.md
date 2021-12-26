# world_weather_analysis
Bootcamp Module 6

## Overview

The purpose of this assignment is to create a tools which helps to plan vacation destinations and itinteraries based on customer weather preference. 

The assignment uses data from OpenWeather.org and Google.com to identify locations which currently are experiencing the weather desired by the customer, and display them on a map. Using Google Maps data, the customer is shown specific cities and hotels which they can stay at, as well as a proposed itinerary for a trip.

The data is collected by randomly generating pairs of latitude and longitude which canvas the globe for weather data and sample cities to visit. CitiPy is used to identify the nearest city to these pairs. Weather data is collected for each city and then filtered based on customer-input parameters. This short list of potential destinations is used with Google Maps to create the propsed itinerary.