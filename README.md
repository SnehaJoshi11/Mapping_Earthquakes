# Mapping_Earthquakes

## Project Overview

For this project we are creating an interactive map that shows the latest earthquake activity around the world. Maps allow us to explore, understand and make decisions about the world.

## Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

Approach will be to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. Also, use of the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

<p align="center">
<img src="Images/Earthquakes_Challange.png" width="60%" height="60%">
</p>

<p align="center">
 <i>An interactive world map of earthquakes</i>
</p>

## Requirements

**The map of earthquakes around the world contains:**

-	Overlay object for **Tectonic plates**.
-	Overlay object for **Earthquakes of the past 7 days**.
-	Overlay object for **Major earthquakes of magnitude above 4.5**.
-	Three different **map styles**:
    - Street view.
    - Satellite view. 
    - Dark view.
-	**A popup marker** with information about the location and magnitude of the earthquake.
-	**The radius** and **the color** of a marker reflect the earthquake intensity.
-	**A legend** with the context for the map.

#
**Tectonic Plate Data**

<p align="center">
<img src="Images/Earthquakes_Challange_Tectonic_Plates.png" width="60%" height="60%">
</p>
<p align="center">
 <i>An interactive world map of Tectonic Plates</i>
</p>

Tectonic plates are pieces of Earth's crust and uppermost mantle, together referred to as the lithosphere. The plates are around 100 km (62 mi) thick and consist of two principal types of material: oceanic crust (also called sima from silicon and magnesium) and continental crust (sial from silicon and aluminium). [Ref-Wikipedia](https://en.wikipedia.org/wiki/List_of_tectonic_plates#:~:text=Tectonic%20plates%20are%20pieces%20of,sial%20from%20silicon%20and%20aluminium)

#

**Major Earthquake Data**

- The earthquake intensity, darker color with larger diameter represents earthquakes with a higher magnitude.

<p align="center">
<img src="Images/Earthquakes_Challange_Major_Earthquakes.png" width="60%" height="60%">

</p>

<p align="center">
 <i> An interactive world map of Major Earthquake Data</i>
</p>

#

**Additional Map styles**
- Satellite view. 
- Dark view.

<p align="center">
 <img src="Images/Earthquakes_Challange_SatelliteView.png" width="40%" height="40%">

 
<img src="Images/Earthquakes_Challange_DarkView.png" width="40%" height="0%">
</p>

<p align="center">
<i>An interactive world map of earthquakes with Satellite View and Dark View</i>
</p>


## Resources

**Data Source:**

- GeoJson file for Tectonic Plates retrieved from GitHub repository: https://github.com/fraxen/tectonicplates/tree/master/GeoJSON
- GeoJson file for earthquakes for the past 7 days retrieved via API call from USGS website: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
- GeoJson file for Major Earthquakes (M4.5+) for the past 7 days via API call from USGS website: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

- **GeoJson** files that are specifically designed to host geographical information. GeoJson files are the industry standard for representing simple geographical features, such as points, linestrings and polygons and non-spatial attributes, such as magnitude of the earthquake, hurricane strength, hail size, elevation, etc.

**Software:**
- Mapbox API [challenge_logic.js](Earthquake_Challenge/static/js/challenge_logic.js)
    -  An open-source mapping platform for custom designed maps. 

- VS Code and Chrome Developer Tools


**Languages:**
- JavaScript, 
- [HTML](Earthquake_Challenge/index.html) and [CSS](Earthquake_Challenge/static/css/style.css) 

**Libraries:**
- D3
- Leaflet
    - A JavaScript library, designed to build the web mapping applications.
