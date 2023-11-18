Airbnb Booking Analysis

Abstract


Airbnb is an online marketplace that connects people who want to rent out their homes with people who are looking for accommodations in that locale. It currently covers more than 100,000 cities and 220 countries worldwide. For hosts, it's a way to earn money while protecting their property from potential damage. However, for guests, it's a risky venture that they should avoid.

For this project we are analyzing Airbnb’s New York City(NYC) data. NYC is not only the most famous city in the world but also top global destination for visitors drawn to its museums, entertainment, restaurants and commerce. According to the Office of New York State Comptroller, NYC hosted 66.6 million visitors in 2019.

Data analysis on thousands of listings provided through Airbnb is a crucial factor for the company. Our main objective is to find out the key metrics that influence the listing of properties on the platform. For this, we will explore and visualize the dataset from Airbnb in NYC using basic exploratory data analysis (EDA) techniques. We have found out the distribution of every Airbnb listing based on their location, including their price range, room type, listing name, and other related factors. We have analyzed this dataset from different angles and have come up with interesting insights. This can help in making strategic data-driven decisions by the marketing team, finance team and technical team of Airbnb.

Problem statement
 This project aims to analyze Airbnb data using Python language and it's libraries, to perform data cleaning and preparation, develop interactive visualizations, and create dynamic plots to gain insights into pricing variations, availability patterns, and location-based trends.

objective
The goal of the project - The purpose of the project is to gather information and analyze the detailed information of the different bookings in the neighborhood groups in order to provide insights about the bookings in a particular area as per your preference, type of rooms, and price accordingly.
We have tried discovering relationships among different columns and found meaningful insights to decipher business impacts.

Data Cleaning:

1.Dropping duplicates.

2.Cleaning individual columns.

3.Remove the Null values from the dataset

Data Analysis and Visualization:

*   What is the average price  according to the location?
*   Number of active hosts per location (Where most of the hosts focused to own property?)
*   Which properties are the busiest in terms of Number of Bookings ?
*   Find the total count of each room type
*   Room types and their relation with availability in different neighbourhood groups.
*   Which are the top 25 most used words in listing names?
*   Find top 10 hosts with most listings.
*   Find the top three hosts based on their turnover.
*   Find total no. of nights spend per location.
*   Total no. of nights spends per room types.
*   Which host has received the most number of reviews?
*   Density of property within a neighbourhood group with location.
*   Correlation of different numerical attributes.
  

Conclusion

Through this exploratory data analysis (EDA) and visualization, we gained several interesting insights into the Airbnb rental market. This Airbnb dataset  appeared to be a very rich dataset with a variety of columns that allowed us to do deep data exploration on each significant column presented, like we got to know:
*   Manhattan is the most focused place in New York for hosts to do their business.
* Manhattan and Broklyn has the most number of hosts.

*  Customers pay highest average amount in Manhattan for all the three types of room.

*  'Entire home/apt' room type has the highest number of listing of 52% and ‘Shared Room’ is the least listed room type at only 2.4% in total.
* There is highest avalibility in Staten Island and lowest in Brooklyn in the year.
*  People stay for longer duration of time in Private rooms in Brooklyn and Manhattan.
*  Words such as ‘bedroom’, ‘cozy’, ‘private’, ‘apartment’ and ‘spacious’ are used more frequently than words such as ‘park’, ‘near’, ‘village’ and ‘heart’.

*  Count of listing by top 10 hosts is almost 2.5%(1270 listings) of the whole dataset. Top three host base on their turnover are Sonder(nyc),Blueground, Sally and best host is Sonder(nyc).
*  More customer preferred Manhattan location for night stay then Brooklyn.
* The entire home appartment is highest in average minimum nights and private room is lowest.
* The top ten hosts with the most reviews helps in marketing.
* The most dense area is Brooklyn with respect to longitude and latitude.
* The heatmap can pe used as a corelation function which defines the impact of a attribute on another attribute.
