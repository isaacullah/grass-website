---
title: "Docker"
date: 2020-10-10T11:02:05+02:00
description: "Download GRASS GIS Docker images"
weight: 4
layout: "os"
---

  
#### Quick links

[ [**GRASS GIS 8.0 (current)**](#GRASS-GIS-current) | [**GRASS 7.8 (legacy)**](#GRASS-GIS-old) | [**GRASS 8.2 (preview)**](#GRASS-GIS-devel) ]

<div class="alert rounded-0 alert-default">
<i class="fa fa-arrow-right"></i> GRASS GIS <b>Docker images</b> provided and maintained by <a href="https://www.mundialis.de/en/" target="_blank">mundialis</a>.
</div>

For a version matrix (GRASS GIS, PROJ, GDAL, PDAL), see [here](https://github.com/OSGeo/grass/blob/master/docker/README.md)

<hr>

### <a name="GRASS-GIS-current"></a> GRASS GIS 8.0.1 (current)

<div class="alert rounded-0 alert-success">
<i class="fa fa-info-circle"></i> The following Docker images are generated from the <b>GRASS GIS releasebranch_8_0</b> (<a href="https://trac.osgeo.org/grass/wiki/Grass8/NewFeatures80">GRASS GIS 8.0 new features</a>)</div>

*  [<i class="fa fa-download"></i> Alpine based](https://hub.docker.com/r/mundialis/grass-py3-pdal/tags?page=1&name=alpine) (<small>190 MB, with Python 3 and PDAL</small>)
    <pre><code class=dockerfile">docker pull mundialis/grass-py3-pdal:8.0.1-alpine</code></pre>

*  [<i class="fa fa-download"></i> Debian 10 based](https://hub.docker.com/r/mundialis/grass-py3-pdal/tags?page=1&name=debian) (<small>1.2 GB, with Python 3 and PDAL</small>)
    <pre><code class="dockerfile">docker pull mundialis/grass-py3-pdal:8.0.1-debian</code></pre>

*  [<i class="fa fa-download"></i> Ubuntu 18.04 based](https://hub.docker.com/r/mundialis/grass-py3-pdal/tags?page=1&name=ubuntu) (<small>1.3 GB, with Python 3 and PDAL</small>)
   <pre><code class="dockerfile">docker pull mundialis/grass-py3-pdal:8.0.1-ubuntu</code></pre>


<hr>


### <a name="GRASS-GIS-old"></a> GRASS GIS 7.8.7 (legacy)

<div class="alert rounded-0 alert-warning">
<i class="fa fa-info-circle"></i> The following Docker images are generated from the <b>GRASS GIS releasebranch_7_8</b> (<a href="https://trac.osgeo.org/grass/wiki/Grass7/NewFeatures78">GRASS GIS 7.8 new features</a>)</div>

*  [<i class="fa fa-download"></i> Alpine based](https://hub.docker.com/r/mundialis/grass-py3-pdal/tags?page=1&name=alpine) (<small>190 MB, with Python 3 and PDAL</small>)
    <pre><code class=dockerfile">docker pull mundialis/grass-py3-pdal:7.8.7-alpine</code></pre>

*  [<i class="fa fa-download"></i> Debian 10 based](https://hub.docker.com/r/mundialis/grass-py3-pdal/tags?page=1&name=debian) (<small>1.2 GB, with Python 3 and PDAL</small>)
    <pre><code class="dockerfile">docker pull mundialis/grass-py3-pdal:7.8.7-debian</code></pre>

*  [<i class="fa fa-download"></i> Ubuntu 18.04 based](https://hub.docker.com/r/mundialis/grass-py3-pdal/tags?page=1&name=ubuntu) (<small>1.3 GB, with Python 3 and PDAL</small>)
   <pre><code class="dockerfile">docker pull mundialis/grass-py3-pdal:7.8.7-ubuntu</code></pre>

<hr>


### <a name="GRASS-GIS-devel"></a> GRASS GIS 8.2.0 (preview)

<div class="alert rounded-0 alert-info">
<i class="fa fa-info-circle"></i> The following Docker images are generated from the <b>GRASS GIS main branch</b>
</div>

*  [<i class="fa fa-download"></i> Alpine based](https://hub.docker.com/r/mundialis/grass-py3-pdal/tags?page=1&name=apline) (<small>190 MB, with Python 3 and PDAL</small>)
    <pre><code class="dockerfile">docker pull mundialis/grass-py3-pdal:latest-alpine</code></pre>

*  [<i class="fa fa-download"></i> Debian 10 based](https://hub.docker.com/r/mundialis/grass-py3-pdal/tags?page=1&name=debian) (<small>1.2 GB, with Python 3 and PDAL</small>)
   <pre><code class="dockerfile">docker pull mundialis/grass-py3-pdal:latest-debian</code></pre>

*  [<i class="fa fa-download"></i> Ubuntu 18.04 based](https://hub.docker.com/r/mundialis/grass-py3-pdal/tags?page=1&name=ubuntu) (<small>1.3 GB, with Python 3 and PDAL</small>)
   <pre><code class="dockerfile">docker pull mundialis/grass-py3-pdal:latest-ubuntu</code></pre>
