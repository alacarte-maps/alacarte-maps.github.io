.. title: alaCarte 0.3.0 released
.. date: 2013-08-05 00:37
.. lang: en
.. tags: releases
.. slug: alacarte-0.3.0
.. author: Florian Jacob
.. description: Today the first fully open source developed version of alaCarte was released.

After a long time since the last release, the `0.3.0 release`_ has seen a lot of work.

Highlights of the new version:

- Near complete support for MapCSS styling attributes
- Rendering of 4x4 tiles ("meta tiles") at the same time to gain speed (and visual quality)
- Reduced memory consumption thanks to using a STR-Tree for rectangle queries

Of course there were many small fixes and improvements as well. In total 229 files where modified, 4521 lines of code where added and 3996 lines deleted.

This release would not have been possible without our many new contributers.
Especially thanks to `Dmitry "AMDmi3" Marakasov`_ for his work on extending the MapCSS support and `Mixaill`_ for the MinGW support.

.. _`Dmitry "AMDmi3" Marakasov`: http://github.com/AMDmi3

.. _`Mixaill`: http://github.com/Mixaill

.. _`0.3.0 release`: https://github.com/alacarte-maps/alacarte/releases/tag/v0.3.0
