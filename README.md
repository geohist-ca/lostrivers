# lostrivers
<strong>Canadian Historical GIS Partnership repository for Lost Rivers of Toronto project.</strong>

The Canadian Historical GIS Partnership Development project is developing web-mapping pilot projects for several collaborating organizations, using a variety of data sets. For more information see project website at www.geohist.ca. <br>
This repository holds code for the Open Source versions of the pilot projects for the Lost Rivers of Toronto organization, for more information see their website at www.lostrivers.ca <br>
The first web-mapping pilot project is the Disappearing Rivers of Toronto. This map uses a time-line slider to display changes in the river network of Toronto over time as streams were buried between 1802 and 1950, to make way for the course of urban development. This web-map was developed using Leaflet and the Time slider was adapted from the generic jQueryUI slider: https://api.jqueryui.com/slider/#option-range by using the Leaflet geojson filter option: http://leafletjs.com/reference-1.0.2.html#geojson-filter. GeoJSON files were generated for the overlay of rivers, and Boundless/Geoserver was used to serve base mapping. <br>
The second web-mapping pilot project is a series of maps depicting three of the walking tours conducted by Lost Rivers of Toronto along the routes of buried river courses, in the Ashbridge's Bay area of Toronto. These web-maps were developed using Leaflet, adapting the leaflet-storymap template mounted on github by Jack Dougherty https://github.com/jackdougherty/leaflet-storymap. <br>

The project web-maps can be seen here: http://mercator.geog.utoronto.ca/georia/lostrivers/ <br>
The code is available in the repository: https://github.com/geohist-ca/lostrivers/tree/master/leaflet-storymap-github

For convenience, the code for different features developed for this project is also broken out into "template" files, also included in the repository:<br>
<strong>Layer Filter Slider:</strong> Code used to filter a .GeoJSON layer using a jQuery slider (Template_FilterSlider.html)<br>
<strong>Opacity Slider:</strong> Code used to change opacity of raster layers generated by Qtiles (Template_OpacitySlider.html)<br>
<strong>Story Map:</strong> Basic story template code using one GeoJSON point layer to display point locations on map and attribute contents in scrollable side panel (Template_Storymap.html)<br>

Documents outlining the development of the files can be found on the project website: <br>
http://geohist.ca/wp-content/uploads/2017/10/LostRivers_Disappearing_Rivers_Devt_OS.pdf <br>
http://geohist.ca/wp-content/uploads/2017/10/LostRivers_Ashbridges_Maptour_Devt_OS.pdf <br>
