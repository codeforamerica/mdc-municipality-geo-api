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


Installing
----

See the [US Census Area API](https://github.com/codeforamerica/US-Census-Area-API) for full installation instructions.


Credits
----

Written by [Michal Migurski](https://github.com/migurski) with
[Andy Hull](https://github.com/andyhull), localized by [Ernie Hsiung](https://github.com/ErnieAtLYD) (c) 2013-2015 Code for America.
See `LICENSE` for license information.