# Week 3 Studio
This repository contains my completed week 3 studio assignment with 3 outputs. These outputs document further experimentation with Mapbox GL JS and can be viewed on the [project page](https://spikeroot.github.io/studio-week3_TB/). All data used is included in this repository in GeoJSON format.

## Output 1
This page contains a choropleth map displaying population density across the US, created following a [Mapbox tutorial](https://docs.mapbox.com/help/tutorials/choropleth-studio-gl-pt-1/).  Interactive features were added so that the density values of states are displayed as they are moused over. A custom Mapbox style was used to symbolize the data. The CSS style for the webpage was designed to match this output.

## Output 2
This page contains another custom Mapbox map, used for further experimentation with various features. Features include popups, flyover effects, geolocation, and user location. 

I stylized the popup to better blend with the map and page styles and used the custom Mapbox style created for the previous studio. I also modified the flyover effect values slightly.

## Output 3
This output was the result of a Mapbox tutorial in the use of [Turf JS](https://docs.mapbox.com/help/tutorials/analysis-with-turf/) for web-based data analysis. It loads two sets of location data, hospitals and libraries, in GeoJSON format and displays them on Mapbox tiles. It also creates popups identifying the name of each feature on mouseover. 

When a library feature is clicked, it uses Turf JS to identify the nearest hospital feature and highlight it with a blue circle.

I further stylized all features to match the site and map style, and used a custom Mapbox style modified from the one used in output 2.
