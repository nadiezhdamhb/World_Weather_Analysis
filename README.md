# **World Weather Analysis**

## Overview of Project

The purpose of this challenge was to improve and upgrade the PlanMyTrip app to contain weather descriptions along with with the already existing weather data. Customers will be able to use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. Lastly, we created both a travel itinerary and travel map as well as a marker layer map. The deliverables for this project are the following:
*	Retrieve Weather Data
*	Create a Customer Travel Destination Map
*	Create a Travel Itinerary Map

## Data Source Information
The data source used in this project was retrieved from Open Weather website, Google gmaps and the statistical analysis was performed with Citipy Library. 

## Software
Python, Pandas Library, Matplotlib, Jupyter Notebook, APIs and JSON.

## Results 

### Retrieve Weather Data 

The Weather Data was retrieved based on a set of 2,000 random latitudes and longitudes. Using the Open Weather map and retrieving the information with API, the cities weather data was collected with the current weather description and saved in a new DataFrame. 

![image](https://github.com/nadiezhdamhb/World_Weather_Analysis/blob/main/Weather_Database/image1.png)


### Vacation Search
The first program uses all of the data collected from openweathermap API to create a map of cities that shows the most popular accommodation, the city and country, and the current weather and temperature. The files, data and image can be found in the vacation_search folder.
 
 
 ![image](https://github.com/nadiezhdamhb/World_Weather_Analysis/blob/main/Vacation_Search/image1.png)

 
 
### Create a Customer Travel Destination Map 

Using customer weather preferences, potential travel destinations were identified along with nearby hotels. The destinations are identified with a marker layer map with pop-up markers. 


### Create a Travel Itinerary Map

Using Google Directions API a travel route was created to display positional coordinate between four cities chosen by the customer. 

![image](https://github.com/nadiezhdamhb/World_Weather_Analysis/blob/main/Vacation_Itinerary/itinerary_image1.png)


A marker layer map with pop-up was added to provide customized information to the user describing the name of the city, country, hotel and current weather description. 



