# Chicago Crime Data

For this project, our group decided to focus on Chicago crimes.  We downloaded the [Chicago crime data](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2) from 2001 to 2020 as a csv and did the same for [Rockford](https://catalog.data.gov/dataset/city-of-rockford-crime-offenses-2016-ytd) from 2011-2016 to have some comparative data.

#### Data Cleaning -  
- Used Python pandas to read in csv, group together similar crimes, drop null values, and change data types

#### Visualizations -  
- Heat maps that showed where the most dangerous crimes occurred  
- Pie charts and bar charts depicting the types of crimes committed each year  
- Scatter plots with a linear regression predicting the trend of number of crimes by month  
- Time series showing the number of crimes per year  
<img src="https://github.com/MissWibbon/chicago_crime_data/blob/master/images/heatmaps.gif" width=200> <img src="https://github.com/MissWibbon/chicago_crime_data/blob/master/images/ChicagoCrimeTypes.png" width=200> <img src="https://github.com/MissWibbon/chicago_crime_data/blob/master/images/ChicagoRockfordTimeSeries.png" width=200>

#### Analysis -  
We found that theft was the most common crime throughout 2001-2020 in Chicago. This could be true for many cities, as it was for Rockford as well. Per the monthly breakdown, more crimes are commited in warmer months than the others. If the current crime rate regression remains true, the number of crimes committed in Chicago for April, 2020 will be 14,318. Lastly, as expected, we found that Chicago had a higher rate of violent crimes compared to Rockford and we believe if we tested this with more cities we would see that higher percentage of violent crimes typically occur in bigger cities.  

**Technologies and Tools Used:** Python, pandas, Gmaps, matplotlib, numpy, requests, json  

**Contributors:** [Kelsey Oros](https://github.com/kelseyoros), [Michelle Wuebben](https://github.com/MissWibbon), [Graham Livingston](https://github.com/gramlivingston), [Ian Tolleson](https://github.com/Ian-Tolleson), [Tong Su](https://github.com/tongsu21), [Michael Gonzalez](https://github.com/Gonzmj01)