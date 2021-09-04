# Mapping Earthquakes

# Overview

Building insightful data visualizations with interactive features on earthquake data from around the world. Supporting website and mobile application development by using the latest earthquake GeoJSON data from the US Geological Survey website. Using JavaScript, D3 and Leaflet libraries to traverse the data and plot the data on a mapbox map using an API request. 

## Process:
Reference [index.html](https://github.com/corispade/Mapping_Earthquakes_1/blob/main/Earthquake_Challenge/index.html) and [challenge_logic.js](https://github.com/corispade/Mapping_Earthquakes_1/blob/main/Earthquake_Challenge/static/js/challenge_logic.js) for below deliverables.

### Deliverable 1: Tectonic Plate Data
1. Added tectonic plate data as a second layer group
2. Added tectonic plate data to the overlay map
3. Wrote a d3.json() callback to pass the geoJSON() layer and add color, width and labels to the tectonic plate lines
4. Added the tectonic layer group to the map legend

### Deliverable 2: Major Earthquake Data
1. Added major earthquake (magnitude 5 and higher) data as a second layer group
2. Added the major earthquake data to the overlay map
3. Wrote a d3.json() callback to pass the geoJSON() layer and add color, radius and popup labels to the markers
4. Added the major earthquake group to the map legend

### Deliverable 3: Dark Map Layer
1. Created a dark map tile layer
2. Added dark map to the overlay object and legend

## Resources:
Data Sources: 
* [All Earthquakes](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
* [Major Earthquakes](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)
* [Tectonic Plates](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)

Languages: JavaScript, HTML5, CSS

Environment: Visual Studio Code

# Webpage Results:


![picture](https://github.com/corispade/Mapping_Earthquakes_1/blob/main/Earthquake_Challenge/static/images/completed_map.png)
