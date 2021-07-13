# Data-Analysis-of-Boston-Crime
https://winnieshi.github.io/Data-Analysis-of-Boston-Crime/Data%20Analysis%20of%20Boston%20Crime.html

The project includes four parts: 
1. Boston crime data collection, 
2. Boston crime data analysis, 
3. Weather data collection and 
4. Analysis of weather&crime data. 

## 1. Boston crime data collection:
In this part,   
(1) converting all data to the proper data type,   
(2) filling or deleting missing values depending on different situations,  
(3) deleting duplicates,  
(4) deleting ambiguous data.  

## 2. Boston crime data analysis:
In this part, analyzing   
(1) number of crimes for different categories,  
(2) number of crimes for different districts,  
(3) number of crimes in time series.  
#### Conclusions
After diving into the Boston Crime Dataset, we can clearly see the trends and relations between the types of offenses, location and the occurances of the offense. The dataset shows:  
1. Top-5 non-shooting offense: 'Motor Vehicle Accident Response', 'Larceny', 'Medical Assistance', 'Investigate Person' and 'Others' and the top-5 shooting offenses.  'Aggravated Assault', 'Investigate Property', 'Ballistics', 'Homicide'and 'Vandalism'.  
2. Top-5 dangous district: Roxbuy, Dorchester, South End, Mattapan and Downtown.  
3. Highest number of offense was around August. The decrease of number of offenses on March 2020 may be caused by shutdown Policy for Covid-19. The dramatic increase of shooting offenses on May, 2020 may be caused by 'Killing of George Floyd' on May 25, 2020.    
2. The shooting offenses are more likely to happen from 22:00 to 24:00 and on weekends. 
3. The non-shooting offenses are more likely to happen during the weekdays and daytime. 
#### Advice:  
1. Relevant department should install more cameras on the street because motor vehicle accident response is the largest count of offenses and leaving scene in the vehicle accident occupied the most.  
2. Residents and shop-owners should also install cameras if necessary.   
3. Drivers should obey the traffic regularizations and buy the car insurance.  
4. Residents and travellers should avoid going out at late night.  
#### Summary:  
I use the Spark SQL to clean and parse the Boston Crime Dataset. Analyze the relations and trends and possible reasons between the types of offenses and locations. Provide advice for the police, residents and travellers. 

## 3. Weather data collection:
Collect data from https://www.ncdc.noaa.gov/cdo-web/ from 2015-06-01 to 2021-04-30

## 4. Analysis of weather and Crimes-Motor Vehicle Accident
In this part,
(1) Analysis relation between temperature and motor vehicle accident,
(2) Analysis relation between precipitation and motor vehicle accident,
(3) Analysis relation between wind speed and motor vehicle accident,
(4) Analysis relation between extreme weather(fog,hail,glaze,smoke) and motor vehicle accident,
(5) Analysis relation between snow all and motor vehicle accident.
#### Conclusions
(1) Number of motor vehicle accident doesnt't have same trends with temperature, but it has same trends with the number of all crimes.
(2) Precipitation, wind speed and extreme weather don't have impact on motor vehicle accident.
(3) 
