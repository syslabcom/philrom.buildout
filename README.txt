Recensio buildout
=================

This buildout largely follows the gocept standard.
That means, all important buildout configs are in the profile folder.

Extras
======

versions
--------
The dev buildout provides a script for checking newer versions of eggs:
./bin/checkversions profiles/picked_versions.cfg -v
This returns newer versions if available.
