# Advanced Weather Analysis using API and Python 


OBJECTIVE:

The aim of this project is to perform advanced weather analysis using the API and python with it’s libraries like folium, requests, matplotlibs, pandas etc. The project includes retrieving weather data, saving it to Excel, visualizing temperature trends over time, and generating interactive weather maps for multiple cities.

PROJECT COMPONENTS:

1. Data Retrieval:
   - Utilized the OpenWeatherMap API to retrieve 5-day weather forecast data for multiple cities.
   - Extracted information such as date and time, temperature, and weather description.
   - Used ExcelWriter for exporting to Excel

2. Data Visualization:
   - Created line charts to visualize temperature trends over time for each city.
   - Plotted the date and time on the x-axis and temperature on the y-axis.
   - The charts provide an intuitive representation of temperature variations.

4. Interactive Weather Maps:
   - Implemented the Folium library to generate interactive maps.
   - Each map includes markers for each data point with details like temperature and weather description.
   - Saved the interactive maps as HTML files 

5. User Interaction:
   - Designed the script to allow user input for selecting cities dynamically.
  - Users can customize data retrieval based on their preferences by specifying     cities and corresponding OpenWeatherMap city IDs.


USAGE:

1. OpenWeatherMap API key is required for data retrieval.

2. Specified cities and their corresponding OpenWeatherMap city IDs in the `cities` list.

3. Executed the script, and it performed the following for each city:
   - Retrieve weather data.
   - Save data to Excel.
   - Visualize temperature trends.
   - Generate an interactive weather map.

CONCLUSION:

This project demonstrates an end-to-end workflow for advanced weather analysis using API and python and it’s libraries for data retrieval, storage, visualization, and interactive mapping. It serves as a foundation for further enhancements and customization based on user requirements.



