# WeatherCompare

## Authors

- Ryan Johnson
- Arman Bance

## Project Description

WeatherCompare is a Python website that lets users compare past weather in two cities.
Users will choose the cities and a month using a page built with Flask. We will get daily temperature and precipitation data from Open-Meteo, a weather service that provides data through an API.
The data will be saved in CSV files and used to calculate weather statistics for each city. We will also include charts showing temperature changes throughout the month and differences in total precipitation between the cities.

## Project Outline / Plan

### Interface Plan

We will use Flask to build two pages:

- **Data selection page:** Users can choose cities and dates, get weather data, and save or load CSV files
- **Results page:** Users can view the weather statistics and charts for their selected cities

The interface will have two city dropdowns, year and month dropdowns, and buttons to get data, save data, load data, open results, generate charts, and go back to the selection page.

### Data Collection and Storage Plan -Ryan Johnson

We will use Python's requests library to collect daily temperature and precipitation data from the Open-Meteo Historical Weather API.
The data will be organized into CSV files containing the date, city, mean temperature, maximum temperature, minimum temperature, and precipitation.
This will be used to build the data selection page and allow users to save and reload the collected data.
