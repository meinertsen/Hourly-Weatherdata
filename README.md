# Hourly-Weatherdata
Get historic hourly weather data from Wunderground and save it to a CSV file using python

Note that values will = -9999 or -999 for Null or Non applicable (NA) variables. Wundergrounds full Phrase Glossary. 

I will demonstrate how to wrangle the csv file in R and merge it with the data set from Kaggle's New York Taxi Trip Challange here:
https://github.com/meinertsen/WeatherWithR


- datetime: Date and time of day (EST)
- tempm: Temperature in Celcius
- tempi: Temperature in Fahrenheit
- dewptm: Dewpoint in Celcius
- dewpti: Dewpoint in
- hum: Humidity %
- wspdm: Wind speed in kph
- wspdi: Wind speed in mph
- wgustm: Wind gust in kph
- wgusti: Wind gust in mph
- wdird: Wind direction in degrees
- wdire: Wind direction description
- vism: Vivibility in Km
- visi: Visibility in miles
- pressurem: Pressure in mBar
- pressurei: Pressure in inHg
- windchillm: Wind chill in Celcius
- windchilli: Wind chill in Fahrenheit
- heatindexm: Heat index Celcius
- heatindexi: Heat index Fahrenheit
- precipm: Precipitation in mm
- precipi: Precipitation in inches
- conds: Conditions: See full list of conditions
- icon
- fog
- rain
- snow
- hail
- thunder
- tornado
