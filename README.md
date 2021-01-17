# tableau-challenge

<p align="center"><img src="https://github.com/meielerol/tableau-challenge/blob/main/Images/LocationStatus-ZipCode-ColorStatus.png" alt="New York City Citi Bike Stations"></p>

## Tableau Workbook

The workbook can be found online on [Tableau Public](https://public.tableau.com/profile/lorelei4499#!/vizhome/CitiBike_Stations/CitiBikeUsage) or on this repo as [CitiBike_Stations.twbx](https://github.com/meielerol/tableau-challenge/blob/main/tableau-workbooks/CitiBike_Stations.twbx).

## Datasets

The data was taken from the [Citi Bike System](https://www.citibikenyc.com/system-data) site.

The 2020 Citi Bike trip data was downloaded from the csv's available at (). January through Decembers data was compiled onto a the single csv file [2020-combined-citibike-tripdata.csv](https://github.com/meielerol/tableau-challenge/blob/main/Resources/2020_TripData/2020-combined-citibike-tripdata.csv).

The json files [stations.json](https://github.com/meielerol/tableau-challenge/blob/main/Resources/stations.json) and [station_information.json](https://github.com/meielerol/tableau-challenge/blob/main/Resources/station_information.json) were also used to create some of the reports found in this tableau workbook. The `stations.json` helped to provide the status of the various stations in New York City.

Trip duration time had to be converted from seconds to minutes. The different user types were customers and subscribers. Customers are those who have either a 24-hour pass or a 3-day pass, while subscribers were annual members. Gender was given aliases in the workbook since 0 = unknown, 1 = male, 2 = female. Age was determined by subtracting the birth year from 2020. Because there were some very old/weird ages being reported from the data, Age was filtered down to an upper limit of 80 in most places.

## 2020 Observations

### Popular Stations

1. Grove St PATH
2. Newport Pkwy
3. Liberty Light Rail
4. Hamilton Park

<p align="center"><img src="https://github.com/meielerol/tableau-challenge/blob/main/Images/Dashboard_2020_PopularStations.png" alt="Popular Stations"></p>

### Popular Months

May and June both show to be popular months for longer bike rides utilizing the Citi Bikes, while September has the most trips taken using these bikes.

<p align="center"><img src="https://github.com/meielerol/tableau-challenge/blob/main/Images/2020_TripCount-TripDuration-v-Month.png" alt="Trip Duration vs. Trips Taken vs. Month"></p>

### User Types

Though most of the users are single use customers, subscribers tend to utilize the bikes more frequently and for shorter durations than customers. Most subscriber taken trips report to be between from the 25-40 age demographic.

The longest rides tend to be completed by people between the ages of 17-26. Though after the decrease in users between ages 26-29, the 30+ year olds maintain a relatively consistent usage of the Citi Bikes.

<p align="center"><img src="https://github.com/meielerol/tableau-challenge/blob/main/Images/2020_Usertype-v-Age.png" alt="User Type by Age"></p>

<p align="center"><img src="https://github.com/meielerol/tableau-challenge/blob/main/Images/2020_TripDurationByGender-v-Age.png" alt="Trip Duration by Gender and Age"></p>

<p align="center"><img src="https://github.com/meielerol/tableau-challenge/blob/main/Images/Dashboard_2020_TripDuration-v-UserType-Age.png" alt="Trip Duration with Age"></p>
