.. title: alaCarte 0.2.1 released
.. slug: alacarte-0.2.1
.. date: 2013-04-10 23:46:00
.. tags: releases
.. author: Florian Jacob
.. lang: en
.. link: https://github.com/alacarte-maps/alacarte/releases/tag/v0.2.1
.. description: Today we published alaCarte, our student lab course project we worked countless hours on in the last semester,
   as open source software.

.. figure:: /images/screenshot.thumbnail.png
   :target: /images/screenshot.png
   :class: thumbnail
   :alt: AlaCarte Screenshot


What is alaCarte?
=================

alaCarte is a tile renderer for OpenStreetMap data written in C++11, using Cairo for rendering and Boost-Spirit for MapCSS parsing.

The rendered tiles are served over HTTP using the Slippy map tilename convention.

To compute which data is needed for rendering a tile, alaCarte uses a variant of a kd-Tree.

alaCarte was designed with medium dataset size in mind. On a typical machine with at leat 8GB RAM, alaCarte can handle a unfiltered export from the federal state of Baden-Wuerttemberg (Germany).

alaCarte was developed as part of a student software project at KIT.

We have a `live demo`_, you can check out the code at `github`_ and if you speak German you can view the slides of the
`finishing presentation`_ of the project.


.. _`live demo`: http://studwww.ira.uni-karlsruhe.de/~s_scheir/alacarte/

.. _`github`: https://github.com/alacarte-maps/alacarte

.. _`finishing presentation`: http://studwww.ira.uni-karlsruhe.de/~s_scheir/alacarte/abschlusspraesentation
