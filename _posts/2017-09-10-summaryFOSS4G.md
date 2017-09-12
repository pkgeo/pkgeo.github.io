---
layout: post
title: FOSS4G - Boston, August 2017
subtitle: Summary notes and highlights from the conference
---
<div><font style="font-size: 19px

;">Conference August 14 - 18, 2017 Boston, MA</font></div><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;">Conference by number</font></div><div><font style="font-size: 19px


;">1,100 attendees</font></div><div><font style="font-size: 19px


;">250 talks/sessions</font></div><div><font style="font-size: 19px


;">56 workshops - two days.</font></div><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;">I attended 4 separate workshops for two days and attended 24 talk sessions for three days. Below are my summary notes. Highlight of the conference were keynotes from Paul Ramsey and Joe Cheng  </font></div><div><font style="font-size: 19px


;"><br/></font></div><div><b><font style="font-size: 19px


;">Workshop</font></b></div><ol>
<li><font style="font-size: 19px


;">Browser-based Geoprocessing with Turf.js and leaflet

</font></li><ul>
<li><font style="font-size: 19px


;"><a href="http://turfjs.org/getting-started/">turf.js</a> client-side geoprocessing using turf.js library and integrating with leaflet.js library to build webmap browser based simple geoprocessing application.  </font></li>
</ul>
<li><font style="font-size: 19px


;">Classification of remote sensing images with the Orfeo ToolBox and QGIS

</font></li><ul>
<li><font style="font-size: 19px


;"><a href="https://www.orfeo-toolbox.org/start/">Orfeo is image processing</a> application that can operate as standalone desktop application or use within QGIS desktop</font></li>
</ul>
<li><font style="font-size: 19px


;">From <a href="https://www.webodm.org/">WebODM</a> to QGIS

</font></li><ul>
<li><font style="font-size: 19px


;">Open source Sfm software with web interface based on OpenCV algorithem. Software can take images taken from drone and process to develop cloud points and orthomoasic photos to 3D model. </font></li>
</ul>
<li><font style="font-size: 19px


;">Processing Lidar and UAV point cloud in <a href="https://grass.osgeo.org/">GRASS GIS

</a></font></li><ul>
<li><font style="font-size: 19px


;">Exploring capabilities of GRASS GIS 7.2 lidar point cloud data processing.</font></li>
</ul>
</ol><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><br/></font></div><div><b><font style="font-size: 19px


;">Conference Sessions:</font></b></div><div><b><font style="font-size: 19px


;"><br/></font></b></div><div><font style="font-size: 19px


;"><i>Leveraging Open Source software to build data/mapping tools in local government</i> - <a href="http://chriswhong.com/">Chris Whong</a> <a href="https://github.com/nycplanning">NYC Planing Lab</a></font></div><div style="margin-left: 2em">
<ul>
<li><font style="font-size: 19px


;">Talked about using various open source to build tool and <a href="https://capitalplanning.nyc.gov/facilities">applications</a></font></li>
<li><font style="font-size: 19px


;">using AuthO, turf.js Cartoserver, mapbox-gl, React, Digital Ocean.</font></li>
<li><font style="font-size: 19px


;">Lesson learned - use existing tools (no customized design/development) bootstrap, eliminate dependencies of large software </font></li>
<li><font style="font-size: 19px


;">build modular (example of <a href="https://github.com/NYCPlanning/jane-maps">Jane maps</a>, name after Jane Jacobs) </font></li>
</ul>
</div><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><i>Why your map sucks and you don't even know it</i> - Will Cadell, <a href="http://www.sparkgeo.com/">Sparkgeo.com</a> </font></div><ul>
<li><font style="font-size: 19px


;">Map analytic company that analyzed 15 million user session. </font></li>
<li><font style="font-size: 19px


;">Results: 25% of users don't touch the map, once it's loaded, user doesn't move around</font></li>
<li><font style="font-size: 19px


;">Double loaded (multiple times) caused by bad coding</font></li>
<li><font style="font-size: 19px


;">10% of activities happens at very first 1% of the duration</font></li>
<li><font style="font-size: 19px


;">Need to tell the "INTENT" of the story very quickly</font></li>
<li><font style="font-size: 19px


;">Most users do not click to explore the map but pan continously </font></li>
</ul><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><i>Let them expire! - One company's experience with fewer proprietary software licenses</i> - Paul Wickman <a href="http://www.respec.com/solution/geospatial-software-analysis/">GIS technology Director RESPEC</a></font></div><ul>
<li><font style="font-size: 19px


;">Using QGIS to them was NOT alternative to Arc but other option</font></li>
<li><font style="font-size: 19px


;">Open Source option is not just free but means value</font></li>
<li><font style="font-size: 19px


;">"Price is what you pay, Value is what you get"</font></li>
<li><font style="font-size: 19px


;">Reasons for migrations</font></li>

<ul>
<li><font style="font-size: 19px


;">Per user scale model won't work for current ESRI licensing model</font></li>
<li><font style="font-size: 19px


;">It's about business with value and felt that ArcGIS value has dimished in value</font></li>
<li><font style="font-size: 19px


;">Look for value not ideology and need to thought out the plan.  "I don't need the drill, just a hole"</font></li></ul></ul><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><i>An Introduction to containerizing geospatial apps with Docker</i> - James Milner, <a href="http://3drepo.org/">3D Repo</a></font></div><ul>
<li><font style="font-size: 19px


;">Docker container is encapulated environment which runs application.<a href="https://docs.docker.com/get-started/">https://docs.docker.com/get-started/</a></font></li>
<li><font style="font-size: 19px


;">Docker eliminate "It works FINE in my machine but NOT yours" issue. Get rid of dependency issue.</font></li>
<li><font style="font-size: 19px


;">Docker Container vs VM (virtual machine)</font></li>

<ul>
<li><font style="font-size: 19px


;">VM isolates everything (no OS access) but Docker container use native OS. </font></li>
<li><font style="font-size: 19px


;">Docker container means running docker images.</font></li></ul><li><font style="font-size: 19px


;">By not having to load OS separately (not like VM), you don’t lose efficiency. </font></li><li><font style="font-size: 19px


;">One can use docker image to load Geoserver + Postgis i.e. from Docker Hub <a href="https://hub.docker.com/r/crcsi/geoserver-postgis/">https://hub.docker.com/r/crcsi/geoserver-postgis/</a></font></li>

</ul><div><b><font style="font-size: 19px


;"><br/></font></b></div><div><font style="font-size: 19px


;"><i>Offline First Mapping </i>- Calvin Metcalf, <a href="https://www.appgeo.com/mapgeo/">AppGeo</a></font></div><div><ul><li><font style="font-size: 19px


;">Using <a href="https://github.com/w3c/ServiceWorker/blob/master/explainer.md">Web Service Worker</a>, this can intercept http request and can save the map tile locally. </font></li><li><font style="font-size: 19px


;">It is browser based script that runs in the background, separate from a web page</font></li><li><font style="font-size: 19px


;">Service workers can periodic background sync &amp; push notifications that normally require native application but can do them through the browser. </font></li><li><font style="font-size: 19px


;">Service workers currently only support Chrome and Firefox browsers.</font></li><li><font style="font-size: 19px


;">Here is a good introductory implementation of this technology in <a href="https://www.captechconsulting.com/blogs/my-experience-using-service-workers">blog writeup </a></font></li></ul></div><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><i>Advanced geospatial technologies: The new powerful GRASS GIS 7.2 release </i>- Helena Mitasova, NC State University.</font></div><div><ul><li><font style="font-size: 19px


;">Not your old GRSS (Geographic Resources Analysis Support System)  from Army Corps of Engineering days, Fascinating story of <a href="https://youtu.be/cZia3ShzTWM">GRASS GIS told by William Shatner</a> back in 1987.</font></li><li><font style="font-size: 19px


;">Lot of new features and capabilities including raster/vector data analysis, cartographic tools, image processing, advance LIDAR processing tools and many more with <a href="https://grass.osgeo.org/">latest version of GRASS GIS</a>.</font></li></ul></div><div><font style="font-size: 19px


;"><br/></font></div><div><b><font style="font-size: 19px


;"><br/></font></b></div><div><font style="font-size: 19px


;"><i><a href="https://www.rstudio.com/">R-Studio</a>:  Coding as first resort</i> - Joe Cheng (CTO of RStudio)</font></div><div><ul><li><font style="font-size: 19px


;">Most folks use coding as last resort after using GUI but speaker showed why it should be other way around. </font></li><li><font style="font-size: 19px


;">GUI - developed design by developer/designer</font></li><li><font style="font-size: 19px


;">CLI - task directed by user themselves</font></li><li><font style="font-size: 19px


;">Use code to extend functionality of existing such as QGIS to repeat and to scale. </font></li><li><font style="font-size: 19px


;">Main benefit of using code </font></li><ul><li><font style="font-size: 19px


;">Concise</font></li><li><font style="font-size: 19px


;">Highly interactive ( inform, return results after each line of code)</font></li><li><font style="font-size: 19px


;">Fast iteration</font></li></ul><li><font style="font-size: 19px


;">R - <a href="https://en.wikipedia.org/wiki/R_(programming_language)">John Chamber originator</a>  is to give user ability to interact and explore data. This programming language is heavily based on statistics and visualization. </font></li><li><font style="font-size: 19px


;">R Studio contains many tools, map + text + graphic/table + narrative to compose data to tell story. </font></li><li><font style="font-size: 19px


;"><a href="https://www.rstudio.com/products/shiny/">Shiny</a> - can generate fully interactive web map using R studio.</font></li><li><font style="font-size: 19px


;"><a href="http://rmarkdown.rstudio.com/lesson-1.html">R Markdown</a> - framework to crate html, report/PDF and dashboard. </font></li></ul><div><font style="font-size: 19px


;"><br/></font></div></div><div><font style="font-size: 19px


;"><i>DIY Mapping with drones and open source in a humanitarian context</i> - Dan Joseph, American Red Cross</font></div><div><ul><li><font style="font-size: 19px


;">Many reasons for DIY drone instead of commercial, off-the-shelf product.</font></li><ul><li><font style="font-size: 19px


;">Fix your own machine out in the field</font></li><li><font style="font-size: 19px


;">Ability to access parts locally</font></li><li><font style="font-size: 19px


;">Lower cost</font></li></ul><li><font style="font-size: 19px


;">Workflow as following </font></li><ol><li><font style="font-size: 19px


;">Using DIY drone map to collect information </font></li><li><font style="font-size: 19px


;">then to process using <a href="http://opendronemap.org/">OpenDroneMap</a> to stich images together then share them through <a href="http://openaerialmap.org/about/">Open Aerial Map</a> which then can be </font></li><li><font style="font-size: 19px


;">used in <a href="http://wiki.openstreetmap.org/wiki/ID">iD Editor to update OpenStreetMap</a> database for everyone to use. </font></li></ol></ul></div><div><b><font style="font-size: 19px


;"><br/></font></b></div><div><font style="font-size: 19px


;"><i>LiveDroneMap - an Automatic Real-time UAV mapping solution </i>- Janwoo Cheon, Seoul University, South Korea.</font></div><div><ul><li><font style="font-size: 19px


;">Real-time drone imagery data being captured and process in real-time data to get result back instantly. </font></li><li><font style="font-size: 19px


;">Live data processing to get instant on-the ground event evaluation without long-lag data processing  time. </font></li></ul><div><font style="font-size: 19px


;"><br/></font></div></div><div><font style="font-size: 19px


;"><i>Data Driven Style (DDS) for fast GL maps</i> - Molly Lloyd, Mapbox</font></div><div><ul><li><font style="font-size: 19px


;">Using <a href="https://en.wikipedia.org/wiki/OpenGL">OpenGL</a> (open graphic library) and <a href="https://en.wikipedia.org/wiki/WebGL">WebGL</a>, one can style using JSON file to stylize map features. </font></li><li><font style="font-size: 19px


;">Mapbox using these two technologies to use in their <a href="https://blog.mapbox.com/introducing-data-driven-styling-in-mapbox-gl-js-f273121143c3">Mapbox GL-JS as styling using JSON data file</a> for their vector tile styling web map. </font></li></ul><div><font style="font-size: 19px


;"><br/></font></div></div><div><font style="font-size: 19px


;"><i>Mapbox GL: How vector maps work</i> - Vladimir Agafonkin, Mapbox</font></div><div><ul><li><font style="font-size: 19px


;">Original creator of <a href="http://leafletjs.com/">Leaflet</a> talked about inner workings of vector tile. </font></li><li><font style="font-size: 19px


;">He said that the new era of cartography is here.</font></li><ul><li><font style="font-size: 19px


;"><a href="https://en.wikipedia.org/wiki/Tiled_web_map">Raster tile </a>era lasted about 30 years which talks to server to get the information</font></li><li><font style="font-size: 19px


;"><a href="https://blog.mapbox.com/mapbox-streets-and-terrain-now-follow-vector-tile-specification-version-2-4842883813e0">Vector map</a> era is here that leverages client side, using web browser to display web map. </font></li><li><font style="font-size: 19px


;">Currently there are 94.8% coverage of WebGL/OpenGL in US and 91.5% for the world. </font></li><li><font style="font-size: 19px


;">OpenGL renders triangle (<a href="https://github.com/mapbox/earcut">Earcut</a>) to display various features </font></li></ul></ul></div><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><i>Migrating to Vector Tiles </i>-Lizzi Silvinski, <a href="http://www.nbtsolutions.com/">NBT Solutions</a>. </font></div><div><ul><li><font style="font-size: 19px


;">Talked about integrating vector tile into existing raster tile system. </font></li><li><font style="font-size: 19px


;">Goals for the project </font></li><ul><li><font style="font-size: 19px


;">Dynmaic styling</font></li><li><font style="font-size: 19px


;">GIS functionality </font></li><li><font style="font-size: 19px


;">Editing tools</font></li></ul><li><font style="font-size: 19px


;"> Proof-of-Concept in <a href="https://github.com/eSlivinski/migrating2VectorTiles">github here</a>. </font></li><li><font style="font-size: 19px


;">Using leaftlet draw to edit in vectortile </font></li><li><font style="font-size: 19px


;">Wrote own node.js to serve tiles. </font></li></ul></div><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><i>State of QGIS </i>- Kurt Menke, Larry Shaffer</font></div><div><ul><li><font style="font-size: 19px


;">Various features coming up QGIS 3.0 </font></li><li><font style="font-size: 19px


;">Major feature of having meta data catalog </font></li><li><font style="font-size: 19px


;">Improve digitizing </font></li><li><font style="font-size: 19px


;">Composer is completely rewritten and single layout with multiple pages</font></li><li><font style="font-size: 19px


;">Summary from <a href="http://www.digital-geography.com/short-announcement-qgis-3-0-is-on-its-way/">blog post</a> </font></li></ul></div><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><i>Vector tiles from OpenStreetMap with OpenMapTiles and TileServer GL</i> - <a href="https://www.klokantech.com/company/">Petr Pridal, Klokan Technologies GmbH</a></font></div><div><ul><li><font style="font-size: 19px


;">Provide various vector tile format for numerous data products and web map serving options.</font></li><li><font style="font-size: 19px


;">OpenStreetMap data in vector tile format <a href="https://openmaptiles.com/downloads/?_ga=2.212714644.1420134845.1504711765-1653973473.1502573542">available by various region</a></font></li><ul><li><font style="font-size: 19px


;">Whole planet data vector ~ 54 GB</font></li><li><font style="font-size: 19px


;">West Coast ~ 1.9 GB</font></li><li><font style="font-size: 19px


;">Washington State ~ 205 MB</font></li><li><font style="font-size: 19px


;">Also can extract <a href="https://openmaptiles.com/extracts/">customized area </a></font></li></ul><li><font style="font-size: 19px


;">Hillshade and contour lines are also <a href="https://openmaptiles.com/">available for download</a></font></li><li><font style="font-size: 19px


;">Workflow is to download OSM vector tile and serve using either <a href="https://openmaptiles.com/server/">OpenMapTIles Mapserver of docker image</a> or use  <a href="https://github.com/klokantech/tileserver-gl">Tileserver-GL</a> locally</font></li><li><font style="font-size: 19px


;"><a href="https://openmaptiles.com/satellite/">Downloadable cloudless satellite photo</a> - 250 GB, 20m pixel resolution with zoom 13 level. </font></li></ul></div><div><font style="font-size: 19px


;"><br/></font></div><div><font style="font-size: 19px


;"><i>Using open-source tools and high-resolution geospatial data to estimate landscapes’ visual attributes</i> - Helena Mitasova, Anna Petrasova, NC State University.</font></div><div><ul><li><font style="font-size: 19px


;">Using <a href="https://www.nrcs.usda.gov/Internet/FSE_DOCUMENTS/nrcs142p2_051510.pdf">Geomorphons </a> - model based using machine/computer vision to interpret topology. </font></li></ul><div><font style="font-size: 19px


;"><br/></font></div></div><div><font style="font-size: 19px


;"><i>Coupling a geospatial <a href="https://tangible-landscape.github.io/">Tangible User Interface</a> (TUI) and an Immersive Virtual Environment (IVE) using open-source geospatial and 3D modeling tools</i> - Helena Mitasova, Anna Petrasova, NC State University. </font></div><div><font style="font-size: 19px


;"></font></div><div><font style="font-size: 19px


;"></font></div><div><ul><li><font style="font-size: 19px


;">System of software (GRASS GIS) and various hardware to do the analysis of natural environment planning and analysis. </font></li><li><font style="font-size: 19px


;">Background information <a href="https://geospatial.ncsu.edu/osgeorel/tangible-landscape.html">here</a> which was developed in NC State University OSGeo Research and Education laboratory.</font></li><li><font style="font-size: 19px


;">Great tools/use case  to apply in environmental analysis and modeling. </font></li></ul></div><div><br/></div>
