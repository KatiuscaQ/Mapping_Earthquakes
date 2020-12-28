# Mapping Earthquakes

## Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Tasks
To complete this project, a URL for GeoJSON earthquake data from the USGS website will be used to retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then the data will be added to a map.

## Approach
The approach will be to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. The Leaflet library will be used to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Results

### Tectonic Plate Data
The tectonic plate data was added to the map as a layer and as an overlay object, the color selected was red in order to make it stand out on all maps. Images of how the tectonic plate data are shown in two types of maps:
#### - Street view:
![](https://github.com/KatiuscaQ/Mapping_Earthquakes/blob/main/Resources/Deliverable1_street.PNG)
#### - Satellite view:
![](https://github.com/KatiuscaQ/Mapping_Earthquakes/blob/main/Resources/Deliverable1_satellite.PNG)

### Major Earthquake Data
The major earthquakes recorded for the past 7 days are added to the maps with the tectonic plate data as a new layer and as a new overlay object. The earthquakes are shown as circles which radii and colors are equivalent to their magnitudes, a popup feature was added to display the magnitude and location of each earthquake, and a legend was added to provide an easy visual explanation to what the colors mean.
The following images are of the two map views:

#### - Street view with all datasets "on":
![](https://github.com/KatiuscaQ/Mapping_Earthquakes/blob/main/Resources/Deliverable2_street.PNG)

#### - Satellite view with only the "Major Earthquakes" dataset activated and a popup with information of one of the major earthquakes recorded:
![](https://github.com/KatiuscaQ/Mapping_Earthquakes/blob/main/Resources/Deliverable2_satellite.PNG)

### Additional map
A dark view was chosen as the additional map. The contrast with the color pallet of the earthquakes and the tectonic plate data are more visually appealing with a dark background.

![](https://github.com/KatiuscaQ/Mapping_Earthquakes/blob/main/Resources/Deliverable3_dark.PNG)

## Resources 
- For the tectonic plate data: https://github.com/fraxen/tectonicplates/blob/master/GeoJSON/PB2002_boundaries.json

- For the major earthquake data:
https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson
