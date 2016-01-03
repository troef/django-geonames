# django-geonames

Do you need geographic data in your project? For a single country or for the entire world? Django GeoNames is an attempt to make it easy to port the free available GeoNames database to your django project. 

__What is geonames?__
Don't know [GeoNames](http://www.geonames.org/)? The GeoNames geographical database covers all countries and contains over eight million placenames that are available for download *free of charge* under [cc-by license](https://creativecommons.org/licenses/by/3.0/). They offer great geo webservices such as a geo search API. Their *[daily database dump](http://download.geonames.org/export/dump/)* is what we are using to synchronize with.


__What to expect __

We believe geo data in a web application always requires customization. To emphasize this we provide no out-of-the-box installation. You are always required to setup your own 'geo' app. The fastest way to do this is by extending our abstract models. 


* A 1:1 port of the geonames datamodel 
* Easy to use synchronization with geonames data sources using management commands
* Greatly customizable filter options to keep your local database as small as possible
* Very customizable using 'synchronization hooks' and a local 'geo app' 
* Fast implementation using our abstract models
* 

__What not to expect__

* Out of the box geo functionality
* Spatial querying (use *django-cities* instead)
