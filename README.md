# EDA_flights_data
EDA in python on flights data containing 2,71,940 records
Dataset is divided into 2 csv files, before proceeding with code, please merge both files into one file and name it as flights.csv and keep it in data repository of your system.
In this project, power of python libraries such as pandas, numpy, matplotlib is used to explore, analyze, visualize, and gain insights from vast dataset containing 2,71,940 records.
It is the first and most important part of data analyst, scientist, and machine learning engineer.

The dataset contains observations of US domestic flights in 2013, and consists of the following fields:
Year: The year of the flight (all records are from 2013)
Month: The month of the flight
DayofMonth: The day of the month on which the flight departed
DayOfWeek: The day of the week on which the flight departed - from 1 (Monday) to 7 (Sunday)
Carrier: The two-letter abbreviation for the airline.
OriginAirportID: A unique numeric identifier for the departure aiport
OriginAirportName: The full name of the departure airport
OriginCity: The departure airport city
OriginState: The departure airport state
DestAirportID: A unique numeric identifier for the destination aiport
DestAirportName: The full name of the destination airport
DestCity: The destination airport city
DestState: The destination airport state
CRSDepTime: The scheduled departure time
DepDelay: The number of minutes departure was delayed (flight that left ahead of schedule have a negative value)
DelDelay15: A binary indicator that departure was delayed by more than 15 minutes (and therefore considered "late")
CRSArrTime: The scheduled arrival time
ArrDelay: The number of minutes arrival was delayed (flight that arrived ahead of schedule have a negative value)
ArrDelay15: A binary indicator that arrival was delayed by more than 15 minutes (and therefore considered "late")
Cancelled: A binary indicator that the flight was cancelled
