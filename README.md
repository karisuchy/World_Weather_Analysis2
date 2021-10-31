# World_Weather_Analysis

## Overview
In this project, we are using Application Programming Interfaces (APIs) to visualize Weather Data and help select vacation destinations. 

This was accomplished by collecting and analyzing weather data from over 500 cities across the globe. Linear regression calculations were then performed to determine the relationship, if any, between latitude and a variety of weather parameters such as temperature, windspeed, and humidity.  

This data can now be used by others to find their ideal destination anywhere in the world based on real-time weather criteria. 

## Resources
- Data Sources: OpenWeatherMap API, Googlemaps API
- Software: Python 3.7, Jupyter 6.3.0, Panda 1.2.4, MatplotLib 3.3.4, CityPy 0.0.5

format: JavaScript Object Notation (JSON Traversals)

## Results

### The Impact of Latitude on Weather Conditions
There is a strong impact of latitude on temperature. The impact of temperature on windspeed, humidity, and cloudiness is slight, if any. The charts below demonstrate the impact of latitude on temperature and degree of cloudiness in the northern and southern hemispheres.    

#### Impact of Latitude on Temperature

![Lin_Reg_North_Hem_Max_Temp](https://user-images.githubusercontent.com/90162669/139594169-51ed3eb0-5e53-4d19-a57d-c60862d1d591.png)

![Lin_Reg_South_Hem_Max_Temp](https://user-images.githubusercontent.com/90162669/139594192-b141de9b-2adb-47ab-8b18-aa7b2c28daea.png)

#### Impact of Latitude on Wind Speed

![Lin_Reg_North_Hem_Clouds](https://user-images.githubusercontent.com/90162669/139594196-b0ccf26c-980d-4f7f-b5df-beef160fcf36.png)

![Lin_Reg_South_Hem_Cloud](https://user-images.githubusercontent.com/90162669/139594202-8ee87c30-e752-4efe-baac-c841bed3e9c8.png)

### Vacation Destinations
After selecting their maximum and minimum temperatures, the program returns a worldwide map displaying cities that meet their criteria. It can also display route from multiple cities that meet the criteria. 

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/90162669/139594360-ae21dc6d-6b7f-4635-a01f-7ae757811f8d.png)


ADD LAST MAP



## Summary
This program could be expanded to compare weather patterns during different times of the year to further assist travelers with their planning. 

All information is available for reivew on Git Hub. 


