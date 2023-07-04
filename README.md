# SQLAlchemy-challenge
![SurfsUp](https://github.com/AnaTipps/SQLAlchemy-challenge/assets/131827518/4a808f29-c02f-47d9-bf5c-156aa2de1246)

## Instructions
For this project a climate analysis of a well-known holiday destination (Honolulu) was done. The following sections outline the steps taken to accomplish this task.

## Part 1: Analyze and Explore the Climate Data
In this section,  Python and SQLAlchemy were used to do a basic climate analysis and data exploration of a given climate database. Specifically, SQLAlchemy ORM queries, Pandas, and Matplotlib were used. 

A precipitation analysis and a station analysis were perfomed.
#### Detailed analysis can be found in the climate_final Jupyter notebook.

## Part 2: Design Your Climate App
A Flask API based on the queries developed in the previous section was created. To do so, Flask was used to create routes as follows:

/

Welcome,  homepage.

All the available routes were listed.

  /api/v1.0/precipitation
  
  /api/v1.0/stations
  
  /api/v1.0/tobs
  
  /api/v1.0/start 
  
  /api/v1.0/start/end

JASON lists and dictionaries were created. 
#### Code can be found on the app.py file
