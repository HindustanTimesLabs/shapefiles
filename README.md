#shapefiles#

Use these files to make maps.

##File types##
You'll find a few different file types which can be used to make maps with different software.
- **.json** [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON).
- **.kml** [Keyhole Markup Language](https://en.wikipedia.org/wiki/Keyhole_Markup_Language).
- **.zip** [Shapefiles](https://en.wikipedia.org/wiki/Shapefile), including the zip file with all three necessary file formats &mdash; *.shp*, *.shx*, and *.dbf*. Sometimes also including *.cpg*, *.prj* and *qpj*.

##Sources##

###All-India###
- **india/district/india_2011_district.ext** - Administrive districts of India as of the 2011 Census. Source: [DataMeet](https://github.com/datameet/maps/tree/master/Districts/Census_2011).
- **india/state_ut/india_state.ext** - Current Indian states and union territories. Source: [DataMeet](https://github.com/datameet/maps/tree/master/Survey-of-India-Index-Maps/Boundaries).
- **india.state_ut/india_2000-2014_state.ext** - Indian states and union territories after 2000 creation of Jharkhand, Chhattisgarh, and Uttarakhand but before 2014 creation of Telangana. Source: [DataMeet](https://github.com/datameet/maps/tree/master/Survey-of-India-Index-Maps/Boundaries); Andhra and Telangana merged with QGIS.

###States and Union Territories###
- **state_ut/[state/ut_name]/assembly** Assembly constituencies, including Andhra Pradesh before the 2014 Telangana split. Source: (1) [Election Commission of India](http://psleci.nic.in/). [View the scraper's repo](https://github.com/HindustanTimesLabs/eci-shape-scrape). (2) [Election Commission of India](http://eci.nic.in/eci_main/GisLayers/GIS_AC_Data.zip). [View the scraper's repo](https://github.com/HindustanTimesLabs/assembly-shape-scrape).
- **state_ut/uttarpradesh/parliament AND district** Parliamentary (Lok Sabha) and district boundaries of Uttar Pradesh. Source: Election Commission of India, [Shristi(GIS-UP)](http://gis.up.nic.in/srishti/election2017/). [View the scraper's repo](https://github.com/HindustanTimesLabs/up-shape-scrape).
- **state_ut/[state or ut other than uttar pradesh]/parliament** Parliamentary (Lok Sabha) boundaries for Indian states and union territories. Source: [Election Commission of India](http://eci.nic.in/eci_main/GisLayers/GIS_PC_Data.zip). [View the scraper's repo](https://github.com/HindustanTimesLabs/parliament-shape-scrape).
- **state_ut/[state or ut other than uttar pradesh]/district** District boundaries for the 2011 Census for Indian state and union territories. Source: [DataMeet](https://github.com/datameet/maps/tree/master/Districts/Census_2011).

###Cities###
- **city/mumbai/ward** City wards (administrative units). Source: Traced with QGIS from a [BMC Elections map](http://www.bmcelections.com/wards-in-mumbai/).

##Disclaimer##
Though we have attempted to gather these files from the most reliable sources available, we do not guarantee their accuracy. You use these files at your own risk. 