# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Using the CityBikes API, Foursquare API, and Yelp API, we will be exploring the relationship between the number of bikes in a particular location and the ratings of the POIs in that location.

## Process

### Getting the Data

The API structure was examined, and the data it returned was analyzed. Then, we picked a city from the CityBikes API and collected data on all bike stations, including their available bikes, latitude, and longitude. 
Foursquare and Yelp APIs was used to obtain information on restaurants or bars and various points of interest in that area. 
The data was then cleaned, and separate DataFrames were created for the Yelp and Foursquare results.
Finally, the data was saved in both csv format and an sqlite3 database to allow future access and minimize the number of API calls needed.


### Joing the Data and Building a Model

The data from Part 1 and Part 2 were merged to generate a new dataframe. 

Data visualization was utilized to investigate the data, and a regression model was constructed with Python's `statsmodels` module to show the connection between the quantity of bikes in a given location and the features of the points of interest (POIs) in that area.


## Results

There is moderate to strong positive relationship between the number of bikes and the ratings of the POIs in that location.

## Challenges 

1. It was challenging to use the apis and to get the proper data from the apis.
2. It was challenging to join the data as the data was in different formats and had different column names.

## Future Goals

We would like to explore the relationship between the number of bikes in a particular location and the characteristics of the POIs in that location in more detail. For eg. 

   - What kind of POIs are more likely to have more bikes?
   - What POIs have less bikes?
   - POI's with more bikes are more likely to have more reviews?
