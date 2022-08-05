# Ride Sharing

## Overview of the Analysis
For this module, I analyzed the ride sharing data of a Uber-similar app. I had two csv files to use as well: ride_data, which has the ride data with location the ride occured at, the date, and the fare collected for every ride, and city_data, which describes type of city and number of drivers per city. The goal of this analysis is to compare the fares of rural, suburban, and urban cities, to determine the average fare of each respective location, and to compare the total fare collection between the three types over the course of some months.
### Resources
- Jupyter Notebook
- Pandas 
- Matplotlib 

## Results
In order to complete this analysis, I had to merge all of the DataFrames together, I then used this to create a summary DataFrame that would display a summary of the ride data over the rural, suburban, and urban areas, leading to the following results: 

For every person riding in the rural cities, there are 5 riding in the suburban cities and there are 13 in the urban cities. (125 vs 625 vs 1625 rides)

The average fare for the urban cities is about $6 and $10 cheaper per ride than their suburban and rural cities respectively, as well as 2.5 times cheaper and 3.5 times cheaper than suburban and rural cities respectively. ($24.53 vs $30.97 vs $34.62 and $16.57 vs $39.50 vs $55.49)

The total fares in urban cities is about nine times that of the fare in rural cities and twice that of suburban cities. ($39,854.38 vs $19,356.33 vs $4,327.93)

![image](https://github.com/CharlesBootCamp/Ride_Sharing/blob/main/Ride%20Sharing/Resources/Total%20Rides.png)

Following is the daily fare collection chart of the cities with a timetable to show when they were completed:

![image](https://github.com/CharlesBootCamp/Ride_Sharing/blob/main/Ride%20Sharing/Resources/Daily%20fare.png)

Lastly, a line graph was created to display how the weekly fare of each type of city did over the course of January through April. The graph displays that the urban cities has the highest weekly fare collection, followed by the suburban cities, and then the rural cities. This graph helps provide data that more closely-knit communities provide more opportunity for ride sharing.
![image](https://github.com/CharlesBootCamp/Ride_Sharing/blob/main/Ride%20Sharing/analysis/PyBer_fare_summary.png)

From the graph, it can be seen that the maximum total weekly fares in urban cities is close to $2,500 at the end of February, while the maximum total weekly fares in suburban cities is about $1,500 at the end of February, and the maximum total weekly fares in rural cities is $500 at the beginning of April.

Following is the weekly fare collection chart of the cities:


![image](https://github.com/CharlesBootCamp/Ride_Sharing/blob/main/Ride%20Sharing/Resources/Weekly%20fare.png)

## Summary
In the end, while urban cities provide the most amount of money, the rural ones are the most profitable, leading to the idea that rural methods should be adopted elsewhere to potentially boost business.

One potential solution to this problem is to reduce number of drivers in urban cities. While there are 2,405 drivers registered in the database, they collectively made only 1,625 rides, this means that not even every driver got a single ride over the period of time, making the whole system inefficient.

Another potential solution is to make quantify a number of distance one can go per minute, making it so it can be seen who does the best with the time they have. To help combat this, urban cities can increase the price of fare, although this may not be taken well by customers.
