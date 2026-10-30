# EV-Charging-Station-Locator
It is a web-based Electric Vehicle (EV) charging station monitoring system that displays charging station information through a dashboard and an interactive map.

⚡ VOLT//GRID -- EV Station Network
Project Overview
VOLT//GRID is a web-based Electric Vehicle (EV) charging station
monitoring system. It provides a dashboard and an interactive map to
explore simulated EV charging stations across selected areas of Chennai.

The application displays station availability, online/offline status,
charging prices, distance from a reference location, and available
charging slots. Users can filter stations and select map markers to view
individual station details.

This project was developed as a Data Structures and Algorithms (DSA)
Micro Project.
Objectives
- Build an interactive dashboard for monitoring EV charging stations.
- Display charging station availability and operational status.
- Calculate the distance between a reference location and each
  station.
- Visualize station locations on an interactive map.
- Filter and process station information efficiently.
- Present station details through a simple user interface.
Features
1. Network Dashboard
- Displays the total number of charging stations.
- Shows the number of online and offline stations.
- Displays the total number of available charging slots.
- Presents station information in a table.
2. Station Filtering
- View all stations.
- Filter online stations.
- Filter offline stations.
- Update the station table according to the selected filter.
3. Interactive Map
- Displays charging stations on a map.
- Uses different marker colours for online and offline stations.
- Shows a reference user location.
- Allows users to select a marker and view station details.
4. Station Details
For each station, the application displays: - Station ID and name -
Online/offline status - Charging price per kWh - Distance from the
reference location - Total charging slots - Available charging slots
5. Map Layers
Users can switch between: - Esri Dark Map - OpenStreetMap - Esri
Satellite View
6. Other Controls
- Re-scan: Generates a new set of simulated station data.
- Power Off / Power On: Displays the application's power-off
  screen.
Technologies Used
  Technology      Purpose
  HTML5           Structures the web application
CSS3            Styling, layout, animations and responsive design
JavaScript      Application logic and data processing
Leaflet.js      Interactive map and station markers
OpenStreetMap   Map tiles
Esri Maps       Dark and satellite map layers
DSA Concepts Used
Arrays
Arrays store the station-area information and generated charging station
records.
Array Methods
The project uses JavaScript array methods: - map() to generate station
records and map data. - filter() to select online or offline
stations. - reduce() to calculate the total number of available
charging slots.
Haversine Distance Formula
The distKm() function uses the Haversine formula to estimate the
geographical distance between two latitude/longitude coordinates.
Data Generation and Processing
JavaScript random-number functions generate simulated station status,
prices and charging-slot values. The generated records are then
processed for the dashboard, table and map.
How the Project Works
1. The application generates station records for selected Chennai
   neighbourhoods.
2. Each station is assigned an ID, name, coordinates, status, price and
   charging-slot information.
3. The dashboard calculates and displays the total stations, online
   stations, offline stations and free slots.
4. Users can filter the table by station status.
5. The map displays the generated station locations using coloured
   markers.
6. Selecting a marker opens a panel containing that station's details.
7. Selecting Re-scan generates a new set of simulated station
   values and refreshes the display.
