# Global GDP per Capita (2023)

**Author:** Lauren Brannan  
**Course:** GHY 4818 – Web Mapping  
**Date:** October 2025  

## Purpose
This project shows estimated GDP per capita (in U.S. dollars) for countries around the world in 2023. The goal was to make an interactive web map that lets users compare economic levels between countries and see overall global patterns.

## Data & Method
The data came from **Our World in Data (2023)**. I filtered and cleaned the spreadsheet in Excel, then joined it with a countries GeoJSON layer in QGIS. After exporting the joined file as `data.geojson`, I used Leaflet to visualize it on the web with the CartoDB Voyager basemap.

## Symbolization & Design
A blue color scale was used to show GDP per capita values—darker blues mean higher income and lighter blues mean lower income. Countries without data are colored tan so they stand out clearly. The map includes a title, description, legend, and sources.

## Reflection
Working on this map helped me understand how QGIS and Leaflet connect and how small style choices change the final product. Getting the legend and colors right took some trial and error, but worked out. I learned a lot about troubleshooting and about how to publish a map on GitHub Pages.
