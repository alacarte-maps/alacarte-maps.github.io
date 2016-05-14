<!-- 
.. title: About alaCarte
.. slug: about
.. date: 2013-04-18 19:22:00 UTC+01:00
.. type: text
-->

alaCarte is a tile renderer for OpenStreetMap data written in C++11, using Cairo for
rendering and Boost-Spirit for [MapCSS](http://wiki.openstreetmap.org/wiki/MapCSS) parsing.

The rendered tiles are served over HTTP using the [Slippy map tilename](http://wiki.openstreetmap.org/wiki/Slippy_map_tilenames) convention.

To compute which data is needed for rendering a tile, alaCarte uses a variant of
a kd-Tree.

alaCarte was designed with medium dataset size in mind. On a typical machine with
at leat 8GB RAM, alaCarte can handle a unfiltered export from the federal state
of Baden-Wuerttemberg (Germany).

alaCarte was developed as part of a software project at [KIT](http://algo2.iti.kit.edu).
For the old project files (mostely in German) see the [old project repository](https://bitbucket.org/TheMarex/alacarte).

## Features ##

* easy to use
* most MapCSS attributes are implemented
* no need to filter OSM exports, you have full access to all attributes at runtime
* stylesheets are updated at runtime (changes are detected automatically)
* tiles can be rendered in groups ("meta tile") to speed up rendering
