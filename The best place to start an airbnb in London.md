# The Best Place to Open an Airbnb in London

This report consists of four parts: description of problem, data, methodology, visualization and results. We will discuss about the problem and data in this week's submission. 

## Description of the Problem

A real estate investor would like to buy a property in London, UK and turn it into an airbnb. He would like to find out which neighbourhood is the best place to have an airbnb. 

We understand that airbnb is mostly for short term visitors, mostly tourists. What's most important for them is the convenience of the location. The following factors are in the mind of tourists when they are looking for the airbnb, distance to attractions and restaurants, and price. Price per night is also a big concern for the investor. 

We will find out the data for the above factors and cluster the neighbourhoods into different culsters. 

Data
We will be collecting data from following sources:

Collect data of London that contains borough, neighborhoods by scraping Wikipedia.
Data source: Wikipedia
We are going to get longtitude and latitude for each neighborhoods by using geocoder.
We are going to go through each of the neighborhoods to get number of attractions, number of restaurants in a 10km radius. 
Data source: foursquare API
Get airbnb listing data of London including ID, address, Neighborhood, price per night, number of guests accomodates. 
Data source: http://insideairbnb.com
Calculate price per guest per night, then group data by neighborhood and get average price per guest per night in each neighborhood.  

We will then put together all the data into one dataset including neighborhood, number of attractions, number of restaurants, and average price per guest per night for each neighborhood. 