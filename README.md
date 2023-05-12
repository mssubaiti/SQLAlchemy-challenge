# SQLAlchemy-challenge

The SQL Alchemy challenge on Python using SQLAlchemy to connect to a SQLite database and perform queries on its data. It has a Flask app that lets developers create web applications in Python and return JSON responses.


 The API routes:

/api/v1.0/precipitation: Returns the last 12 months of precipitation data in the database.
/api/v1.0/stations: Returns a list of all weather stations in the database.
/api/v1.0/tobs: Returns the last 12 months of temperature observations for the most active weather station in the database.
/api/v1.0/<start>: Returns the minimum, average, and maximum temperature for all dates greater than or equal to the specified start date.
/api/v1.0/<start>/<end>: Returns the minimum, average, and maximum temperature for all dates between the specified start and end dates.
