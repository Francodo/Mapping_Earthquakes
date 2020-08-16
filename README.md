# Mapping_Earthquakes
Francis Odo

Background 
This project demonstrates the application of data in creating maps. In particular, it shows how to map earthquake data in the very best visualization format using HTML, JavaScript and CSS programing language and techniques. 
Objective
The objective is to create a three-tiered layer map that presents a choice menu for the viewer using the GeoJSON formatted tectonic plates data from Github. 
Tools/Environment
Our development environment is Visual Studio Code. Programming is done using:
•	HTML
•	JavaScript
•	CSS
Data is supplied from a Github repository for Earthquakes tectonic plates in GeoJSON format (GeoJSON/PB2002_boundaries.json). Other sources of support material include (CDN – Mapbox, Leaflets)
Code Plan
JAVASCRIPT
•	Create a map variable with “mapid” and Geo-Location coordinates (Mapbox link).
•	Create a variable for the tile layer for the base map (Mapbox Link)
•	Create a variable for the satellite layer and add to the base map structure (Mapbox Link)
•	Create a variable for dark view and add to map (Mapbox Link)
•	Create a variable for light view and add to map (Mapbox Link)
•	Create a variable for the tectonic layer with the link or Github url for the data (GeoJSON/PB2002_boundaries.json)
•	Create a styling function with the necessary parameters (opacity, fillcolor, color, etc.)
•	Apply D3.json to retrieved data
•	Create and add circle and pop markers using L.circleMarker() function
•	Create overlays (for satellite and tectonic plates)
•	Create a legend with color reference to earthquake magnitude range.
HTML
•	Format HTML template
•	Include links for stylesheet
•	Include links for logic.js, config.js and style.css 
CSS
•	Create a style.css file
Approach
•	Create map image in HTML and display in web browser.
•	Folder arrangement
Risk
•	Map image requires a significant amount of computer memory. There may be a noticeable delay as the map page renders.
•	Coloring can be improved
Conclusion
The process of creating maps with earthquake data is successfully demonstrated as required. The code will need some improvement for better performance. 
Here are some sample screen shots:



