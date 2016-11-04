.. toctree::
  :maxdepth: 1
  
  map_symbology
  gps_camera
  feature_toolbar
  map_toolbar
  popup_bar
  find_location
  export_map
  download

FireMapper
======================================

FireMapper is a mobile application is designed for quickly generating bushfire maps. It is designed to be used by firefighters and other emergency services on the field as a data collection tool

Map Symbology
----------------
FireMapper contains bush firefighting symbols that are commonly used in Australia, USA & Canada with support for:

* National All Hazards Symbology Set
* USA Interagency Wildfire Point Symbols
* New Zealand Symbology

.. image:: /screenshots/symbology_set.png
  :width: 220px

Draw and Record Lines
---------------------
FireMapper allows users to quickly draw lines and record GPS tracks. The interface is designed for easy & fast data entry. Common line styles that are used in firefighting are supported including:

* Active & Inactive Fires
* Proposed & Completed Control Lines
* Proposed & Completed Blackburn Lines
* Machine Cut Track
* and more....

GPS Camera
----------
FireMapper now includes a GPS camera that allows users to capture geo-referenced photos. When you take a picture, FireMapper automatically records the location and direction of the image and displays it on the map.

Photos taken with the GPS camera can be shared via text message, email and more via the ‘Export Map’ screen.

(GPS Camera has not been released on Android version yet..)

.. image:: /screenshots/camera.png
  :width: 220px

Location Formats
----------------
FireMapper supports a range of coordinate systems including:

* Latitude/Longitude (Decimal Degrees and Degree Minutes/Aviation)
* UTM Coordinates
* NZTM Coordinates (Great for New Zealand)
* 1:25 000, 1:50 000 & 1:100 000 map sheet references
* UBD Map References (Sydney, Canberra, Adelaide, Perth)

You can use the search tool to quickly search for locations in a range of different coordinate formats (4 figure, 6 figure, 14 figure, lat/lng, utm and more)

Export Maps
-----------
Multiple points can be drawn on the map and exported in the same email. The map data can be exported as:

* GPX *(suitable for ArcGIS, MapDesk, QGIS and other popular GIS products)*
* KML *(suitable for Google Maps & Google Earth)*
* KMZ *(best for Google Earth, contains embedded symbology)
* CSV *(suitable for Microsoft Excel & Google Spreadsheets)*
* JPG *(suitable for viewing and printing) - satellite and terrain views*

.. image:: /screenshots/export_map.png
  :width: 320px