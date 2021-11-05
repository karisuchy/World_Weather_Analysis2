# World_Weather_Analysis

## Overview
In this project, we are using Application Programming Interfaces (APIs) to visualize weather data and help select vacation destinations. 

This was accomplished by collecting and analyzing weather data from over 500 cities across the globe. Linear regression calculations were then performed to determine the relationship, if any, between latitude and a variety of weather parameters such as temperature, windspeed, and humidity.

This resource can now be used to find ideal destinations anywhere in the world based on real-time weather criteria. 

## Resources
- Data Sources: OpenWeatherMap API, Googlemaps API
- Software: Python 3.7, Jupyter 6.3.0, Panda 1.2.4, MatplotLib 3.3.4, CityPy 0.0.5

## Results

### The Impact of Latitude on Weather Conditions
There is a strong relationship between latitude and temperature; the impact of temperature on windspeed, humidity, and cloudiness is slight, if any. The charts below demonstrate the impact of latitude on temperature and degree of cloudiness in the northern and southern hemispheres. 

#### Impact of Latitude on Temperature

![Lin_Reg_North_Hem_Max_Temp](https://user-images.githubusercontent.com/90162669/139594169-51ed3eb0-5e53-4d19-a57d-c60862d1d591.png)

![Lin_Reg_South_Hem_Max_Temp](https://user-images.githubusercontent.com/90162669/139594192-b141de9b-2adb-47ab-8b18-aa7b2c28daea.png)

#### Impact of Latitude on Wind Speed

![Lin_Reg_North_Hem_Clouds](https://user-images.githubusercontent.com/90162669/139594196-b0ccf26c-980d-4f7f-b5df-beef160fcf36.png)

![Lin_Reg_South_Hem_Cloud](https://user-images.githubusercontent.com/90162669/139594202-8ee87c30-e752-4efe-baac-c841bed3e9c8.png)

### Vacation Destinations
After users input their preferred maximum and minimum temperatures, the program returns a worldwide map displaying cities that meet the criteria. Users can than choose one or more destinations. The program can also display recommended routes between several cities and provide recommended hotels. The graphs below display the world wide map of available cities and selected travel itinerary based on one users choices.  

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/90162669/139594360-ae21dc6d-6b7f-4635-a01f-7ae757811f8d.png)

![WeatherPy_travel_map](https://user-images.githubusercontent.com/90162669/140588434-4820c2b5-c776-48fe-ab1f-56bf1a05dfdc.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/90162669/140588440-84fd85df-8850-4eca-a4ab-3611fec51cbc.png)

## Summary
This program offers a vast number of vacation choices and is still user-friendly. With additional programming, it could be expanded to compare weather patterns during different times of the year to further assist travelers with their vacation planning. 

All information is available for review on Git Hub. 


