<!--
.. title: alaCarte 0.4.0 released
.. slug: alacarte-040-released
.. date: 2016-12-28 20:56:01 UTC+01:00
.. lang: en
.. tags: releases, draft
.. slug: alacarte-0.4.0-released
.. type: text
.. description: Today we published alaCarte 0.4.0, with ArchLinux packages and Windows binaries!
-->

![an a la carte menu from japan](/images/alacarte-menu-16-9.jpg)

<!--- git diff (double-hyphen) shortstat v0.3.0 -->
Today we published the [0.4.0 release][] of alaCarte!
In the last three years, quite a few changes accumulated which mainly improve
packaging and using alaCarte. So it was about time, hurray!




## Highlights of the new version: ##

* [Official Windows binaries][]
* For ArchLinux, we now provide the [alacarte-maps AUR package][]
  and the [alacarte-maps-git AUR package][].
* Added documentation for [alacarte-maps-importer][] and [alacarte-maps-server][] binaries in form of man pages.
* Removed dependencies on log4cpp, Cairomm and SigC++.
* Added support for Debian Jessie (as it's the new stable).
* Removed support for Debian Wheezy (as it's now oldstable and its boost version is now too old).

…and of course various bug fixes, build improvements and cleanups.
For details, see the newly-introduced [Changelog][].

If you aren't on Arch Linux or Windows, you can [download the source][]
and follow the [build instructions][] (also found in the included `README.md`).


Happy rendering!

[build instructions]: https://github.com/alacarte-maps/alacarte/tree/v0.4.0#how-to-build
[download the source]: https://github.com/alacarte-maps/alacarte/releases/tag/v0.4.0
[0.4.0 release]: https://github.com/alacarte-maps/alacarte/releases/tag/v0.4.0
[Changelog]: https://github.com/alacarte-maps/alacarte/blob/master/CHANGELOG.md
[alacarte-maps AUR package]: https://aur.archlinux.org/packages/alacarte-maps/
[alacarte-maps-git AUR package]: https://aur.archlinux.org/packages/alacarte-maps-git/
[alacarte-maps-importer]: https://alacarte-maps.github.io/alacarte/manpages/alacarte-maps-importer.1.html
[alacarte-maps-server]: https://alacarte-maps.github.io/alacarte/manpages/alacarte-maps-server.1.html
[Official Windows binaries]: https://github.com/alacarte-maps/alacarte/releases/tag/v0.4.0
