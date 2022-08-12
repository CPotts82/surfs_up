# surfs_up
## Overview
The purpose of the overall analysis was to help investors decide if they should contribute to a new venture; a Surf and Ice Cream shop in Oahu, Hawaii. The initial analysis concentrated on weather trends from August 2016 to August 2017 with a focus on amount of precipitation, the number of weather stations reporting weather data and how active they were in reporting.  These questions were all answered but the potential investors came back with another concern.  They would like to see the temperature trends for the months of June and December specifically.  This analysis focuses on the requested trends with data from January 2010 to December 2017 to see if the business can be sustained all year. 

## Resources
Jupyter Notebook, VS Code, SQLite, SQLAlchemy, Flask, hawaii.sqlite

## Results
The following results for June and December were taken from data spanning January 2010 to December 2017 for Oahu, Hawaii.
### June Temperature Results
- Average Daily Temperature - 74.94 degrees
- Minimum Daily Temperature - 64.00 degrees
- Maximum Daily Temperaure - 85.00 degrees

See Below - histogram that visualizes the frequency of the temperatures for the month of June from 2010 to 2017 in Oahu.

![June_Temperatures](https://user-images.githubusercontent.com/106348899/183990692-7999bff4-cceb-40c0-9a60-3f00ae680bb0.png)


### December Temerature Results
- Average Daily Temperature - 71.04 degrees
- Minimum Daily Temperature - 56.00 degrees
- Maximum Daily Temperaure - 83.00 degrees

See Below - histogram that visualizes the frequency of the temperatures for the month of December from 2010 to 2017 in Oahu.

![December_Temperatures](https://user-images.githubusercontent.com/106348899/183990216-5ba69aa5-953d-4223-9e3f-de7844e27b07.png)


## Summary
### Overall Analysis
This analysis focused on the temperatures for the months of June and December for the years 2010 through 2017.  The histograms with the results of the June and December temperatures show that while they do have low temperatures of 56 and 64 degrees, the frequency of those low temperatures is also low, meaning that low temperatures do not happen very often.  The temperatures that occur with the most frequency for June are between 70 and 77 degrees. For December, the most frequently occurring temperatures are between 69 and 77 degrees.  These warm temperatures are great for surfing and ice cream!  There will be chilly days in the fifties and sixties but they will not happen often.  And there will also be hot days with highs in the eighties, these days are most definitely welcome when it comes to surfing and a cold treat.  The temperature trends show that this business is sustainable year round. (With the climate change situation occuring and locations heating up, the demand for recreation that cools one off will be in demand.)

### Additional - Precipitation Queries for June and December
The investors only asked for an analysis of temperatures for June and December but temperature alone is not a complete assessment. Included is an analysis of precipitation for the months of June and December. Too much rain could be detrimental to a business as well as too cold of temperatures. The precipitation was assessed for all months of June and December from 2010 to 2017.  

### June Precipitation Results
- Average Daily Precipitation - 0.134
- Minimum Daily Precipitation - 0.000
- Maximum Daily Precipitation - 4.430

See Below - Table of Statistics that includes the count, standard deviation and percentiles for precipitation in June from 2010 to 2017 in Oahu.

![June_Precipitation](https://user-images.githubusercontent.com/106348899/183998178-d352b584-959d-4ff8-a429-439087059140.png)


### December Precipitation Results
- Average Daily Precipitation - 0.217
- Minimum Daily Precipitation - 0.000
- Maximum Daily Precipitation - 6.420

See Below - Table of Statistics that includes the count, standard deviation and percentiles for precipitation in June from 2010 to 2017 in Oahu.

![December_Precipitation](https://user-images.githubusercontent.com/106348899/183998506-77badc43-e4ae-4856-a662-0ac7f59448ba.png)
