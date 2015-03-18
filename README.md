Erosion modeling tutorial
=========================

This is repository for tutorial for erosion modeling in GRASS GIS and ArcGIS.

Updating the website
--------------------

This repository is using custom scripts to build the web site and
GitHub pages to publish the website.
`master` branch contains "raw" files which are build into a website
which is in the `gh-pages` branch.

If you haven't published pages from your computer use:

    ./get-gh-pages-branch.sh

This will create `build` directory with another clone of the repository
but it will be switched to `gh-pages` branch. To build the website
for review use:

    ./build.sh

To publish the website use:

    ./publish.sh


Authors
-------

 * Helena Mitasova, North Carolina State University, NCSU OSGeoREL
 * Anna Petrasova, North Carolina State University, NCSU OSGeoREL
 * Vaclav Petras, North Carolina State University, NCSU OSGeoREL
 * Steve Warren
 * Matt Hohmann
 * Niels G. Svendsen
 * Tom Ruzycki

License
-------

CC BY-SA (http://creativecommons.org/licenses/by-sa/4.0/)
