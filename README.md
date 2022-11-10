# MentalHealth_Trails
Bivariate map illustrating mental health cases per 100,000 people and trailheads.

### Mental Health and Trail Access in North Carolina


#### This bivariate map illustrates mental heath emergency department visits per 100,000 people. Mental Heath ED visits are presented for each ZIP Code in North Carolina. 

#### I created this map in HTML, JavaScript and CSS, utilizing Leaflet and JQuery libraries in Atom. To create the map, leaflet functions were very helpful, including L.map to create my map, L.tileLayer to add my basemap and L.geoJSON to retrieve my geoJSON files. Map icons are from [Font Awesome](https://fontawesome.com/). If statements were used to add my hiking icons, using the 'pointToLayer' function and if statements were also used to set the choropleth colors for the mental health data. To create additional interactions, I used 'onEachFeature' and 'bindPopUp' to indicate each trails distance in kilometers. 

#### The trail data is from the [Trust for Public Land's](https://www.tpl.org/parkserve/downloads) dataset. I converted the trail and mental health data to a GeoJSON file using QGIS and [geojson.io](https://geojson.io/#map=2/20.0/0.0). Text color in the description box was styled using css in the main.css file. All other styling was coded in the index.html file.

