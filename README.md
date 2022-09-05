# Mapping_Earthquakes


![Satellite Map](https://github.com/rloufoster/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/SatelliteImage.png?raw=true)


## Overview:

For this project, we used data from the U.S. Geological Survey to create an interactive visualization that maps earthquake data by using Geo-coordinates. Scripts were written using JavaScript and D3.js library to retrieve the GeoJSON earthquake data from the USGS website and to access the geographical coordinates and magnitudes of earthquakes for the last seven days. Leaflet library was then used to plot the data on a Mapbox styled map through an API request. Layers were then added to the map that provide the user with options for different map styles (Street View, Satellite View and Dark View). In addition, the user can also choose to apply to the map, a line map of the Tectonic plates, locations of all earthquake activity, and if preferred, locations of only the major earthquake activity (4.5 magnitude or more). Since the data is being retrieved in real-time, the map updates with current information whenever it is accessed.


 * **Deliverable 1: Add Tectonic Plate Data**
 * **Deliverable 2: Add Major Earthquake Data for earthquakes with magnitude greater than 4.5**
 * **Deliverable 3: Add an Additional Map**
 
 
 ## Resources:
 
   * USGS website
   * GeoJSON URL
   * D3 Library
   * Mapbox API
   * Leaflet Library
   * JavaScript
   * VS Code
   
 
 
 ## Results: 
 
  
 * **Map of Tectonic Plates**
 
 ![TectonicPlates](https://raw.githubusercontent.com/rloufoster/Mapping_Earthquakes/c9945508d016d869373aa2871bd7f951c13896d7/Earthquake_Challenge/Images/TectonicPlates.png)
 
 
 * **Map of Earthquakes with magnitude of 4.5 or greater**
 
 ![Major Earthquakes](https://raw.githubusercontent.com/rloufoster/Mapping_Earthquakes/c9945508d016d869373aa2871bd7f951c13896d7/Earthquake_Challenge/Images/MajorEarthquakes.png)
 
 * **Additional Map - Dark**
 
 ![Dark Map](https://raw.githubusercontent.com/rloufoster/Mapping_Earthquakes/c9945508d016d869373aa2871bd7f951c13896d7/Earthquake_Challenge/Images/DarkMapImage.png)