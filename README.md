# sqlalchemy-challenge

In this challenge we were tasked with data analysis of climate data in Hawaii. 
All files needed for this challenge are found in the resources file which include the SQLite database and starter code. 

This challenge consists of 2 parts. 

Part One. 
Using python and sqlalchemy create an engine to connect to the SQLite database. 
Session queries to analyze the data. 
Using the automap_base() to show the tables and classes of the data. 

We were then tasked to create two matplotlib plots to show our data vizualization. 


Part Two. 
Design a client app using flask and flask routes to fulfil these requirements. 

1. /
   
Start at the homepage.
List all the available routes.

2. /api/v1.0/precipitation
   
Convert the query results from your precipitation analysis (i.e. retrieve only the last 12 months of data) to a dictionary using date as the key and prcp as the value.
Return the JSON representation of your dictionary.

3. /api/v1.0/stations
   
Return a JSON list of stations from the dataset.

4. /api/v1.0/tobs
   
Query the dates and temperature observations of the most-active station for the previous year of data.
Return a JSON list of temperature observations for the previous year.

5. /api/v1.0/<start> and /api/v1.0/<start>/<end>

Return a JSON list of the minimum temperature, the average temperature, and the maximum temperature for a specified start or start-end range.
For a specified start, calculate TMIN, TAVG, and TMAX for all the dates greater than or equal to the start date.
For a specified start date and end date, calculate TMIN, TAVG, and TMAX for the dates from the start date to the end date, inclusive.
