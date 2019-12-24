# Best Location for Mexican Restaurant
Applied Data Science Capstone

## Introduction

While opening a restaurant can be a very lucrative business, a lot of factors cause many restaurants to close within the first year of opening. These factors could be location, competition, and quality of food.  

The goal of this project is to use the Foursquare API to determine the optimal location to open a Mexican Restaurant. For this problem specifically, location and competition will be determined by where the restaurant will be opened. If there are too many Mexican restaurants the profitability of the restaurant will be decreased. Another factor could be starting the restaurant in a location with higher income, this could increase the profitability.

Business Problem.  If the client wanted to open an Mexican Restaurant in Toronto, what areas are the best options to open the restaurant?

## Data

To answer the business problem, we will use the Toronto Censs data set and the toronto neiborhoods data obtain by wikipedia.The following factors have to be extracted from the data sources:

1)Population & Ethnic Distribution of Each Neighborhood (Toronto Census)
2)Income Distribution of Each Neighborhood (Toronto Census)
3)Number of Restaurants in Each Neighborhood (Foursquare API)
4)Number of Mexican Restaurants in Each Neighborhood (Foursquare API)

The Toronto Census data was extracted from https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/
The Toronto postal codes was scraped from https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

### Toronto census
![](https://github.com/IvanEdmundo/Coursera_Capstone/blob/master/Imagenes/TorontoCensus.png)


