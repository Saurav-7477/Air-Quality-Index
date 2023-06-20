# AQI_
Air Quality Index

### Air Quality Index (AQI) is a measure used to assess the quality of air in a particular area, taking into account various pollutants that can have detrimental effects on human health and the environment. It provides a standardized and easily understandable way to communicate air quality levels to the public. The significance of air quality and its impact on human health and the environment has gained increasing attention in recent years. As pollution levels continue to rise in many regions, there is a growing need to monitor, analyze, and understand air quality data to make informed decisions and take proactive measures to mitigate pollution.


# Data Collection and Analysis
## This repository contains Python scripts for data collection and analysis of climate and air quality data.

# Data Collection
### The data_collection.py script collects climate data from the website "https://en.tutiempo.net/climate" for the years 2013 to 2018. It uses the requests library to fetch HTML data for each month and year and stores it in the "Html_data" directory. The collected data is saved as HTML files with the naming convention "year/month.html".

# Data Analysis
### The data_analysis.py script reads the collected HTML data and performs analysis on the climate and air quality data. It extracts the PM2.5 values from the HTML files and calculates the average PM2.5 values for each month and year. The results are then visualized using line plots.

The script generates line plots to visualize the average PM2.5 values over time for each year. The plots show the trend of PM2.5 pollution levels throughout the year.

# Dependencies
The following Python libraries are required to run the scripts:
### os
### time
### sys
### requests
### pandas
### numpy
### matplotlib
### seaborn
### BeautifulSoup
### csv


## Please make sure to install the dependencies before running the scripts.
