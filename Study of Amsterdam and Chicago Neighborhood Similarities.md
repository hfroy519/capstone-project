## Introduction

A group of Americans from Chicago are moving to Amsterdam for work. None of them know anything about neighborhoods
in Amsterdam and are uncertain about which neighborhoods they may prefer. They do know which neighborhoods they prefer
in Chicago. They'd like to get a recommendation for which neighborhood in Amsterdam is most similar to each neighborhood in Chicago. 

## Data

In order to help the group make more informed decisions, I will use the four square data for each of the cities to retrieve venue
type data by neighborhood. These neighborhoods will be defined by geojson files for each city that were found online. 

## Methodology

I will use the neighborhood and venue data to calculate a value for each neighborhood pair based on similarity of venue type. 
I will then return the Amsterdam neighborhood that is most similar to each Chicago neighborhood.

## Results

The results of my project are two data frames containing each neighborhood from Chicago and Amsterdam along with their closest 
neighborhood match from the opposite city.

## Discussion

The Americans from Chicago who are moving to Amsterdam are looking for a way to know which Amsterdam neighborhood is most similar to
the Chicago neighborhood that they currently live in. This project was able to deliver this result by looking at four square data to see
the most popular venues types in each neighborhood and then compare these values for each pair of neighborhoods. The result set from this 
project provides very useful data to the Americans who are moving to Amsterdam. 

## Conclusion

The result of this project is that anyone with knowledge of Chicago neighborhoods will be able to find the most similar neighborhood to 
a neighborhood they already know. 
