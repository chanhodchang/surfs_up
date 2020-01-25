# surfs_up
Using Jupyter Notebook, VS Code, and SQLite to analyze weather data in Oahu 

## Project Overview
Using Python to manipulate data in SQLite to find weather patterns for the month of July. Data for which weather stations were most active were also analyzed. The data that was found was then put into a Flask app, coding in different routes to display the different data found.

The challenge project was to create a working function which would compute key weather data statistics for different months.
And using that function to find the weather data for July and December.

## Resources
- Data Source: hawaii.sqlite
- Software: Python 3.6.1, conda 4.7.12, Visual Studio Code 1.38.1, SQLite 3.30.1, Flask 1.1.1

## Summary 

The project was to find data about weather in Oahu in the month of August. SQLite was used to find the data and Flask was used to display it.

1. First all dependicies were imported
2. SQLite was then set up in Jupyter Notebook
3. Weather data for the month of August was then queried
4. Session.query was also used to find the data of each weather station
5. A Flask App was then created and separate routes were coded in to display the different data queried from SQLite

The challenge project was finding the different weather data for the months of July and December.

1. A calc_temps function was created to make the process of finding weather data easier.
2. July and December weather was found using the function

## Analysis

Looking at the data obtained for the month of August, it seems that the average rainfall is about 0.177 inches per hour. This is considered moderate rainfall and seems like the perfect weather to open shop.

|August | Precipitation |
|-------|---------------|
| count | 2021.000000   |
| mean  | 0.177279      |
| std   | 0.461190      |
| min   | 0.000000      |
| 25%   | 0.000000      |
| 50%   | 0.020000      |
| 75%   | 0.130000      |
| max   | 6.700000      |

For the data on the months of July and December, there seems to be a very miniscul difference between them. Average rainfall is 0.197 incher per hour in July and 0.170 inches per hour in December. There should be no worries to set up a store in Oahu since the weather looks good all year round.

| July  | Precipitation |
|-------|---------------|
| count | 2195.000000   |
| mean  | 0.196907      |
| std   | 0.556862      |
| min   | 0.000000      |
| 25%   | 0.000000      |
| 50%   | 0.020000      |
| 75%   | 0.140000      |
| max   | 9.640000      |

| December  | Precipitation |
|-----------|---------------|
| count     | 1318.000000   |
| mean      | 0.170008      |
| std       | 0.453680      |
| min       | 0.000000      |
| 25%       | 0.000000      |
| 50%       | 0.010000      |
| 75%       | 0.120000      |
| max       | 6.250000      |
