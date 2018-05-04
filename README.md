GDAL - Geospatial Data Abstraction Library
====

GDAL is an open source X/MIT licensed translator library for raster and vector geospatial data formats. This is a mirror of the GDAL Subversion repository.

* Main site: http://www.gdal.org - Developer and user docs, links to other resources
* SVN repository: http://svn.osgeo.org/gdal
* Download: ftp://ftp.remotesensing.org/gdal, http://download.osgeo.org/gdal
* Wiki: http://trac.osgeo.org/gdal - Bug tracking, various user and developer contributed documentation and hints
* Mailing list: http://lists.osgeo.org/mailman/listinfo/gdal-dev

## Howto 

```bash
cd gdal

./configure --prefix=/usr --sysconfdir=/etc --with-libkml --with-libjson-c=internal
make
./configure --prefix=/usr --sysconfdir=/etc --with-libkml
make
sudo make install
```

Is it stupid? yes. Does it work? yes.