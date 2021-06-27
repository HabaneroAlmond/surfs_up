# surfs_up 

Analyzing weather patterns using SQLite, SQLAlchemy and building climate apps using Flask.

# Overview
In this scenario we wanted to review an SQLite weather database to analyze information on conditions to convince a potential investor that opening a surf shop in Oahu, Hawaii could be a profitable venture. 

We used SQLAlchemy to connect/generate queries in our SQLite database and help us pull relevant information to our weather analysis. We also used VS Code to create Python apps that allowed us to share our results through a Flask routed webpage. 

# Results
To begin our analysis we looked at Oahu precipitation for a one year timeframe, specifically August 23 2016 - August 23 2017.
![image](https://user-images.githubusercontent.com/82848585/123556411-1b005580-d759-11eb-8949-14449e8ad088.png)

Our mean for precipitation was about 18%, which means a little over 80% of the time in Oahu it is not precipitating.

We also wanted to know the number of weather stations collecting precipitation data and find out which one was collecting the most data and use that for our temperature collection. After finding the station we used its data to determine the high low and average temperature for the same time period. Our results showed that the average temperature was 72°F with a high of 85° and a low of 54°.

![image](https://user-images.githubusercontent.com/82848585/123556426-25225400-d759-11eb-908e-f4a2cc5eb36d.png)

We then dove deeper into our analysis by looking at all of the observations recorded in the months of June and December. In the dataframes below the left represents June while the right represents December. We were able to find three key differences between June and December. 

![june_temp](https://user-images.githubusercontent.com/82848585/123559596-fdd48280-d76a-11eb-8646-37b43065e29f.png)![december_temps](https://user-images.githubusercontent.com/82848585/123559597-0036dc80-d76b-11eb-880b-9339108f9030.png)

  - The mean temperature differs by about three degrees from 74°(June) to 71° (December)
  - The lowest temperature in December was 56° while June was 64°
  - We only had 1517 temperature observations counted in December compared to 1700 in June

# Summary
Based on our data analysis the weather is looking good for the Surf N Shake investment. We found that the temperature in Oahu is relatively the same throughout the year in the mid 70s and the chances of continuous rainfall is low. If the investor Mr. W. Avy still isnt convinced then there are other avenues we can explore for further analysis. We could compare precipitation levels between June and December or other months, and find out if there is going to be an 'off season' month where Oahu will be expecting more than 18% of its days seeing rain. Instead of using the weather station with the highest level of observations we could choose a weather station closest to the exact store location to give us the most accurate representation of precipitation and temperature. Finally, we can look at larger historical data of precipitation and temperature and compare data based on yearly trends as opposed to the months in one year. 




