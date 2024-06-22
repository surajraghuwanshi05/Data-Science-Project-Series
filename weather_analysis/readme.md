# Weather Data Analysis
## Overview
This project focuses on analyzing historical weather data from JFK International Airport, NY, spanning from 1970 to 2022. The primary objective is to clean the dataset, perform exploratory data analysis, and implement a predictive model for forecasting the maximum temperature (tmax).

## Files
weather.csv: The dataset containing weather observations.
weather_analysis.ipynb: Jupyter Notebook with the data cleaning, analysis, and modeling steps.
README.md: Documentation for the project.
Data Description
## The dataset contains the following columns:

STATION: Weather station ID <br />
NAME: Station name  <br />
PRCP: Precipitation (in inches)  <br />
SNOW: Snowfall (in inches) <br />
SNWD: Snow depth (in inches <br />
TMAX: Maximum temperature (in Fahrenheit) <br />
TMIN: Minimum temperature (in Fahrenheit) <br />
Additional columns related to various weather observations and conditions. <br />

## Data Cleaning
Missing Values: Columns with more than 5% missing values were removed.  <br />
Forward Fill: Remaining missing values were forward filled.
Data Types: Ensured correct data types for each column. <br />
Date Indexing: Set the DATE column as the index and converted it to datetime. <br />
