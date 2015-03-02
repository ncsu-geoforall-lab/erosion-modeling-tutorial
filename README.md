Erosion modeling tutorial
=========================

This is repository for tutorial for erosion modeling in GRASS GIS and ArcGIS.

Updating the website
--------------------

This repository is using GitHub pages to publish thw website.
`master` branch has the same content as `gh-pages` branch.

If you have a separate clone for `gh-pages` branch use the following
commands to update the website:

    git pull
    git merge master
    git push

If you don't keep separate clone just for the `gh-pages` branch, you can
use the following commands to update the website:

    git pull
    git checkout gh-pages
    git merge master
    git push
    git checkout master

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
