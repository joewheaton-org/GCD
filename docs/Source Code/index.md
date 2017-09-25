---
title: Source Code
---

GCD 6 exists in a few different flavors. The GCD 6 ArcGIS Add-In is a C# project coded in Visual Studio that makes calls to an underlying GCDCore library written in C++, as well as a [RasterMan Library](https://github.com/NorthArrowResearch/rasterman) also written in C++. There is a command-line version of GCD that makes calls to the same C++ libraries. Given how finicky the Add-In program is, we have not made that open source and instead freeware. However, the underlying libraries that all the computations and GCD functionality is based on are all open source.

### GCDCore Library

The GCDCore Library will be posted to a GitHub repository shortly. 

### RasterMan Library


The [RasterMan Library](https://github.com/NorthArrowResearch/rasterman) is used in GCD and other tools and is an open source library of common raster geoprocessing calls written in C++ and available in Win32, Win64, Ubuntu12.04 and OSX 10.10 builds. A GitHub repository of the source code can be found [here](https://github.com/NorthArrowResearch/rasterman).

![rasterman]([{{ site.baseurl }}/assets/images/rasterman.png)

### GCD Specific DEM Error Model Fuzzy Inference Systems

[![Bitbucket_Logo]({{ site.baseurl }}/assets/images/Bitbucket_Logo.png)](https://bitbucket.org/pipbailey/fis-dem-error-repository)

The GCD supports building and running `*.fis` [Matlab Fuzzy Logic compatible](https://www.mathworks.com/help/fuzzy/index.html) fuzzy inference systems . We have an open source [bit-bucket repository](https://bitbucket.org/pipbailey/fis-dem-error-repository) for all the FIS error models we use. This repository is linked to the GCD FIS Library that the GCD ships with.