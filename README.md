# django-geonames

Django Geonames is an attempt to make it easy to port django geonames to a django project. 

We believe geo data in a web application always requires customization. To emphasize this we provide no out-of-the-box installation. You are always required to setup your own 'geo' app. The fastest way to do this is by extending our abstract models. 

__What to expect__

* A 1:1 port of the geonames datamodel 
* Easy to use synchronization with geonames data sources using management commands
* Greatly customizable filter options to keep your local database as small as possible
* Very customizable using 'synchronization hooks' and a local 'geo app' 
* Fast implementation using our abstract models
* 

__What not to expect__

* Out of the box geo functionality
* Spatial querying (use *django-cities* instead)
