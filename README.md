Miami-Dade County Municipality API
==================================

This is a geospatial APIs that will retreive the municipality within 
Miami-Dade County, given a latitude and a longitude. If no municipality is returned, 
this means that the latitude and longitude may be in unincorporated Miami-Dade County, 
an area which provides city services to 2.1 million people so long as the location is 
within county borders.

This project is a fork of a the [US Census Area API](https://github.com/codeforamerica/US-Census-Area-API), 
a Code for America project that allows simple geospatial APIs. We installed the repo 
on heroku, with a ZIPPED_DATA_URL argument of a URL taken directly from 
[Miami-Dade County's ESRI portal](http://gis.mdc.opendata.arcgis.com/datasets/4e13f5bcf55d401b85ab85b90495ba50_0).


What other Miami-Dade County Geospacial APIs are out there?
----

Shortly after this repo was localized, we were notified that 
[Miami-Dade County offers web services](http://gisws.miamidade.gov/gisaddress/addresswebservice.asmx?op=Address) 
which return metadata - including municipality names - given a particular address in 
the county. The county web services have some differences compared to this API, including 
SOAP services, XML formats and X and Y return coordinates rather than latitudes and longitudes. 
Use the web service that works the best for you!


Installing
----

See the [US Census Area API](https://github.com/codeforamerica/US-Census-Area-API) for full installation instructions.


Credits
----

Written by [Michal Migurski](https://github.com/migurski) with
[Andy Hull](https://github.com/andyhull), localized by [Ernie Hsiung](https://github.com/ErnieAtLYD) (c) 2013-2015 Code for America.
See `LICENSE` for license information.
