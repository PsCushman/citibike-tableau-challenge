![Screen Shot 2023-07-24 at 12 35 19 PM](https://github.com/PsCushman/citibike-tableau-challenge/assets/122395437/a067b31d-3115-4908-b692-b57d840d788d)
# Citibike Ridership Analysis
Discovering trends in ridership after the pandemic... 

## Tableau Public Link

[https://public.tableau.com/app/profile/payson.cushman/viz/CitiBike_Tableau_Challenge_PSC/TheWholeStory?publish=yes]

## Analysis

Pre Pandemic CitiBike from Jersey City was a useful if not unpopular mode of transportation. 

Post Pandemic ridership has rapidly increased even while other modes of public transportation in the New York City Area have seen signifigant decreases. 

In this Tableau Story, we will attempt to illustrate where and when the largest increases have been seen in CitiBike ridership throughout Jersey City in relation to it's pre Pandemic levels. 

Pre Pandemic CitiBike from Jersey City was a useful if not unpopular mode of transportation. 

Post Pandemic ridership has rapidly increased even while other modes of public transportation in the New York City Area have seen signifigant decreases. 

In this Tableau Story, we will attempt to illustrate where and when the largest increases have been seen in CitiBike ridership throughout Jersey City in relation to it's pre Pandemic levels. 

Ridership in 2022 of CitiBikes was up over 160%, while in Feubuary 2023, Subway and Bus Ridership were both hovering around 65% of the ridership compared to Febuary 2019. https://comptroller.nyc.gov/wp-content/uploads/documents/Riders-Return-February-2023-Snapshot.pdf

![Screen Shot 2023-07-24 at 11 13 59 PM](https://github.com/PsCushman/citibike-tableau-challenge/assets/122395437/1c9c5032-f5fb-4c25-872a-77dd5e0de3e9)
![Screen Shot 2023-07-24 at 11 19 49 PM](https://github.com/PsCushman/citibike-tableau-challenge/assets/122395437/99bfeb4f-d042-4f0d-b012-7a991a722371)


A note on Data Wrangling...

To create a table that could be analized, some column names needed to be updated because the headers were changed mid 2022. 

To compare longer periods of time (3 full years), the Jersey City data sets were more adaptable. The files were much smaller and thus, could be utilized in Tableau Public with exceeding to 1 GB limit. 

That said, an article from the NY Times suggests that the findings in this analysis are consistent with trends across New York City. https://www.nytimes.com/2021/12/02/nyregion/citi-bike-parking-docking-station.html

During 2020 and the height of the pandemic, there was a slight decrease in ridership. Yet, it was much smaller than expected. After the pandemic, there is a signifigant increase.

![Screen Shot 2023-07-24 at 11 14 49 PM](https://github.com/PsCushman/citibike-tableau-challenge/assets/122395437/fbdb6f97-6c0a-4c63-9b07-74b1fad22ad4)

To explore whether  the jump in ridership truly followed the pandemic, we took a look at the ridership for the winter months of all three years to detrmine if the there had already been signigifant increases that may have been halted by the pandemic and the city shut down. While there had been an increase between 2018 and 2020 in these winter months, it was meager when compared to the jump post pandemic.

![Screen Shot 2023-07-24 at 11 15 32 PM](https://github.com/PsCushman/citibike-tableau-challenge/assets/122395437/d45aaf8d-86e3-4a64-8edc-44ae409b72c2)


2018 to 2020 saw 21, 811 increase in ridership. The jump from 2020 to 2022 is twice as large (43,643).

The fact that Grove St. PATH station is consistently the highest use station suggests that CitiBike is being used in concert with other modes of public transportation.

![Screen Shot 2023-07-24 at 11 16 14 PM](https://github.com/PsCushman/citibike-tableau-challenge/assets/122395437/4f56d3e3-ccd3-4023-82f9-d2c313021b07)


There has been an increase in active stations post pandemic. Is it the cause of or the response to an increasing demand? 

Is CitiBike the New PATH???

NOT YET: 2022 the PATH system saw 45,501,400 rides (over 22 million orginating in New Jersey). https://en.wikipedia.org/wiki/PATH_(rail_system)

Jersey City's TOTAL CitiBike ridership in 2022 didn't crack a million.

Expectedly, there are a greater number of riders during commuter hours in all three years, but take a look at 2020; specifically, it peaks and valleys

![Screen Shot 2023-07-24 at 11 17 05 PM](https://github.com/PsCushman/citibike-tableau-challenge/assets/122395437/58da1102-a5f9-41d5-98d8-7ce61db87e33)

The valleys are less severe and the peaks are longer.

Not only are there more people traveling during regular comuter hours, there are more people traveling during "off-peak" hours including 10 AM - 2 PM and even late at night and into the early morning.

![Screen Shot 2023-07-24 at 11 18 29 PM](https://github.com/PsCushman/citibike-tableau-challenge/assets/122395437/629e284f-4366-47b7-b0d7-17d913750e0b)


## Requirments
Map (25 points)

Markers for all bike stations (5 points)
Station markers indicate popularity by color, size, shape, or some other means (5 points)
Ability to change marker data based on month and year (5 points)
Sections are marked by zip code (5 points)
A write-up on the trends that were discovered while making the map (5 points)

Visualizations (25 points)

4-10 total visualizations (5 points)
A total of 2 Tableau dashboards, each dedicated to a specific data discovery (5 points)
Dashboards are named appropriately (5 points)
Data is cleaned such that data entry errors are removed and columns are correctly typed (5 points)
Visualizations can logically be used to explore the data (5 points)

Tableau Story (25 points)

Individual visualizations are used (5 points)
Dashboards are used (5 points)
A map is used (5 points)
Visualizations on the same page are clearly related to one another (5 points)
The story is informative and easy to navigate (5 points)

Analysis (25 points)

Analysis is written in a markdown file or included in the Tableau Public workbook (5 points)
Analysis describes the dashboards and any interesting data discoveries contained within them (5 points)
Analysis on the chosen city official requested map detailing any noticeable trends (5 points)
The written analysis references specific visualizations and interactive features (5 points)
The document is written in a manner that a non-technical reader could understand (5 points)
