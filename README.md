pyflat
======

Python loader for Omicron Flat File Format

This script parse the Omicron Matrix Flat File Format to return a python
object containing the measured data in physical units and all the relevant
measurement parameters in a multi-level dictionnary. The implementation simply
follows the Omicron Flat File Format documentation.

Infos
-----
flatFile.py written by François Bianco, University of Geneva - francois.bianco@unige.ch

Usage
-----
See example log for a very rough and basic example.


Copyright
---------
Copyright © 2009-2013 François Bianco, University of Geneva - francois.bianco@unige.ch

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Updates
-------

2013-01 fbianco:
    added support for Matrix 3.1-1 which breaks the axis keys naming
2011-11 fbianco:
    restructuring code
2011-08-05 fbianco:
    code cleaning
2009-05-06 fbianco:
    converted to a module
2009-03-17 fbianco:
    added drawing capabilities
2008-11-21 fbianco:
    first version