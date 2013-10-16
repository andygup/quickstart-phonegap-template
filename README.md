# quickstart-phonegap-template

Don't want to use node to build PhoneGap/Cordova 3.x apps? If so, then this template is for you!

**No Node.js is required.**

A set of simple samples that show how to get started with the ArcGIS API for JavaScript and PhoneGap/Cordova. These samples provide best practices for using PhoneGap across different device operating systems and within the PhoneGap application lifecycle.

PhoneGap is based on the [Apache Cordova](http://cordova.apache.org/) open source project. You can download PhoneGap or Cordova and both will work. Adobe has a few additions to PhoneGap that don't exist in Cordova such as [PhoneGap Build](https://build.phonegap.com/apps) which is an online build system.

## Features
This repo contains one Hello World app and four sample applications. Note these applications will not work as stand-alone web applications because there are coded specifically for PhoneGap/Cordova.
* index.html - the cordova Hello World app.
* index_basicmap.html - a basic mapping application configuration.
* index_basicwebmap.html - uses a simple web map.
* index_basicgps.html - uses the GPS to acquire current location and center the map.
* index_jquerymobilegps.html - demonstrates how to use jQuery mobile with PhoneGap and the ArcGIS API for JavaScript.

## Instructions

NOTE: The current PhoneGap online documentation is pretty bad, so I recommend just using Cordova and the Cordova documentation. The Cordova documentation works and is correct. I find the PhoneGap documentation mostly incorrect and confusing since some of it was written for older versions of PhoneGap and the instructions may or may not work with the lastest version.

1. Fork and then clone the repo or download the .zip file. 
2. Find the appropriate [platform guide](http://cordova.apache.org/docs/en/3.1.0/guide_platforms_index.md.html#Platform%20Guides) in the Cordova documenation.
3. Follow the "Open a Project in the SDK" (minus the node.js instructions) for your platform using this repo as the target for the IDE.

## Testing
**Option 1** - Push application directly to a device and use console.log statements for troubleshooting.

**Option 2 **- Use the [Ripple Emulator Chrome Plugin](https://chrome.google.com/webstore/detail/ripple-emulator-beta/geelfhphabnejjhdalkjhgipohgpdnoc?hl=en) to test locally on your machine.

Here's a good article to check out by [Andy Trice](http://www.tricedesigns.com/2013/01/18/my-workflow-for-developing-phonegap-applications/). This article also provides suggestions on how to set up Chrome for testing on http://localhost. I'm working on a blog article to explain this in more detail.


## Requirements

* A minimum of one device for each mobile platform you want to deploy to.
* Eclipse (Android) or ADT Bundle (Android) and XCode (iOS)
* Android SDK if you are deploying to Android

## Resources

* [ArcGIS for JavaScript API Resource Center](http://help.arcgis.com/en/webapi/javascript/arcgis/index.html)
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [twitter@esri](http://twitter.com/esri)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Anyone and everyone is welcome to contribute. 

## Licensing
Copyright 2013 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
