# Final_Project2
Contains new data, with shapefiles unprojected (GCS_WGS_1984)

## Goal

GES 778 Final Project The goal is to be able to display this project on my website at nohemivoglozin.wix.com/nohemi-voglozin It will be about the genetic diversity of rice varieties in two ecogeographic regions in BENIN, West Africa, and how that genetic diversity is correlated:

- to the management and decisions that farmers make on their fields on a daily basis, and
- to environmental variables such as rainall, elevation, temperature, etc. 

It will also display some touristic characteristics of the country and some points of interests that are definitely worth checking out while visiting or travelling through the country.

### Documentation

* Attribution 
    * * The shapefiles were created as part of my doctoral program (more info here: http://nohemivoglozin.wixsite.com/nohemi-voglozin/projects), except for the national parks and the cynegetic zones. These shapefiles 
    were created as part of a personal project that I wanted to do to develop a touristic map for the country and showcase the different attractions.
* Extremely brief description of all pre-processing
    * Shapefiles converted to GeoJSON by instructor: https://github.com/umbcvis/projects/tree/master/nohevog1
    * To be able to overlay them with the basemap, the shapefiles, which were in the WGS_1984_UTM_Zone_31N projection, had to be unprojected in WGS_1984 (Lat, Lon).
    * Shapefiles also converted to GeoJSON by Nohemi V. using ogre.adc4gis.com: https://github.com/nohevog1/Classes
    * The shapefiles were modified in ArcMAP 10.3 to add 2 fields to hold the links for the images and the urls for the "more info"
    * Most of the pictures are personal pictures acquired throughout my studies and my time in the field, but some pictures like the logo of the 2 parks were taken from the internet. 
    
#### Final Project Final Version

The project ended up being more of a touristic map of BENIN. The map is an overlay of 9 different layers. The map shows national parks, cynegetic zones, the 12 departments of the country, but also some data about my doctoral research such as the communes or subdivisions in the North and the South of the country as well as the different villages in which I conducted my doctoral field research. 
For more information on my doctoral research, please visit: http://nohemivoglozin.wixsite.com/nohemi-voglozin/projects.

The map allows the user to add or remove some layers, and when the user hover on the villages, the names are displayed as an info, and on the other layers, pictures representing a particularity of the region is shown along with the name of the feature.

FINAL PROJECT GIST: https://gist.github.com/nohevog1/7e9f3a0a170cd644cbd020f94ba9aa39

FINAL PROJECT DEMO: http://bl.ocks.org/nohevog1/raw/d978718d7bb6f7479dbe7a00c2db1eaf/
