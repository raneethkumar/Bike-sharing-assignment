# Bike-sharing-assignment

# Project Name
> Bike Sharing Data Set.


## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]


## General Information
## --Problem statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

 
## Conclusions
# The equation of best fitted line is 

cnt= 0.2470(yr) + 0.0547(workingday) - 0.1666(windspeed) - 0.1180(spring) - 0.3041(Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) - 0.0889(Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist) + 0.0614(Saturday) + 0.1159('3') + 0.1310('4') + 0.2125('5') + 0.2376('6') + 0.2106('7') + 0.2363('8') + 0.2720('9') + 0.2052('10') + 0.1014('11')+ 0.0610('12')

# Demand of bike depends on the variables below

yr, workingday, windspeed, spring, Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds, Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist, Saturday, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12

the demand for bikes increases on workingday, saturday, in the months of 3 ,4 ,5 ,6 ,7 ,8 ,9 ,10 ,11 ,12
the demand for bikes decreases with windspeed, spring, Light Snow, (Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds), (Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist) conditions


## Technologies Used
- Pythom
- Numpy
- Pandas
- Matplotlib
- Seaborn


