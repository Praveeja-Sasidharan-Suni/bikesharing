# Bikesharing

Using tableau to analyze bikeshare data in NYC.

## Overview of the Analysis

The purpose of our project is to see if the bike rental business is worth investing in Des Moines. One of the key factors we need to look at is trip duration. Finding out how long the trips
are in the month of August will give us a good analysis on when the bikes are rented, how long they are rented and what times are the most 
popular times to rent a bike. Before we do any of this there needs to be a change made in the csv to change the column that records the trip duration in seconds to hours, minutes and 
seconds. Once this was completed I uploaded the new CSV into tableau with the converted tripduration column.

## Results:

### Deliverable 1

-Using Python and Pandas functions, we will convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). 
After we convert the "tripduration" column to a datetime dataytpe, we will export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

![datetime-conversion.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/datetime-conversion.PNG?raw=true)

-The data in the "tripduration" column is converted to a datetime datatype and has the correct time format.
The DataFrame is exported as a new file without the index column. 

![newcsv.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/newcsv.PNG?raw=true)

### Deliverable 2

Using tableau I have created 8 different visulizations using the total number of trips, the types of users and the trip duration. Here are the findins:

-There was a total of 2,344,224 trips in the month of August.

-Checkout time for Users:Most users take the trip in an hour with a majoroty of trips in 10 minutes.

![checkout%20time%20for%20users.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/checkout%20time%20for%20users.PNG?raw=true)

-Checkout time for gender:Most citi bike users are males.There are 108,087 males users and 34,151 female users.

![checkout%20time%20for%20genders.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/checkout%20time%20for%20genders.PNG?raw=true)


-Trips by Week day for each hour:Thursday is the most popular day to take a bike ride.The heaviest citi bike traffic occurs during office starting and ending hours like 8am in the 
morning and 5-7pm in the evening.

![trips%20by%20weekday.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/trips%20by%20weekday.PNG?raw=true)


-Trips by Gender:Most citi bike users are males.But both male and female users display the same riding pattern when it comes to the hpours of the day.

![Trips%20by%20gender.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/Trips%20by%20gender.PNG?raw=true)

-User trips by gender by week day:Male subscribers are the most active citi bike users.

![user%20trips%20by%20gender%20and%20weekdays.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/user%20trips%20by%20gender%20and%20weekdays.PNG?raw=true)

-Total customers:There are 1,900,349 subscribers and 443,865 customers. 

![customers.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/customers.PNG?raw=true)
 
-Gender breakdown: There are 1530271 male,588431 female and 225531 other bike riders .

![Gender%20breakdown.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/Gender%20breakdown.PNG?raw=true)

-August peak hours:The peak bike ride hours are between 5.6pm.

![August%20peak%20hours.PNG](https://github.com/Praveeja-Sasidharan-Suni/bikesharing/blob/main/images/August%20peak%20hours.PNG?raw=true)

-To see all of my visualizations please click the link below:

[Link to Tableau Dashboard](https://public.tableau.com/app/profile/praveeja.sasidharan.suni/viz/BikeSharing_16319989367740/Bikesharingstory?publish=yes)

### Deliverable 3
- A detailed written report on bike sharing is done.

## Summary

From my visualisations, its clear that Thursday is the most popular day to take a bike ride and the business is in peak during office starting and ending hours.
It would be a good idea for our customer to start the bikeshare business in a different city because whether people are biking to get to work or just doing it for fun,
there are lots of subscribers and customers.Tourists could also be using citibikes to explore the city throughout the day, which plotting trip paths would be able to show. 
Although I think we have enough evidence to convince our customer to do this even if we are only looking at one month, 
there are some other visulizations that can further back this claim. If we are able to look at the colder months in the city to see how many riders we have in November/December so that the customer can prepare for those months too .
