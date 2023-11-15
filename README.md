# sqlalchemy-challenge

# PART 1
In this section, you’ll use Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database. Specifically, you’ll use SQLAlchemy ORM queries, Pandas, and Matplotlib. To do so, complete the following steps:

The majority of this task was to narrow down stations by usage and precipitation. The stations with the highest observations is USC00519281.

With temp measurements of:
Lowest Temperature: 54.0 F
Highest Temperature: 85.0 F
Average Temperature: 71.66 F

the last 12 months of precipitation:
![image](https://github.com/Elliotttye26/sqlalchemy-challenge/assets/142332245/a28ecb72-8e84-45df-bb64-7678869d7176)

Temperature and frequency of the most used station:
![image](https://github.com/Elliotttye26/sqlalchemy-challenge/assets/142332245/2c2b5443-73ef-47dd-b503-209adbe03b42)



# Part 2
Design Your Climate App


After creating the code I was able to return the below. Using this new URL, we can plug in the rest of the link and have it return the requested information. With more time I may be able to create a link that reads the information in a better format than the links currently read.

http://127.0.0.1:5000

/api/v1.0/precipitation - Precipitation data
/api/v1.0/stations - List of stations
/api/v1.0/tobs - Temperature observations
/api/v1.0/start_date - Temperature statistics from start date
/api/v1.0/start_date/end_date - Temperature statistics from start date to end date


Useful links used in this challenge:
https://discuss.python.org/t/get-http-1-1-404-get-favicon-ico-http-1-1-404/34577
https://stackoverflow.com/questions/22945626/import-is-not-working-after-exporting-an-environment-variable-in-python
https://docs.sqlalchemy.org/en/20/core/engines.html

I also utilized askBCS more in this challenge than I have in any other.
