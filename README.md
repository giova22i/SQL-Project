# SQL-Project
Data Analysis on Chicago taxicab rides and weather reports to advise hypothetical ride-sharing company Zuber
What affects a taxi ride in Chicago?

## Background
This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist

**Skills Used: Data Collection and Storage (SQL)**

## Data Description
A database with info on taxi rides in Chicago:

**neighborhoods table: data on city neighborhoods**

* name: name of the neighborhood
* neighborhood_id: neighborhood code

**cabs table: data on taxis**

* cab_id: vehicle code
* vehicle_id: the vehicle's technical ID
* company_name: the company that owns the vehicle

**trips table: data on rides**

* trip_id: ride code
* cab_id: code of the vehicle operating the ride
* start_ts: date and time of the beginning of the ride (time rounded to the hour)
* end_ts: date and time of the end of the ride (time rounded to the hour)
* duration_seconds: ride duration in seconds
* distance_miles: ride distance in miles
* pickup_location_id: pickup neighborhood code
* dropoff_location_id: dropoff neighborhood code

**weather_records table: data on weather**

* record_id: weather record code
* ts: record date and time (time rounded to the hour)
* temperature: temperature when the record was taken
description: brief description of weather conditions, e.g. "light rain" or "scattered clouds"

## Libraries Used
* Pandas
* Matplotlib.pyplot
* seaborn
* scipy.stats
* numpy
* Beautiful Soup
* Requests
