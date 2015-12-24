This project is a fork of https://github.com/shramov/leaflet-plugins
The reason for the fork is to be able to import the project in node/browserify builds.

STATUS: WIP.

As of now only tile/layer/Google.js has been modified to not use global L object and instead require('leaflet')

Leaflet plugins
============

What ?
------

Miscellaneous Leaflet plugins for services that need to display
route information and need satellite imagery from different providers.
Currently it consists of:

 - Vector layers (`layer/vector/`):
   * GPX
   * KML

 - Providers (`layer/tile`):
   * Google - using Google Maps API v3;
   * Yandex - using Yandex Maps API v2;
   * Bing - with proper attribution.

All these providers are implemented with respect to terms of use.

Also there are some useful control plugins (`control/`):

 * Permalink - OpenLayers compatible permanent link with support for storing
   location data in hash part (#lat=...);
 * Distance - simple tool to measure distances on maps

Where ?
------

Homepage : https://github.com/shramov/leaflet-plugins

Downloads : https://github.com/shramov/leaflet-plugins/releases

npm : https://www.npmjs.org/package/leaflet-plugins
