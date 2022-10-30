# Web cartography, GIS, and mapping design resources <!-- omit in toc -->

Over the years, I have been collecting a list of my go-to resources for cartography and web design, including everything from selecting colors to finding data to helpful tutorials (though this list is by no means comprehensive). Feel free to submit a pull request or email me at tolomaps@gmail.com if you have suggestions of resources to add to this list or notice that something is outdated.

# Table of Contents <!-- omit in toc -->

- [General mapping](#general-mapping)
- [Web mapping](#web-mapping)
- [Basemaps and Vector Tiles](#basemaps-and-vector-tiles)
- [Mapping frameworks and templates](#mapping-frameworks-and-templates)
- [Routing](#routing)
- [Color](#color)
- [Typography](#typography)
- [Software](#software)
- [Databases](#databases)
- [Data Sources](#data-sources)
- [Data wrangling, transformation, and manipulation](#data-wrangling-transformation-and-manipulation)
- [Data scraping](#data-scraping)
- [Textures / Patterns](#textures--patterns)
- [Images](#images)
- [Icons](#icons)
- [Geocoding](#geocoding)
- [Projections](#projections)
- [Tutorials / Guides / Forums](#tutorials--guides--forums)
- [Blogs](#blogs)
- [Conversion tools](#conversion-tools)
- [Site generators](#site-generators)
- [Hosting](#hosting)
- [WYSIWYG mapping](#wysiwyg-mapping)
- [SQL](#sql)
- [Git](#git)
- [Raster](#raster)
- [UI/UX](#uiux)
- [Miscellaneous](#miscellaneous)
- [Tutorials](#tutorials)

---

## General mapping

- [Cartography Guide](http://www.axismaps.com/guide/): Axis Maps' amazing thematic cartography guide
- [OpenStreetMap](http://www.openstreetmap.org/ "OpenStreetMap"): Editable, open map of the world.
- [mapschool.io](http://mapschool.io/): Brief introduction to all things geo.
- [20 Unrequested Map Tips](http://uxblog.idvsolutions.com/2013/10/20-unrequested-map-tips-part-1.html "John Nelson's 20 Unrequested Map Tips part 1"): John Nelson's 20 map-making tips

## Web mapping

- [CartoDB](http://cartodb.com/ "CartoDB"): Create web maps easily. Especially useful for large datasets.
- [D3.js](http://d3js.org/ "D3"): A JavaScript library to create powerful online visualizations. Often used for web mapping.
  - [D3 Tips & Tricks](https://leanpub.com/D3-Tips-and-Tricks%20 "D3 Tips and Tricks"): Free, downloadable book on D3
  - [D3 Selection](http://northlandia.wordpress.com/2014/11/01/d3-selection-mysteries-solved/ "D3 Selection Mysteries Solved"): Understanding how D3 selections work
  - [Let's Make a Map!](https://bost.ocks.org/mike/map/): Introduction to making a basic map with D3, by Mike Bostock himself (the creator of D3).
- [Leaflet](http://leafletjs.com/ "Leaflet"): JavaScript library for making mobile-friendly, interactive web maps.
- [TurfJS](http://turfjs.org/ "TurfJS"): GIS for web maps
- [DropChop](http://dropchop.io/): In-browser application to perform basic GIS operations
- [awesome-spatial](https://github.com/RoboDonut/awesome-spatial): Links to various (awesome) GitHub repos that have some sort of spatial/geo/web mapping use
- [Leaflet providers](http://leaflet-extras.github.io/leaflet-providers/preview/): Previews free map tiles that you can use on your Leaflet map, with instructions on how to include it in your code.

## Basemaps and Vector Tiles

- [Mapbox](https://www.mapbox.com/maps/)
- [OpenMapTiles](https://openmaptiles.org/)
- [Thunderforest](https://thunderforest.com/docs/vector-maps-api/)

## Mapping frameworks and templates

- [Storymap.js](https://github.com/jakobzhao/storymap): a javascript library for storytelling with web maps, maintained by Cartography and Geovisualization Group at Oregon State University.
- [Storytelling](https://github.com/mapbox/storytelling): template designed by Mapbox to accelerate building out a "scrollytelling" map story using Mapbox styles and GL JS.

## Routing

- [GeoJSON Path Finder: Serverless, offline routing in the browser](http://www.liedman.net/geojson-path-finder/)
- [GraphHopper](https://www.graphhopper.com/)
- [Mapbox Directions API](https://www.mapbox.com/navigation/)
- [Project OSRM](http://project-osrm.org/)
- [Transitland](https://transit.land)

## Color

- [chroma.js](https://vis4.net/chromajs/)
- [Chroma.js Color Palette Helper](https://gka.github.io/palettes)
- [ColorBrewer](http://colorbrewer2.org/ "ColorBrewer"): Cartographer's go-to resource for selecting colors for thematic maps, especially choropleth maps. Can filter based on whether color scheme is optimized for printing, colorblindness, etc.
- [0to255](http://www.0to255.com/ "0to255"): One of my favorite color resources. Pick a color, and 0to255 will show you every shade of that color.
- [Adobe Color](https://color.adobe.com/ "Adobe Color"): Create your own color scheme, up to 5 colors. Explore others' color schemes.
- [Paletton](http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF "Paletton"): Create your own color scheme.
- [HEX to RGB Converter](http://hex.colorrrs.com/ "HEX to RGB Converter"): Convert between HEX and RGB color values. Super simple interface.
- [Selecting equidistant perceived colors](https://vis4.net/blog/posts/avoid-equidistant-hsv-colors/#more-3199 "How To Avoid Equidistant HSV Colors"): Great blog post and tool(s) to select colors that are evenly spaced, especially good for choropleth maps
- [i want hue](http://tools.medialab.sciences-po.fr/iwanthue/): Generate palettes of optimally distinct colors. This is great for making sure colors will look different enough on a map to distinguish colors.
- [D3 Curvy](http://www.macwright.org/d3-curvy/): Design your own color scheme for choropleth maps based on ColorBrewer.
- [ColorHexa](http://www.colorhexa.com/): Enter in a color value and get pretty much any information you would ever want about the color, including shades, tints, and tones of that color, as well as suggested color schemes that include that color. Also includes a color gradient generator, where you can type in the values of two colors and it will generate a gradient between those colors.
- [PaletteFX](http://palettefx.com/): Create a color scheme from an image that you upload.
- [Color Calculator](https://www.sessions.edu/color-calculator/): Choose an initial color, select the type of color scheme you're looking for, and get some ideas.
- [ColorClaim](http://www.vanschneider.com/colors/): A color picking site by Tobias van Schneider to help with picking color schemes. "All I do is collect my favorite color combinations on one big page. Usually these combinations are very subtle, one main and one accent color.";
- [simple colors](https://siimple.juanes.xyz/colors/): an elegant and minimalistic color palette. It provides a set of colors optimized to be used in UI projects.
- [color supply](https://colorsupplyyy.com/app)
- [A Bivariate Choropleth Palette Generator](https://geoviz.ceoas.oregonstate.edu/storymap/assets/color.html)

## Typography

- [Fontelico](http://fontello.com/)
- [DaFont](http://www.dafont.com/es/): Free, downloadable fonts.
- [FontSquirrel](http://www.fontsquirrel.com/): Free, downloadable fonts.
- [Google Fonts](http://www.google.com/webfonts): Free fonts that can be used for webpages.
- [TypeKit](https://typekit.com/fonts "Adobe TypeKit"): Download fonts specifically for using with Adobe's software suite
- [TypeBrewer](http://www.typebrewer.org/): Looks at different attributes of selecting typography for maps.
- [8 typography tips](http://inspire.adobe.com/2013/12/1/eight_tips_for_combining_typefaces.html?scid=social_20150220_40757606&adbid=568893177639219200&adbpl=tw&adbpr=23822236 "Typography Tips"): General typography tips from Adobe
- [Flipping Typical](http://flippingtypical.com/ "Flipping Typical"): Allows you to see and test out all of the fonts installed on your computer by typing in a specific phrase and showing you what it looks like in the various fonts
- [Top 30 free open-source web fonts](https://www.typewolf.com/open-source-web-fonts): Great collection of free fonts for download/web use

## Software

- [QGIS](http://www.qgis.org/en/site/ "QGIS"): Open-source desktop GIS software. Can do most of what ArcMap can do, for free. Often it does it much, much faster.
- [Mapbox](https://www.mapbox.com/ "Mapbox"): Use Mapbox online to design basemaps; Mapbox Studio is desktop software for designing map tiles that can be uploaded and hosted on Mapbox. Check out their [Getting Started Guides](https://www.mapbox.com/help/#get-started-with-mapbox "Mapbox Getting Started Guides") or [Help](https://www.mapbox.com/help/ "Mapbox Help") section for more information.
- [Indiemapper](http://indiemapper.io// "Indiemapper"): Make thematic maps online. Bring in your own or use provided data.
- [Map Stack by Stamen](http://mapstack.stamen.com/ "Map Stack by Stamen"): Create quick map snapshots of anywhere, with the ability to customize colors and which labels/lines to include.
- [HUGEpic](http://hugepic.io/ "HUGEpic"): Create a slippy map from an image. This can be used when you want to be able to pan and zoom on a static map.
- [Kosmtik](https://github.com/kosmtik/kosmtik): Open-source MBTiles software.
- [Pyramid Shader](http://www.terraincartography.com/PyramidShader/): An application for visualizing terrain data

## Databases

- [Why should you care about PostGIS? — A gentle introduction to spatial databases](https://medium.com/@tjukanov/why-should-you-care-about-postgis-a-gentle-introduction-to-spatial-databases-9eccd26bc42b)
- [DBeaver](https://github.com/dbeaver/dbeaver): Free multi-platform database tool for developers, SQL programmers, database administrators and analysts
- [qri: A new tool for data science](https://qri.io/desktop/):qri (“query”) is versioned, scriptable, exportable, collaborative datasets

## Data Sources

- [Urban Institute Data Catalog](https://datacatalog.urban.org/search/type/dataset): a place to discover, learn about, and download open data provided by Urban Institute researchers and data scientists.
- [Global Change Data Lab](https://global-change-data-lab.org/): on-profit research organization in the education sector.
- [Our World in Data](https://ourworldindata.org/): Research and data to make progress against the world’s largest problems
- [Public Data Sources](https://github.com/justmarkham/DAT5/blob/master/other/public_data.md): compiled by @justmarkham for DAT5
- [US National Historical GIS](https://www.nhgis.org/): DOWNLOAD U.S. CENSUS DATA TABLES & MAPPING FILES
- [Harvard dataverse](https://dataverse.harvard.edu/dataverse/harvard): Share, archive, and get credit for your data. Find and cite data across all research fields
- [Mapbox Traffic Data](https://docs.mapbox.com/traffic-data/overview/)
- [FEMA to Release a Flood of Insurance Data](https://www.nrdc.org/experts/anna-weber/fema-release-flood-insurance-data)
- [OSMaxx](https://osmaxx.hsr.ch/): Get the OpenStreetMap data you want in the file format you need
- [SOI Tax Stats - Migration Data](https://www.irs.gov/statistics/soi-tax-stats-migration-data)
- [Census Factfinder](http://factfinder.census.gov/): Download Census demographic data
- [Data.gov](http://www.data.gov/ "data.gov"): U.S. Government data
- [Diva-GIS](http://www.diva-gis.org/gdata "DIVA GIS data"): Basic datasets for many countries around the world. Administrative boundaries datasets may be more detailed than Natural Earth.
- [EarthWorks](https://earthworks.stanford.edu/ "EarthWorks"): Compilation of free GIS data from various universities; run by Stanford Libraries
- [Free GIS Data](http://freegisdata.rtwilson.com/#home "Free GIS Data from Robin Wilson"): A list of over 300 FREE data sources from around the world! Woo hoo!
- [GADM](http://gadm.org/ "Global Administrative Areas): GADM is a spatial database of the location of the world's administrative areas (or administrative boundaries"). Includes countries as well as lower level administrative boundaries.
- [GIS Data Repositories](https://docs.google.com/spreadsheet/ccc?key=0AuApi46szKw4dDhVM1dZNmpld3dIQWdRS2NnRkZDQWc&hl=en_US#gid=47 "GIS Data Repositories"): Google Doc compilation of free, downloadable datasets that may be useful in humanitarian response (and many other scenarios). Compiled by Karen Payne of the University of Georgia's Information Technologies Outreach services.
- [Libra](http://libra.developmentseed.org/ "Libra: Development Seed"): A browser for open Landsat 8 imagery.
- [Natural Earth](http://www.naturalearthdata.com/ "Natural Earth Data"): Public domain datasets available for the world. Includes political and physical features at various scales. You can easily get Natural Earth datasets as GeoJSONs from [geojson.xyz](http://geojson.xyz).
- [OpenStreetMap Data Extracts](http://download.geofabrik.de/ "OpenStreetMap Data Extracts"): Download the latest data from OpenStreetMap, by continent/country.
- [Overpass Turbo](http://overpass-turbo.eu/ "Overpass Turbo"): Make queries for specific downloads from OpenStreetMap (for example, if you just want a certain type of road in a certain area, but not every type of data in that area).
- [Viewfinder Panoramas](http://www.viewfinderpanoramas.org/dem3.html "Viewfinder Panoramas DEM"): Best publicly-available DEMs, according to Daniel Huffman
- [World Bank Data](http://data.worldbank.org/ "World Bank Data"): Free and open access to development data
- [U.S. Cartographic Boundary Shapefiles](https://www.census.gov/geo/maps-data/data/tiger-cart-boundary.html "Cartographic Boundary Shapefiles"): These are what you should use if you want to show coastline on your map. If you download the regular TIGER shapefiles from the U.S. Census, they'll give you the technical boundaries but will look weird because boundaries for counties/states extend into the ocean.
- [World Population data](http://www.worldpop.org.uk/data/): 100m resolution raster population for many parts of the world
- [30 data sources](http://flowingdata.com/2009/10/01/30-resources-to-find-the-data-you-need/ "30 resources to find the data you need"): Data tips from FlowingData. [See also, this](http://flowingdata.com/2015/05/06/how-to-ask-for-datasets/ "How to ask for datasets").
- [OpenStreetMap administrative boundaries](https://mapzen.com/data/borders): Free administrative boundary downloads from OpenStreetMap data, provided by Mapzen and updated monthly
- [College Scorecard](https://collegescorecard.ed.gov/data/): U.S. government data on colleges
- [CAIT Climate Data](http://cait.wri.org/): One of the most trusted sources of climate data, from the World Resources Institute. Includes historical data, visualizations, and data downloads.
- [U.S. Census of Agriculture](http://www.agcensus.usda.gov/): Leading source of information on agriculture in the U.S.
- [U.S. Department of Transportation](http://catalog.data.gov/organization/dot-gov): Download data on everything to do with transportation in the U.S.: airports, various road networks, U.S. Army Corps of Engineers waterways, national bridge inventory, fatality analysis from drunk driving crashes, etc.
- [U.S. Hydropower datasets](http://nhaap.ornl.gov/content/nhaap-data-sources): Various datasets from the National Hydropower Asset Assessment Program on hydropower in the U.S.
- Elevation data: From Paolo Raposo's 2015 NACIS talk: [USGS National Map](http://viewer.nationalmap.gov/viewer/), [Earth Explorer](http://earthexplorer.usgs.gov/), [GDEM](http://gdem.ersdac.jspacesystems.or.jp/)
- [National Historic GIS](https://nhgis.org/): Free census data and historic boundary files for the U.S. since 1790
- [Open Terrain Data](https://github.com/openterrain/openterrain/wiki/Terrain-Data): A list of where to get worldwide open terrain data.
- [Open Geoportal](http://data.opengeoportal.org/): A &#8220;collaboratively developed, open source, federated web application to rapidly discover, preview, and retrieve geospatial data from multiple repositories&#8221;
- [Download elevation data](http://dwtkns.com/srtm30m/): Awesome/easy interface to download 30-m resolution elevation data
- [GLOVIS](http://glovis.usgs.gov): Can be used to download U.S. government satellite imagery. Beware: requires Java in your browser. It's not a great interface, but possible to get lots of data, including historic imagery.
- [OECD](http://stats.oecd.org/): Data from the Organisation for Economic Co-operation and Development; not necessarily in readily available geographic format, but lots of data by member countries.
- [U.S. Homeland Security data](https://hifld-dhs-gii.opendata.arcgis.com/): A portal of a wide variety of datasets, including everything from agriculture to education to energy to law enforcement to transportation and more.
- [Gapminder](http://www.gapminder.org/data/): Database of world demographic and economic data.
- [OpenAQ](https://openaq.org/#/sources): The most comprehensive compilation of datasets I've seen on air quality around the world. Can access data either through download or API.
- [Top 10 data sources for international development](http://www.theguardian.com/global-development-professionals-network/2016/mar/16/the-top-10-sources-of-data-for-international-development-research): According to The Guardian
- [10 Free GIS Data Sources: Best Global Raster and Vector Datasets (2017)](http://gisgeography.com/best-free-gis-data-sources-raster-vector/)
- [Free Spatial Data from DIVA-GIS](http://www.diva-gis.org/Data)
- [WorldClim Version2](http://worldclim.org/version2)
- [GADM database of Global Administrative Areas](http://gadm.org/)
- [HindustanTimesLabs/shapefiles](https://github.com/HindustanTimesLabs/shapefiles/tree/master/state_ut)
- [U.S. GEOGRAPHIC SUMMARY DATA AND BOUNDARY FILES](https://www.nhgis.org/) (National Historic GIS data)
- [Bridging data for census tracks across time](https://s4.ad.brown.edu/projects/diversity/Researcher/ltdb.htm)
- [Comprehensive list of 2600+ Open Data Portals Around the World](https://www.opendatasoft.com/a-comprehensive-list-of-all-open-data-portals-around-the-world/)
- [NextGIS](https://data.nextgis.com)
- [The United States Wind Turbine Database (USWTDB)](https://eerscmap.usgs.gov/uswtdb/)
- [HERE Student Sample Data](https://go.engage.here.com/student-sample-data.html)
- [Our World In Data](https://ourworldindata.org)
- [Public APIs](https://github.com/toddmotto/public-apis)
- [Open Data Network](https://www.opendatanetwork.com/)
- [Discovery API](https://socratadiscovery.docs.apiary.io/#)
- [Public APIs](https://github.com/toddmotto/public-apis) (A collective list of free APIs for use in software and web development.)
- - [Stanford Open Policing Project](https://openpolicing.stanford.edu/)
- [CARTO's LOCATING GEOSPATIAL AND MAPPABLE DATA](https://carto.com/docs/tips-and-tricks/mappable-data/)
- [Inside AirBNB](http://insideairbnb.com/get-the-data.html)
- [Awesome Datascience data sets](https://github.com/justmarkham/awesome-datascience#data-sets)
- [US City Open Data Census](http://us-city.census.okfn.org/)
- [College Scorecard Data](https://collegescorecard.ed.gov/data/)
- [Homeland Infrastructure Foundation-Level Data (HIFLD)](https://hifld-geoplatform.opendata.arcgis.com/)
- [Hydroshare](https://www.hydroshare.org/)
- [European Data Portal](https://www.europeandataportal.eu/nl/)
- [Programmable Web Search APIs](https://www.programmableweb.com/apis/directory)

## Data wrangling, transformation, and manipulation

- [Jeezy](https://github.com/harrystevens/jeezy): a JavaScript library for manipulating data. It provides lots of useful functions and has no dependencies, so it won't add a lot of code to your project.
- [AddFIPS](https://github.com/fitnr/addfips)
  : AddFIPS is a tool for adding state or county FIPS codes to files that contain just the names of those geographies.

## Data scraping

- [All the Places](https://globaleclipse.com/): A project to extract GeoJSON from the web focusing on websites that have 'store locator' pages.

## Textures / Patterns

- [Subtle Patterns](http://subtlepatterns.com/ "Subtle Patterns")
- [Lost & Taken](http://lostandtaken.com/ "Lost & Taken")
- [55 seamless, subtle grunge patterns](https://creativemarket.com/liammckay/258119-55-Seamless-Subtle-Grunge-Patterns?u=liammckay&utm_source=Link&utm_medium=CM+Social+Share&utm_campaign=Product+Social+Share&utm_content=55+Seamless+Subtle+Grunge+Patterns+~+Patterns+on+Creative+Market)
- [Geopattern](http://btmills.github.io/geopattern/)
- [Pattern Fills](http://iros.github.io/patternfills/)
- [Hero Patterns (repeatable SVG backgrounds)](http://www.heropatterns.com/)

## Images

- [Placeholder](https://placeholder.com/): API for querying images of various sizes with custom text and colors. Good for mockups of layout

## Icons

- [Streamline 3.0 Icons](https://streamlineicons.com/free/)
- [Hero Icons](http://www.heroicons.com/)
- [Nounproject](http://thenounproject.com/4/): Creative Commons license icons. Can either pay to use them without attribution, or give attribution to the creator.
- [Maki](http://mapbox.com/maki/): Open-source icons developed by Mapbox for cartographic uses.
- [Font Awesome](http://fontawesome.io/icons/ "Font Awesome Icons"): Scalable vector icons specifically designed for web use.
- [Ionicons](http://ionicons.com/ "Ionicons"): Icon font.
- [Ikonate](https://www.ikonate.com/)

## Geocoding

- [Geocodio](http://geocod.io/ "Geocodio"): Online geocoder. Simple to use, but only covers the U.S. Free for less than 5,000 entries per day, after that it's really cheap.
- [Texas A&M Geoservices](http://geoservices.tamu.edu/Services/Geocode/ "Texas A&M Geoservices")
- [OpenCage Geocoder](http://geocoder.opencagedata.com/api.html#quickstart)
- [Geocoding in the browser](http://giscollective.org/geocoding-in-the-browser/ "Geocoding in the browser"): tutorial/tips by Sam Matthews
- [Geocode with a CSV](http://emanuelfeld.github.io/geocoder/ "Geocoder by Emanuel Feld"): Uses the Google Maps API, ideally with not more than a few hundred rows
- [csvgeocode](https://github.com/veltman/csvgeocode): Node.js geocoder tool by Noah Veltman that allows you to convert a CSV with addresses to lat/lon coordinates using several built-in geocoders or a custom one. Fulcrum [wrote a blog post explaining how to use it](http://www.fulcrumapp.com/blog/geocoding-data-with-nodejs/).
- [Nominatim](http://nominatim.openstreetmap.org/)
- [OpenCage Data](https://geocoder.opencagedata.com/)
- [OSMNames](https://osmnames.org/)
- [Mapbox Search API](Mapbox Search API)
- [Pelias](https://github.com/pelias/)

## Projections

- [Choosing the Right Map Projection](https://source.opennews.org/articles/choosing-right-map-projection/): Michael Corey’s guide to smashing the earth for fun and profit
- [Projection Wizard](http://projectionwizard.org/ "Projection Wizard"): Helps you select an appropriate projection for your map, depending on the area that you are mapping.
- [Projection overlays](http://sandbox.azavea.com/projection-overlays/ "Azavea: Projection Overlays"): Shows different areas of the world in different projections to demonstrate the importance of selecting an appropriate projection
- [ArcGIS list of supported map projections](http://help.arcgis.com/en/arcgisdesktop/10.0/help/index.html#//003r00000017000000 "ArcGIS list of supported map projections")
- [USGS Map Projections](http://egsc.usgs.gov/isb//pubs/MapProjections/projections.html "USGS Map Projections"): Descriptions of different types of common projections, plus tables that layout the different properties of various projections
- [Radical Cartography's projection reference](http://www.radicalcartography.net/?projectionref "Radical Cartography's projection reference")
- [Why Web Mercator is used for web maps](https://gist.github.com/tmcw/a3828827c8490f7e13a9#mapproxy)
- [Flex Projector](http://www.flexprojector.com/): Tool to create your own map projection
- [Projection distortions](http://www.gis.osu.edu/misc/map-projections/): Awesome animated map that shows how different projections distort differently
- [Dirty Reprojectors](http://devseed.com/dirty-reprojectors-app/): Download geojson for common features in different projections, or upload your own WGS84 geojson and reproject it.
- [What the proj?](https://stevage.github.io/WhatTheProj/): Provide a projected coordinate and an idea of where it should be and the tool suggests the projection.

## Tutorials / Guides / Forums

- [Intro to the Geo Command Line](https://developmentseed.org/blog/2015/08/28/geo-command-line-introduction/): A blog post by yours truly to introduce GIS/mapping people to the wonderful world of the command line.
- [Making web maps with JavaScript](https://github.com/mjfoster83/web-map-workshop "LeafletJS Tutorial"): A series of web mapping tutorials by Mike Foster.
- [Series of web, web development, web mapping, etc tutorials from DUSPviz](http://duspviz.mit.edu/tutorials/)
- [Aligned Left](http://alignedleft.com/tutorials/d3): Scott Murray's great D3 tutorials
- [How to create a bivariate choropleth map](http://www.joshuastevens.net/cartography/make-a-bivariate-choropleth-map/ "Make a bivariate choropleth map"): Excellent tutorial by Josh Stevens
- [How to make a bivariate choropleth map with ArcMap](https://blogs.esri.com/esri/arcgis/2015/09/15/making-bivariate-choropleth-maps-with-arcmap/)
- [How to make a value-by-alpha map](http://andywoodruff.com/blog/how-to-make-a-value-by-alpha-map/ "How to make a value-by-alpha map"): Excellent tutorial by Andy Woodruff
- [Find and Replace Graphics in Illustrator](http://kelsocartography.com/blog/?p=325 "Nathaniel Kelso Find and Replace Graphics in Illustrator Script"): Have you ever wanted to replace all point symbols on a map in Illustrator with a different symbol? Here's a handy dandy script that you can use!
- [LearnOSM](http://learnosm.org/en/ "LearnOSM"): Guide to learning how to use OpenStreetMap.
- [Flow-mapping with QGIS](http://undertheraedar.blogspot.co.uk/2014/10/flow-mapping-with-qgis.html?m=1 "Flow mapping with QGIS")
- [Designing icons for maps](http://blog.thenounproject.com/post/22660280513/designing-icons-for-web-cartography "Designing Icons for Maps")
- [Python tutorials](https://github.com/SeanEaster/pythonTutorials "Python Tutorials")
- [CartoTalk](http://www.cartotalk.com/ "CartoTalk"): Forum run by NACIS (North American Cartographic Information Society) on all cartography topics.
- [GIS Stack Exchange](http://gis.stackexchange.com/): Forum for answering GIS questions, including QGIS.
- [PostGIS + SQL in Mapbox Studio](https://www.mapbox.com/mapbox-studio/postgis-manual/ "PostGIS + SQL in Mapbox Studio")
- [Intro to Node](https://github.com/maxogden/art-of-node#the-art-of-node "Art of Node"): A guide to Node.js, a JavaScript library that helps you work with different sources
- [Convert Google directions to GeoJSON](http://zevross.com/blog/2014/09/23/convert-google-directions-to-geojson-points-or-polylines/ "Convert Google directions to GeoJSON point or polyline"): Inspired by the [NYC Taxi visualization](http://chriswhong.com/data-visualization/taxitechblog1/), describes how to extract Google Maps directions data as a GeoJSON to then use as you please
- [How to use different projections with Leaflet](http://vis4.net/blog/posts/no-more-mercator-tiles/): Pannable, zoomable map with Leaflet that isn't in web mercator
- [How to create illuminated contours in QGIS](http://anitagraser.com/2015/05/24/how-to-create-illuminated-contours-tanaka-style/): A tutorial by Anita Graser
- [Introduction to D3 web mapping](https://github.com/maptimelex/d3-mapping): Rich Donohue's maptime tutorial that walks through how some basic d3 web maps work
- [GDAL Cheat Sheet](https://github.com/dwtkns/gdal-cheat-sheet): Cheat sheet for GDAL/OGR command-line geodata tools by Derek Watkins
- [How to use non-Web Mercator projections in CartoDB](http://blog.cartodb.com/free-your-maps-web-mercator/)

## Blogs

- [Mapping blogs, woo!](https://docs.google.com/spreadsheets/d/1F1f3p78wHLSjxyDKV0pzY5N1HVrNTBzYKJHzovZXA-A/edit) Publicly editable list of blogs about "maps, cartographic design, mapping technology, and a few related subjects that may include maps."; Initially created by Andy Woodruff.

## Conversion tools

- [Geojson.io](http://geojson.io/ "geojson.io"): Convert to/from GeoJSON. Prep your data for making web maps. I've found it particularly useful for converting to/from CSVs.
- [ToGeoJSON](http://mapbox.github.io/togeojson/): Convert from KML to GeoJSON.
- [csv2geojson](http://mapbox.github.io/csv2geojson/): Convert from CSV to GeoJSON.
- [leaflet-omnivore](https://github.com/mapbox/leaflet-omnivore): Parses different file format to add to Leaflet map.
- [ai2html](http://ai2html.org/ "ai2html"): Converts from Adobe Illustrator document to HTML
- [prj2epsg](http://prj2epsg.org/ "prj2epsg"): Converts a .prj projection file to EPSG number
- [The Distillery](https://shancarter.github.io/distillery/): Convert files to TopoJSON.
- [Ogre](https://ogre.adc4gis.com/): Convert to/from GeoJSON/shapefile.
- ogr2ogr: Great [blog post](http://ben.balter.com/2013/06/26/how-to-convert-shapefiles-to-geojson-for-use-on-github/) on using ogr2ogr to convert to GeoJSON.

## Site generators

- [Gatsby](https://www.gatsbyjs.org/): static site generator (works well with React)

## Hosting

- [Now](https://zeit.co/now): static web host
- [Surge](http://surge.sh/): static web host
- [Map hosting on Amazon S3](https://www.maptiler.com/how-to/hosting-on-amazon-s3/)

## WYSIWYG mapping

- [MapHub](https://maphub.net/): simple interface for making and embedding web maps.

## SQL

- [Spatial SQL](https://github.com/MicheleTobias/Spatial_SQL) (Workshop by Michele Tobias)

## Git

- [Git Flight Rules](https://github.com/k88hudson/git-flight-rules)

## Raster

- [GeoTiff.js](https://geotiffjs.github.io/): Library to parse TIFF files for visualization or analysis, usable in both the browser and node.js applications.

## UI/UX

- [MAP UI Patterns](https://www.mapuipatterns.com/)

## Miscellaneous

- [Convert ArcGIS JSON to GeoJSON](https://arcgisjson.togeojson.com/)
- [Everything you ever wanted to know about GeoJSON](http://www.macwright.org/2015/03/23/geojson-second-bite.html "Tom MacWright blog post about GeoJSON"): Excellent blog post by Tom MacWright about the GeoJSON format
- [Awesome GeoJSON](https://github.com/tmcw/awesome-geojson): List of useful GeoJSON utilities
- [Project Linework](http://www.projectlinework.org/ "Project Linework"): Library of free, public-domain sets of vector linework for cartographic use
- [The Lost Art of Critical Map Reading](http://www.graphicarto.com/the-lost-art-of-critical-map-reading/ "Mike Foster's Lost Art of Critical Map Reading"): Mike Foster's explanation of how and why to read maps with a critical eye
- [http://www.comparea.org/](http://www.comparea.org/): Compares areas of two different geographic regions/countries
- [Political world maps](http://www.shadedrelief.com/political/): Free, openly licensed world political maps from Tom Patterson, including hand-made shaded relief. You can edit as you wish and use without attribution.
- [Sketchy D3 map](http://bl.ocks.org/wboykinm/81b9be3f39026a0f3f1f)
- [More resources!](http://duspviz.mit.edu/resources/) From DUSPviz
- [Data Viz Tools](http://dataviz.tools/): a curated guide to the best tools, resources and technologies for data visualization
- [Popper](https://popper.js.org/): JS library for managing popups and tooltips within a document
- [Bounding box](https://boundingbox.klokantech.com/): tool for finding the lat/lon coordinates of a bounding box.

## Tutorials

- [Geospatial Analysis
  Create interactive maps, and discover patterns in geospatial data](https://www.kaggle.com/learn/geospatial-analysis)
