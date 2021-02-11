# World-Weather-Analysis
Using Python and APIs to give customers a tailored choice in choosing their city destination vacation.

# World Weather Analysis

## Basic Project Plan
_Task_ : collect and analyze weather data across cities worldwide
_Purpose_ : PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
_Method_ : Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

## In-Depth Project Plan
1. Collect the data by:
    Using the NumPy Module to generate more than 1,500 random latitudes and longitudes.
    Use the citipy module to list the nearest city to the latitudes and longitudes
    Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
    * Parse the JSON data from the API request.
    * Collect the following data from the JSON file and add it to a DataFrame:
      * City, County, Date
      * Latitutde and longitude
      * Maxium temperature
      * Humidity
      * Cloudiness
      * Wind speed
      
2. Exploratory Analysis with Visualization
    * Create scatter plots of the weather data for the following comparisons
      * Latitude versus Temperature
      * Latitude versus Humidity
      * Latitude versus Cloudiness
      * Latitude versus Wind Speed
    
    * Determine the correlations for the following weather data:
      * Latitude and Temperature
      * Latitude and Humidity
      * Latitude and Cloudiness
      * Latitude and Wind Speed
      
    * Create a series of heatmaps using the Google Maps and Places API that showcase the following:
      * Latitude and Temperature
      * Latitude and Humidity
      * Latitude and Cloudiness
      * Latitude and Wind Speed
      
3. Visualize Travel Data
    * Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. 
    
## Steps to follow to complete the analysis:
1. Filter the Pandas DataFrame based on user inputs for minimum and maximum temperature.
2. Create a heatmap for the new DataFrame.
3. Find a hotel from the cities' coordinates using Google's Map and Places API, and Search Nearby feature.
4. Store the name of the first hotel in the DataFrame.
5. Add pop-up markers to the heatmap that display information about the city, current maxium temperature, and a hotel in the city.

## Geography Notes:
- Latitudes are horizontal around the globe.
- Longitudes are vertical around the globe.
- The equator marks degree 0.
- Above the equator is positive to 90 degrees.
- Below the equator is negative to -90 degrees.
- The prime meridian represents zero meridian and splits the Earth into Eastern and Western Hemispheres.
- All meridians east of the prime meridian are considered positive, after 0 degrees and up to 180 degrees.
- All meridians west of the prime meridian are considered negative, after 0 degrees and up to -180 degrees.
- Geographic coordinate system (GCS) references any point on Earth by its latitude and longitude coordinates.
