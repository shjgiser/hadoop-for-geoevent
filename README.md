# hadoop-for-geoevent

ArcGIS GeoEvent Processor Sample Hadoop Outbound Connector for storing GeoEvents in HDFS.

![App](hadoop-for-geoevent.png?raw=true)

## Features
* Hadoop Outbound Transport

## Instructions

Building the source code:

1. Make sure Maven and ArcGIS GeoEvent Processor SDK are installed on your machine.
2. Run 'mvn install -Dcontact.address=[YourContactEmailAddress]'

Installing the transport and connector:

1. Copy the *.jar files under the 'target' sub-folder(s) into the [ArcGIS-GeoEvent-Processor-Install-Directory]/deploy folder.
2. Open the ArcGIS GeoEvent Processor Manager, go to the 'Site -> Configuration Store' page and import the HDFS_Connector.xml file.

## Requirements

* ArcGIS GeoEvent Processor for Server.
* ArcGIS GeoEvent Processor SDK.
* Java JDK 1.6 or greater.
* Maven.

## Resources

* [Download the connector's tutorial](http://www.arcgis.com/home/item.html?id=fa7b33b480c940019d17d3eb159a8b04) from the ArcGIS GeoEvent Processor Gallery
* [ArcGIS GeoEvent Processor for Server Resource Center](http://pro.arcgis.com/share/geoevent-processor/)
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [twitter@esri](http://twitter.com/esri)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/esri/contributing).

## Licensing
Copyright 2013 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](license.txt?raw=true) file.

[](ArcGIS, GeoEvent, Processor)
[](Esri Tags: ArcGIS GeoEvent Processor for Server)
[](Esri Language: Java)