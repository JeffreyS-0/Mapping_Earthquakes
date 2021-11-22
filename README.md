# Mapping_Earthquakes

## Overview
The purpose of this analysis was to create an interactive world map to visually express the differences between the magnitudes of earthquakes all over the planet for the last 7 days. In order to complete this task, I had to use a URL for GeoJSON earthquake data from the USGS website to retrieve the geographical coordinates and the magnitudes of earthquakes for the past week. In order to pull the data from the website, I had to use JavaScript and the D3.js library. After pulling the data, I used the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Images
As you can see below, we have created 3 different interactive maps to show a dark world view, street view and the satellite view. The tectonic plates are lined in burnt orange and each earthquake is displayed by size and color dependent on their magnitude.

### Satellite View
![Satellite_img](https://user-images.githubusercontent.com/69607218/142789657-521285d8-b2b6-49d5-8494-a2180bde501c.png)

### Street View
![Streets_img](https://user-images.githubusercontent.com/69607218/142789699-65f95d1b-1028-4bdc-ae7b-720f89004487.png)

### Dark View
![Dark_img](https://user-images.githubusercontent.com/69607218/142789713-91d6e096-2247-4077-98c1-3db1a18770b8.png)
