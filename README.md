# django-geonames

Do you need geographic data in your project? For a single country or for the entire world? Django GeoNames is an attempt to make it easy to port the free available GeoNames database to your django project. 

__What is geonames?__

Don't know [GeoNames](http://www.geonames.org/)? The GeoNames geographical database covers all countries and contains over eight million placenames that are available for download *free of charge* under [cc-by license](https://creativecommons.org/licenses/by/3.0/). They offer great geo webservices such as a geo search API. Their *[daily database dump](http://download.geonames.org/export/dump/)* is what we are using to synchronize with.

__What to expect__

In my experience geo data in a web application always requires customization. To encourage this django-geonames does not provide a out-of-the-box installation. You are always required to setup your own 'geo' app allowing maximum flexibility. So, if it doesn't work out of the box, what does the package has to offer? 

* A set of fully prepared abstract models for you to extend in a matter of minutes
* A clever synchronization command
* Great documentation on how to create your own customized geo app

__Design philosophy__

* The abstract models must be light using as little indexes as possible to support large datasets
* The package is not dependant on other third-party packages
* The user has to be able to extend/adapt the package to its own needs including
  * Adding indexes
  * Adding spatial functionality
  * Customize the import behaviour using hooks
* We want to have great documentation including
  * Quick start guide
  * Examples for the most common customizations
  * An example app in the repositry showing the most common customizations
    



* A fully prepared port (=adaptation) of the geonames datamodel to a Django environment 
* Easy to use synchronization with geonames data sources using management commands
* Greatly customizable filter options to keep your local database as small as possible
* Very customizable using 'synchronization hooks' and a local 'geo app' 
* Fast implementation using our abstract models
* 

__What not to expect__

* Out of the box geo functionality
* Spatial querying (use *django-cities* instead)
