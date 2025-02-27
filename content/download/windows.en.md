---
title: "Windows"
date: 2021-12-29T11:02:05+02:00
description: "Download GRASS GIS installers for Windows"
weight: 2
layout: "os"
---


#### Quick links

[ [**Standalone installers**](#standalone-installers) | [**OSGeo4W**](#OSGeo4W) ]

<div class="alert rounded-0 alert-default">
<i class="fa fa-arrow-right"></i> Install GRASS GIS on Windows using a standalone installer or OSGeo4W. </div>

<hr>


### <a name="standalone-installers"></a> Standalone installers

Standalone installer: install GRASS GIS with the required support packages.

#### <a name="GRASS-GIS-current"></a> GRASS GIS 8.0.1 (current)

<div class="alert rounded-0 alert-success">
<i class="fa fa-info-circle"></i> <u>New stable release</u>, see <a href="https://trac.osgeo.org/grass/wiki/Grass8/NewFeatures80">GRASS GIS 8.0 new features</a> and <a href="https://github.com/OSGeo/grass/releases/tag/8.0.1">GRASS GIS 8.0.1 announcement</a> for more information.</div>

*  [<i class="fa fa-download"></i> Download 64bit](/grass80/binary/mswindows/native/WinGRASS-8.0.1-1-Setup.exe)

<hr>

#### <a name="GRASS-GIS-old"></a> GRASS GIS 7.8.7 (legacy)

<div class="alert rounded-0 alert-warning">
<i class="fa fa-info-circle"></i> <u>Old stable release</u>, see <a href="https://trac.osgeo.org/grass/wiki/Grass7/NewFeatures78">GRASS GIS 7.8 new features</a> and  <a href="https://github.com/OSGeo/grass/releases/tag/7.8.7">GRASS GIS 7.8.7 announcement</a> for more information.
</div>

*  [<i class="fa fa-download"></i> Download 64bit](/grass78/binary/mswindows/native/x86_64/WinGRASS-7.8.7-1-Setup-x86_64.exe)

<!--
*  [<i class="fa fa-download"></i> Download 32bit](/grass78/binary/mswindows/native/x86/WinGRASS-7.8.6-3-Setup-x86_64.exe)
-->

<hr>

#### <a name="GRASS-GIS-devel"></a> GRASS GIS 8.2.0 (preview)

<div class="alert rounded-0 alert-info">
<i class="fa fa-info-circle"></i> Active <u>development</u> and <u>experimental</u> <b>GRASS GIS</b> version.
</div>

*  [<i class="fa fa-download"></i> Download 64bit](https://wingrass.fsv.cvut.cz/grass81/)

<hr>


### <a name="OSGeo4W"></a> OSGeo4W

OSGeo4W is an installer for a broad set of open source geospatial software packages including GRASS GIS as well as many other packages (QGIS, GDAL/OGR, and more).

*  [<i class="fa fa-download"></i> Download OSGeo4W v2](https://download.osgeo.org/osgeo4w/v2/osgeo4w-setup.exe)

**NOTE FOR EXISTING USERS**: OSGeo4W v2 is now the regular repository. OSGeo4W v2 does not include a 32-bit version. If you need 32-bit support, use the version 1 download (See below). 

**CAUTION**: Upgrades of old (v1) setups using the new repository are not supported. You need to do a fresh install or use a different install directory.

Legacy download (OSGeo4W v1)

*  [<i class="fa fa-download"></i> Download OSGeo4W 64bit version 1](https://download.osgeo.org/osgeo4w/osgeo4w-setup-x86_64-v1.exe)
*  [<i class="fa fa-download"></i> Download OSGeo4W 32bit version 1](https://download.osgeo.org/osgeo4w/osgeo4w-setup-x86-v1.exe)

The following install modes are offered (see also the dedicated [wiki page](https://grasswiki.osgeo.org/wiki/Installation_Guide#OSGeo4W_installer) for further details):

##### Express Desktop Install mode:

Run the downloaded installer as administrator and select the **grass** (stable) or **grass-daily** (development) packages to install. All needed dependencies (e.g. GDAL, common python packages) will be automatically downloaded.

##### Advanced Install mode:
All packages can be individually selected and additional useful packages (e.g. python-pandas, msys) are available, too.

##### Command line mode:
Installation can also be done through command line, as shown below:

<pre style="background-color:#CCCCCC">
osgeo4w-setup.exe -q -k -P grass -s https://download.osgeo.org/osgeo4w/v2/x86_64/
</pre>

##### QGIS users:
In order to have GRASS GIS support (also in QGIS-Processing) as well as the "With GRASS" shortcut you need to install the "qgis-grass-plugin*" packages.
