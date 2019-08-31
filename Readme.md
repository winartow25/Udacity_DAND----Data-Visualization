
![alt text](2000px-Ford_GoBike_logo.svg-2.png "Logo Title Text 3")

## Dataset
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay Area. On June 28, 2017, the system officially launched as Ford GoBike in a partnership with Ford Motor Company.
This project has downloaded a provided dataset by [Lyft](https://s3.amazonaws.com/baywheels-data/index.html) for bike sharing data in the greater San Francisco Bay Area at July 2019 with approximately 20,000 bike-sharing data. Feature documentation is available [here](https://www.lyft.com/bikes/bay-wheels/system-data)

### Summary Of Findings
In this project, there are four main areas of analysis for the bike usage, there are based on Time (Montly, Daily, and Hourly Trend), Member age and Gender, User type. Additionally, this project also made recommendation of bike replenihsment during the two peak hours time zone(Morning: 7-9 a.m and Afternoon: 4-7 p.m).

1. Bike Usage Trend Analysis Based on Time
    - Daily Bike Usage in June 2019 is shown as multimodal distribution where the peak bike usage volume is dominated by weekday
    - Peak volume of bike usage are start from Monday until Wednesday
    - Peak Hours of bike usage are start from 7-9 a.m and 4.7 p.m
    - Trip length is slightly greater during the weekday compare with weekend, this might be due to traffic congestion

2. Bike Usage Trend Analysis in Based on Member Age and Gender
    - More than 75% user are in between 20-40 years old, this might indicates the bike-sharing user profile is professional, worker, or students
    - Male is dominating the market of bike-sharing for more than 70%

3. Bike Usage Trend Analysis in Based on User Type
    - 90% of bike usage is subscriber, this might a indicator that 90% of the bike sharing user are resident of San Franscisco Bay Area who are living, working, or schooling within the area. While, the normal customer is more likely a tourist and visitor.

### Recommendation for Bike Replenishment during Peak Hours
In this project, I also created a replenihsment model during the peak hours:

For **Morning Peak Hours**, these are recommendation for stations that need to be replenished based on the prioritization:

**From:**
1. San Francisco Caltrain (Townsend St at 4th St)
2. San Francisco Caltrain Station 2 (Townsend St at 4th St)
3. Grand Ave At Perkins St
4. 2nd Ave at E 18th St
5. Hubbell St at 16th St

**To:**
1. Montgomery St BART Station (Market St at 2nd St)
2. 19th Street BART Station
3. MacArthur BART Station
4. Post St at Keanny St
5. Powell St BART Station (Market St at 4th St)

For **Afternoon Peak Hours**, these are recommendation for stations that need to be replenished based on the prioritization:

**From:**
1. 19th Street BART Station
2. MacArthur BART Station
3. 4th St at 16th St
4. Post St at Keanny St
5. Salesforce Transit Center (Natoma St at 2nd St)
    
**To:**
1. San Francisco Caltrain Station 2 (Townsend St at 4th St)
2. San Francisco Caltrain (Townsend St at 4th St)
3. San Francisco Ferry Building (Harry Birdges Plaza)

_(Note: Due to the large bike shortage number in San Francisco Caltrain Station 2, the prioritization of bike replenishment is only made in those 3 stations by considering the balance of bike excessive and shortage)_

## Limitation

1. Distance between station to another station is not investigated in this project since it requeries further study about San Fransisco Map. Therefore, the data about longitude and latitude was dropped since it is not relevant to this project
2. Further mapping studies are also required to optimize the bike replenishment recommendation by considering distance from 1 station to another station and also congestion data would be an important information.


```python

```
