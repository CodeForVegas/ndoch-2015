# Welcome to National Day of Civic Hacking 2015!   

## Challenges

To celebrate National Day of Civic Hacking, over 30 federal agencies have released new datasets and challenges to hack.  They are available here: 

http://hackforchange.org/announcing-national-day-of-civic-hacking-challenges/

## Open Data from the City of Las Vegas

The city of Las Vegas has an open data portal as well, with many data repositories.  That data can be found here: 

https://opendata.lasvegasnevada.gov/browse?limitTo=datasets

## Las Vegas Crime Data

An API for crime in Las Vegas has been setup.  You can access data using the following formats:

`http://curs.es:9000/lat/<latitude>/lng/<longitude>/distance/<distance>`

Distance is in meters and max distance is 5000 meters.

Example: http://curs.es:9000/lat/36.079411233095/lng/-115.02346661800036/distance/5000

You can also specify a time frame like so:

`http://curs.es:9000/lat/<latitude>/lng/<longitude>/distance/<distance>/startDate/<start date>/endDate/<end date>`

Year is in YYYY-MM-DD format.

Example: http://curs.es:9000/lat/36.079411233095/lng/-115.02346661800036/distance/5000/startDate/2014-12-16/endDate/2014-12-17




