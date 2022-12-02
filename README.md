# World_Weather_Analysis
Module 6: APIs and World Wide Weather

# Brief Summary 

This project was created to ultimately build a travel itinerary to cities that met certain temperature criteria of the traveler. 

There were three parts to building the finaly product (Deliverable 3).

- **Deliverable 1**: We first used OpenWeatherMap API to genereate a random list of cities to choose from, and used this as the list to reference moving forward. The lat/lngs used as bounding parameters were arbitrarily chosen due to where most land is located on earth. 
- **Deliverable 2**: We created 2 varaibles to produce a temperature range at which the traveler would like to be in. We used those parameters to filter out preferred cities from the list generated in Deliverable 1, cleaned the preferred cities list up, and used it to call the Geoapify API for information about each city, and to find the nearest hotel to the city centers. Any cities that didn't return hotels were removed from the list, and the remaining cities were plotted on a map.
- **Deliverable 3**: We used the cleaned up list and map from Deliverable 2 to pick four cities to travel to... using hvplots mapping function, we plot a map showing the route between the selected cities. 

