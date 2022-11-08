# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of the project is to investigate the relationship of various points of interests in an area with the amount of city bikes in nearby stations. Various APIs will be used to obtain data of city bikes stations as well as nearby points of interests.

## Process
### Step 1 : Acquire city bike stations details
The city bikes API will be used to select one location and obtain the stations details of tthe nearby stations associated with the location. 
### Step 2: Acquire information on POI near each station
The Yelp and Foursquares API will be used to obtain the information of restaurants near each of the stations. 
### Step 3: Process the data and set up a regression model
Set up visualization models and regression models depicting the relation of interest and attempt to find correlation between variables. 

## Results
There is no observable relationship between the number of bikes in a station and the rating and review number of nearby restaurants. There might be a relationship between the number of bikes in a station and the number of restaurants near that station (1km radius), but it is impossible to because of Yelp API's limit of 20 items per request. 

## Challenges 
The main challene faced in this project is the limitation of API requests. It is very difficult to check the number of nearby restaurant because the Yelp API only allows 20 items per requests and the Foursqares API even less. Another issue is difficulty in finding relevant foursqure venue filter applicable to the foursquare API. Most of the resorces seems to be only applicable to the version 2 and not version 3. 

## Future Goals
It will be possible to look into other locations of interest that may be more relevant to the number of bikes available to each station. One such category would be points of interests related to transportation since bikes also belong to that category. 

It would also be helpful to be able to spend more time cleaning the data to make sure it does not have unreasonable values, null values or duplicate data inside. 
