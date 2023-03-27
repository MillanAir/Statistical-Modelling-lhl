# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Using the CityBikes API, Foursquare API, and Yelp API, we will be exploring the relationship between the number of bikes in a particular location and the characteristics of the POIs in that location.

## Process

### Getting the Data

1. We first explored the structure of the API, queried the API, and understood the data returned.
2. We chose a city covered by the CityBikes API and retrieved all available bike stations in that city along with available bikes, latitude, and longitude.
3. Using the Foursquare and Yelp API, we retrieved information for the following in that location:
    - Restaurants or bars
    - Various POIs (points of interest) of your choice
4. After cleaning the data, we created a DataFrame for the Yelp results and Foursquare results.
5. Saved the data in csv format and sqlite3 database so as to ensure that we can access the data in the future and reducing the number of api calls.


### Joing the Data and Building a Model
1. We joined the data from Part 1 with the data from Part 2 to create a new dataframe.
2. We used data visualization to explore the data.
3. We built a regression model using Python’s `statsmodels` module that demonstrates a relationship between the number of bikes in a particular location and the characteristics of the POIs in that location.

## Results
We found that there is a loosely positive relationship between the number of bikes in a particular location and the characteristics of the POIs in that location.

## Challenges 

1. It was challenging to use the apis and to get the proper data from the apis.
2. It was challenging to join the data as the data was in different formats and had different column names.

## Future Goals

1. We would like to explore the relationship between the number of bikes in a particular location and the characteristics of the POIs in that location in more detail. For eg. 
   - What kind of POIs are more likely to have more bikes?
   - What POIs have less bikes?
   - POI's with more bikes are more likely to have more reviews?
