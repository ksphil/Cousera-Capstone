# New Korean Restaurant Location among 5 major cities in Midwest

## St. Paul, MN, Chicago, IL, Indianapolis, IN, Detroit,MI, Columbus,OH 
***
Data Science Capstone Course

## Introduction
***
We are trying to open a new Korean Restaurant in Midwest. However, Midwest cities are not as populated as coast cities.<br>
Therefore, we consider only five cities. St. Paul, Chicago, Indianapolis, Detroit, and Columbus.<br>

Another factor we want to consider is competition. We don't want to open new restaurant where many Korean restaurants are located.<br>

We want to find a city where Korean restarants are spread out ranther than concentrated.<br>
We want to fidn a city with high Asain population. <br>
We want to fidn a city with small number of Korean restaurants <br>
In short, we want to find a city with lowest competition. 
## Data
***
I will use **FourSqaure API** to get the locations and Numbers of Korean restaurants in each cities. And I also use the Asian population information and areas from https://worldpopulationreview.com/us-cities for each cities. 
The data from 'worldpopulationreview.com' doesn't exist as a one table, it ahs been obtained maually. I choose Asian Population. Most of customers in Korean Restaurant are Korean. And secondly, other Asian. Of couse, Korean food s getting popular among white population also.
To simplify the analysis, I choose Asian.

I collect the land areas of the cities. I don't think it is critical choosing either land area or total area, since there is high correlation between them.
However, I choose land area assuming nobody lives on the water.


|City|Asian Population|Area|
|----|----|----|
|St. Paul|55,669|134.61|
|Chicago|175,109|588.81|
|Indianapolis|27,717|948.96|
|Columbus|49,616|566.18|
|Detroit|10,659|359.28|
