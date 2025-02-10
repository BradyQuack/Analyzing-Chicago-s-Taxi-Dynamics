# Analyzing Chicago's Taxi Dynamics
View project: [Analyzing Chicago's Taxi Dynamics]()
## Project Description:
In this project, you will analyze taxi ride data in Chicago from November 2017 to extract actionable insights and test specific hypotheses regarding ride durations under varying conditions.
## Data Description: EDA and SQL Queries
### Neighborhoods table: data on city neighborhoods
name: name of the neighborhood

neighborhood_id: neighborhood code

### Cabs table: data on taxis
cab_id: vehicle code

vehicle_id: the vehicle's technical ID

company_name: the company that owns the vehicle

### Trips table: data on rides
trip_id: ride code

cab_id: code of the vehicle operating the ride

start_ts: date and time of the beginning of the ride (time rounded to the hour)

end_ts: date and time of the end of the ride (time rounded to the hour)

duration_seconds: ride duration in seconds

distance_miles: ride distance in miles

pickup_location_id: pickup neighborhood code

dropoff_location_id: dropoff neighborhood code

### Weather_records table: data on weather
record_id: weather record code

ts: record date and time (time rounded to the hour)

temperature: temperature when the record was taken

description: brief description of weather conditions, e.g. "light rain" or "scattered clouds"

## Data Description: Hypothesis Testing
### Taxi Company Data:
File: /datasets/project_sql_result_01.csv contains:

company_name: Name of the taxi company

trips_amount: Number of rides provided by each company on November 15-16, 2017.

### Neighborhood Data:
File: /datasets/project_sql_result_04.csv contains:

dropoff_location_name: Chicago neighborhoods where taxi rides ended

average_trips: Average number of rides ending in each neighborhood during November 2017.

### Ride Details Data:
File: /datasets/project_sql_result_07.csv contains:

start_ts: Timestamp for ride pick-up

weather_conditions: Weather at the time of ride pick-up

duration_seconds: Duration of each ride in seconds
