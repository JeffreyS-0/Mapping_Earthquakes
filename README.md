# Mapping_Earthquakes

## Overview
The purpose of this analysis was to create an interactive world map to visually express the differences between the magnitudes of earthquakes all over the planet for the last 7 days. In order to complete this task, I had to use a URL for GeoJSON earthquake data from the USGS website to retrieve the geographical coordinates and the magnitudes of earthquakes for the past week. In order to pull the data from the website, I had to use JavaScript and the D3.js library. After pulling the data, I used the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Images
As you can see below, we have created 3 different interactive maps to show a dark world view, street view and the satellite view. The tectonic plates are lined in burnt orange and each earthquake is displayed by size and color dependent on their magnitude.

### Satellite View
![Satellite_img](https://user-images.githubusercontent.com/69607218/142790235-e9b41ee9-05bd-446a-b883-2b2a24d7bf14.png)

### Street View
![Streets_img](https://user-images.githubusercontent.com/69607218/142790250-c811fd53-917a-4ec3-be40-79125fa9f0c5.png)

### Dark View
![Dark_img](https://user-images.githubusercontent.com/69607218/142790254-4066f19b-043f-4caf-aa09-c09600ec9f8c.png)
