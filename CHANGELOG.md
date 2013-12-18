## Version 3.6

* Released December 18, 2013
* Updated build.properties to require ArcGIS API 3.6 for Flex.
* Updated meta.xml, widget version and description to reflect version 3.6.

## Version 3.5
* Released October 10th, 2013
* Updated build.properties to require ArcGIS API 3.5 for Flex.
* Updated meta.xml, widget version and description to reflect version 3.5.
* Updated [gh_pages branch][gh_pages]
* [Fixed issue][ghi20]: where classification layer id was parsed incorrectly.
* Added [user enhancement request][uer1] to support multiple layers inside of widget configuration, see [GitHub Issue 18][ghi18]

## Version 3.4

* Released August 7, 2013
* Updated build.properties to require ArcGIS API 3.4 for Flex.
* Updated meta.xml, widget version and description to reflect version 3.4.
* Added layer name option to the configuration file, used for display purposes only.
* Added gh_pages branch to host working sample.
 
## Version 3.3

* Released May 14, 2013
* Updated build.properties to require ArcGIS API 3.3 for Flex.
* Updated meta.xml, widget version and description to reflect version 3.3.

## Version 3.2

* Released March 22, 2013
* Updated build.properties to require ArcGIS API 3.2 for Flex.
* Updated meta.xml, widget version and description to reflect version 3.2.
* Updated icon in meta.xml to resolve asset name conflict with viewer.
* Renamed widget asset from i_thematic.png to i_thematic_icon.png.

## Version 3.1

* Released February 13, 2013
* Added support for the following user interface enhancements and widget features:
    * [Layer transparency](https://github.com/Esri/thematic-widget-flex/issues/7)
    * [Users can now change the start and end color ramp values](https://github.com/Esri/thematic-widget-flex/issues/8)
    * [Configurable classification methods and classification fields](https://github.com/Esri/thematic-widget-flex/issues/9)
    * [Support for dynamic labeling](https://github.com/Esri/thematic-widget-flex/issues/10)
* Bug fixes:
    * [Widget legend issue](https://github.com/Esri/thematic-widget-flex/issues/11)
* First GitHub release
    * New documentation on [Github wiki](https://github.com/Esri/thematic-widget-flex/wiki) for [Application Builder](https://github.com/Esri/thematic-widget-flex/wiki/Application-Builder) users and [Developers](https://github.com/Esri/thematic-widget-flex/wiki/Developers).
    * Includes Apache&reg; Ant&reg; [build](build.xml) file to compile and package widget for [Application Builder](http://resources.arcgis.com/en/help/flex-viewer/concepts/01m3/01m30000004m000000.htm) integration.
* Developers: Requires Adobe&reg; Flex&reg; SDK 4.6.0 and ArcGIS API 3.1 for Flex

## Version 3.0

* Released July 19, 2012
* Supports [Application Builder](http://resources.arcgis.com/en/help/flex-viewer/concepts/01m3/01m30000004m000000.htm "Viewer concepts") integration.
* Contains starting [Custom Widget Template](../../tree/CustomWidgetTemplate-Begin), before integration with ArcGIS API for Flex sample.
* Contains finished [Custom Widget Template](../../tree/CustomWidgetTemplate-End), after integration with ArcGIS API for Flex sample.
* Requirements
    * ArcGIS 10.1 or later required for dynamic layer support.
    * Developers: Requires Adobe Flex SDK 4.6.0 and ArcGIS API 3.0 for Flex.
* This code sample was originally designed to support the 2012 User Conference session "ArcGIS Viewer for Flex - Advanced Topics".

[gh_pages]: http://esri.github.io/thematic-widget-flex

[ghi18]: https://github.com/Esri/thematic-widget-flex/issues/18
[ghi20]: https://github.com/Esri/thematic-widget-flex/issues/20

[uer1]: http://forums.arcgis.com/threads/76036-thematic-widget-flex?p=299903&viewfull=1#post299903