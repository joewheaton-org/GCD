---
title: Release Notes
---

#### [6.1.14 - 26 Nov 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/6114-26nov2015)

posted Nov 26, 2015, 10:50 AM by Philip Bailey

- Moved pyramid building code out of GISCode and into the user interface so that it doesn't interfere with other products that use GISCode.

[Download](http://releases.northarrowresearch.com/GCD/Desktop/2015_11_26_GCDAddIn_6_1_14.esriAddIn)

#### [6.1.13 - 18 Nov 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/6113-18nov2015)

posted Nov 18, 2015, 2:29 PM by Philip Bailey

- Temporary workspace path now validated on new/open project rather than on GCD start-up.
- Improved handling of temporary workspace paths containing spaces and periods.

[[Download](http://releases.northarrowresearch.com/GCD/Desktop/2015_11_18_GCDAddIn_6_1_13.esriAddIn)]

#### [6.1.12 - 12 Nov 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/6112-12nov2015)

posted Nov 12, 2015, 5:11 PM by Philip Bailey   [ updated Nov 12, 2015, 6:13 PM ]

- All GCD project rasters now include compression.
- New user interface for controlling which rasters have pyramids built automatically.
- FIS rule file does not require a blank line at end of file and can have blank lines between rules.
- Cleaned-up user interface for managing the GCD temporary workspace.
- Fixed exception when deleting an error surface from the DEM survey properties form.
- Associated surface roughness calculation now enforces cell resolution of DEM on sample window size.

[Download](http://etal.usu.edu/GCD/GCD6/2015_11_12_GCDAddIn_6_1_12.esriAddIn)

#### [6.1.11 - 23 Oct 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/6111-23oct2015)

posted Oct 23, 2015, 2:18 PM by Philip Bailey   [ updated Oct 23, 2015, 2:19 PM ]

- Budget Segregation now deletes intermediate masked DoD rasters as it loops over classes.
- Budget segregation now uses two GDAL calls instead of ESRI SetNull calls.

[Download](http://etal.usu.edu/GCD/GCD6/2015_10_23_GCDAddIn_6_1_11.esriAddIn)

#### [6.1.10 - 19 Oct 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/6110-19oct2015)

posted Oct 19, 2015, 2:45 PM by Philip Bailey   [ updated Oct 19, 2015, 2:46 PM ]

- Improved handling of both DEM method masks and budget segregation masks:

- - Empty feature classes
  - Feature classes with mismatching spatial references
  - Feature classes stored in file geodatabases
  - Geodatabase feature classes with field names longer than 10 characters
  - Feature classes with Z and/or M values

[Download](http://etal.usu.edu/GCD/GCD6/2015_10_19_GCDAddIn_6_1_10.esriAddIn)

#### [6.1.9 - 6th Aug 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/619-6thaug2015)

posted Aug 6, 2015, 8:16 PM by Philip Bailey   [ updated Aug 11, 2015, 5:10 PM by Joe Wheaton ]

- Enabled editing of error surfaces in user interface
- Fixed Budget Segregation Bug With Duplicate Field Values.
- Removed multi-resolution roughness tool from GCD menu.
- Warning that concave hull tool only works in ArcGIS 10.1.
- Synchronized GISCode across products.

![http://etal.usu.edu/GCD/GCD6/2014_11_25_GCDAddIn_6_1_03.esriAddIn](https://sites.google.com/a/joewheaton.org/gcd/_/rsrc/1468741652116/downloads/AddIn_Graphic_50x50.png) `2015_08_06_GCDAddIn_6_1_09.esriAddIn`, (20 Mb, August 6, 2015) 

#### [6.1.8 - 15 April 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/618-15april2015)

posted Apr 15, 2015, 5:11 PM by Philip Bailey   [ updated Apr 15, 2015, 5:17 PM by James Hensleigh ]

- Fixed thresholded DoD striping when spatial coherence is enabled

- Fixed thresholded DoD statistics for budget segregation

- Warning message when DoD results in all zeroes (i.e. when new and old raster are identical)

- Editing survey items

- - DEM survey name, method and type
  - Associated surface name and type
  - Error surface name

- Enhanced survey date control (partial date or time allowed)

- Updated FIS library with more consistent file names

- - naming convention [explained here](https://bitbucket.org/pipbailey/fis-dem-error-repository).

- Error surfaces can now be derived from an existing associated surface

- Improved checking when an input raster is missing a spatial reference

- User can now sort surveys in a project by:

- - date
  - name
  - date added to project

- % error values now appear in report

- Hiding report tabs in analyses results forms

- Turning on Spatial Analyst Extension automatically when running HillShade geoprocessing

- Budget segregation masks can be added to map from Budget Segregation Results panel

- Activated help buttons for new online help pages

- GCD Project tree auto-expands DoD and Budget Segregation nodes

- Improved exception handling

- - User interface form cleaned up
  - ArcGIS version now provided in message
  - GCDCore and RasterMan included in message

- Upgraded to the GCDCore and Rasterman 6.1.6

- More documentation on GCD 6 Help pages.

Known Issues

- Concave hull survey boundary tool fails in ArcGIS 10.2.2

[Download](http://etal.usu.edu/GCD/GCD6/2015_04_15_GCDAddIn_6_1_08.esriAddIn)

#### [6.1.7 - 4 Feb 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/617-4feb2015)

posted Feb 4, 2015, 12:53 PM by Philip Bailey   [ updated Feb 5, 2015, 2:02 PM ]

- Bootstrap Roughness Modeler tool beta release

- - provides user ability to estimate roughness through a bootstrapping routine.
  - documentation for tool can be [found here](https://sites.google.com/a/joewheaton.org/gcd-6-help/gcd-command-reference/gcd-analysis-menu/b-roughness-analysis-submenu/bootstrap-roughness-modeler).

- Grain Size Distribution Estimator beta release

- - provides user ability to obtain D16, D50, D84, and D90 estimates of grain size from a surface roughness raster.
  - documentation for tool can be [found here](https://sites.google.com/a/joewheaton.org/gcd-6-help/gcd-command-reference/gcd-analysis-menu/b-roughness-analysis-submenu/grain-size-distribution-estimator).

- Fixes to error surface symbolization.

- TopCat User interface fixes.

[Download](http://etal.usu.edu/GCD/GCD6/2015_02_04_GCDAddIn_6_1_07.esriAddIn)

#### [6.1.6 - 31 Jan 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/616-31jan2015)

posted Jan 31, 2015, 3:24 PM by Philip Bailey

- Round 2 of GCD Report Improvements

[Download](http://etal.usu.edu/GCD/GCD6/2015_01_31_GCDAddIn_6_1_06.esriAddIn)

#### [6.1.5 - 28 Jan 2015](https://sites.google.com/a/joewheaton.org/gcd/downloads/release-notes/615-28jan2015)

posted Jan 28, 2015, 2:33 PM by Philip Bailey

- GCD Report Round 1 refinements incorporated.
- Code vault cleanup and tidy.

[Download](http://etal.usu.edu/GCD/GCD6/2015_01_28_GCDAddIn_6_1_05.esriAddIn)