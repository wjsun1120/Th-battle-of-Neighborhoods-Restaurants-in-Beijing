# Th-battle-of-Neighborhoods-Restaurants-in-Beijing

1. Introduction

The project provides reliable cuisine information to visitors to Beijing from other countries. I would list different food venues at each division in Beijing and visualize them to help visitors make better choices.

2. Background

I have arranged several trips to Bejing for my friends from other countries, and some common problems they faced before planning were to decide what to have and where to find authentic chinese restaurants. Besides, the XXIV Winter Olympic Games in Bejing would attract tens of thousands of tourists around the world, and some of them would face the same problems as my friends did. I think it would be helpful to create such information source they could go for selecting restaurants, which would save them plenty of time collecting information on their own.

3. Data Requirements

  1. All administrative dividions of Beijing City which were retrieved from Wikipedia:  https://en.wikipedia.org/wiki/List_of_administrative_divisions_of_Beijing

     I scrapped the table 'Administrative Divisions' on Wikipedia and found their coordinates through geocoder class of Geopy client.

  2. Restaurants in each division of Beijing which were retrieved from Foursquare APIs.

     I got all the venues in each division with Foursquare APIs and filtered out restaurants only. 





