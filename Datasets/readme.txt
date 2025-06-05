README.txt

==========================================
Flight Delay Data Files - Description
==========================================

This folder contains 4 CSV files related to flight data in the United States. 
These files are used for analyzing flight delays, airline information, and airport locations.

==========================================
1. flights.csv
==========================================

- Contains detailed information about individual flights.
- Includes data like:
  - Flight number
  - Airline code
  - Origin and destination airport
  - Scheduled and actual departure/arrival times
  - Delay times (in minutes)
  - Cause of delay (weather, airline, etc.)

Use this file to study how different factors affect flight delays.

==========================================
2. flight_delayed.csv
==========================================

- A simplified version of flight data focused only on delays.
- Contains:
  - Flight ID
  - Whether the flight was delayed or not
  - Delay duration
  - Important features used for prediction

Good for training machine learning models to predict delays.

==========================================
3. airlines.csv
==========================================

- Contains a list of airline codes and their full names.
- Example:
  - Code: AA
  - Name: American Airlines

Use this file to match airline codes in other CSVs with the actual airline name.

==========================================
4. airports.csv
==========================================

- Contains information about airports.
- Includes:
  - Airport code
  - Airport name
  - City and state
  - Latitude and longitude (location on the map)

Useful for mapping flight routes or analyzing airport locations.

==========================================
Usage Tip
==========================================

You can load these CSV files using Python and the Pandas library:

Example:
import pandas as pd  
flights = pd.read_csv('flights.csv')  
airlines = pd.read_csv('airlines.csv')

==========================================

