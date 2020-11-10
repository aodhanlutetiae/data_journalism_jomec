**PREPARATORY WORK**

— Do: get Tableau Desktop / Public running, get Carto login (via github education), install QGIS 3.10, get Datawrapper and Flourish accounts

— Read:
- [Marcoux, Jacques. Geographic information systems, a use case for journalists. Datajournalism.com, Nov 2019.](https://datajournalism.com/read/longreads/geographic-information-systems-a-use-case-for-journalists)
- [ONS. A beginner's guide to UK geography, 2020.](https://www.arcgis.com/sharing/rest/content/items/86ebfbad61c941bebbc7edbf2b985efe/data)
- [ONS. UK geographic codes reference, 2020.(reference only)](https://geoportal.statistics.gov.uk/datasets/register-of-geographic-codes-june-2020-for-the-united-kingdom-v2)

**CONCEPTS**

- latitude & longitude, xy coordinates, projection
- geodata filetypes (csv, KML & KMZ & GML, shp, geojson)
- Boundaries Wales (Police & emergency services, Rugby regions, Senedd regions, NHS boards & trusts, Unitary authorities, UK & Senedd constituencies, Electoral wards, Communities (parishes), Output areas, Super Output areas)
- Googlemaps, OSM, Datawrapper, Flourish
- Carto, Mapbox
- Tableau, QGIS
- Python mapping modules (geopandas, folium, geojson)
- Other python mapping modules (descartes, gmaps, gpxpy, mplleaflet, geoplotlib, cartopy)

**PRACTICE**

- Build a Datawrapper choropleth (no adjustment for population) of number of [petition](https://petition.parliament.uk/petitions/550579) signatures by Welsh constituency using wales_petition.csv

- Using a python notebook, download the JSON data on the [Free School Meals petition](https://petition.parliament.uk/petitions/554276.json). Drill down for constituency data only and establish a dataframe. Then filter for Welsh constituencies only. Then collect [some ONS population data](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/parliamentaryconstituencymidyearpopulationestimates) for each constituency and merge the two dataframes. Export the data as a csv and build a Datawrapper choropleth map showing number of petition signatures by constituency per 10,000 people.

- Googlemaps Points map: Plot the stop and search data in Sept 2020 (male and female) from South Wales Police. Use female_ss_sept and male_ss_sept.csv. (Notebook available with steps from original data to two filtered datasets for male and female)

- DW Hexmap: Wales 2019 UK election results
- Flourish Hexmap: US elections 2016 / 2020

- Tableau Points map: EPL stadiums and goals scored 2018-19
- Tableau geojson example: Irish counties
- Tableau shp file: Great Britain lighthouses

**HOMEWORK (Colab notebooks supplied)**
- Line map. Construct a line map of flight PS752 downed in Iran from ps752.csv (gathered [here](https://www.flightradar24.com/blog/ukrainian-flight-ps752-crashes-shortly-after-take-off-from-tehran/)) (notebook using mplleaflet, folium, matplotlib)
- Points map. Construct a points map of several sport facilities in Cardiff (notebook using shapefiles)

[Not covered: Animation, Realtime updating, Python modules: geoplotlib, cartopy, geojson, geopandas]

**RECOMMENDED RESOURCES**

- [Mason, Betty. “Election maps are everywhere. Don’t let them fool you”. New York Times. 2020.](https://www.nytimes.com/interactive/2020/10/30/opinion/election-results-maps.html)
- [Ericson, Matthew. When maps shouldn’t be maps. Blogpost. 2011.](http://www.ericson.net/content/2011/10/when-maps-shouldnt-be-maps/ )
- [Field, Kenneth & Dorling, Danny. “UK election cartography”, International Journal of cartography. 2/2, 2016.](https://www.geog.ox.ac.uk/research/transformations/gis/papers/2017/UK_election_cartography.pdf)
- [Giulani, Diego & Napolitano, Maurizio. Online course materials. Geospatial analysis and representation for data science. University of Trento, 2020.](https://napo.github.io/geospatial_course_unitn/)
- [Knight Center. Online course: Intro to mapping for journalists. 2018.](https://journalismcourses.org/course/intro-to-mapping-and-gis-for-journalists/ )
