# About dataset

## Context

Divvy is a bike sharing service in Chicago USA. This dataset contains records of individual rides taken by users of the system. The Divvy system has two classes of users, annual Members, and Casuals who purchase passes good for a single trip or a full day.

## Content

The data includes information on bike trips, stop name, duration, type of bike share user. The original data was provided monthly and then concatenated to make it more suitable for the analysis.

the dataset include:

ride_id: a numerical and letter ID

rideable_type: the type of bike utilized for the trip

started_at: time which the ride starts

ended_at: time which the ride ended

start_station_name: name of station where trip started

start_station_id: station id where trip stated

end_station_name: name of station where trip ended

end_station_id: station id where trip ended

member_casual: membership type

Some columns were removed for not adding any insight for this analysis, these columns include:

start_lat: latitude where the trip started

start_lng: longitud where the trip started

end_lat: latitude where the trip ended

end_lng: longitud where trip ended


## Acknowledgements

The original dataset can be downloaded <a href="https://divvy-tripdata.s3.amazonaws.com/index.html" target="blank">here</a>

## Inspiration

It can be a very good experience to explore it, it gives you knowledge on how often people use bikes to move around the city and the time spent on it.

Some ideas worth exploring:

What are the top five most popular stations to start a trip?

What is the most used start-station by users? 
