GEOSFileViewer
==============

A GUI application for viewing and converting GEOS document files.


Copyright (C) 2016, Daniel England.
All Rights Reserved.  Released under the GPL.

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more
details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <http://www.gnu.org/licenses/>.


Introduction
------------

GEOS is an operating system that is run on a C64, C128 or Apple IIe.  It is a
GUI OS which was quite remarkable at the time given the constraints of its
target systems.

GEOS was supplied with the fantastic applications geoPaint and geoWrite which
allowed you to create picture and text documents.  This application allows you
to view these documents as well as GEOS fonts and get detailed information on
any GEOS file.


Usage
-----

The usage is simple.  Select File | Open... to open either a .d64, .d71 or .d81
disk image file.  You will be presented with a list of GEOS files.  Selecting a
file will display an in-depth view of the file's details in a number of tabs.

Use the View menu to view the additional file viewers available for the selected
file's type.  Presently, there is a text only viewer for geoWrite documents,
an image viewer for geoPaint documents and an interactive font viewer for GEOS
fonts.


Compiling
---------

You need FPC and Lazarus to compile GEOSFileViewer.  You can get Lazarus (which
includes FPC) for your platform from the following address:

        http://www.lazarus-ide.org/

At the time of writing, I am using Lazarus version 1.6 but earlier versions
should be supported so long as they have FPC version 2.1 or higher.

Several platforms are supported, including Windows, Linux and MacOSX.  32bit or
64bit compilation should be supported, depending upon your requirements.

To compile, open the "GEOSFileViewer.lpi" file in Lazarus and select
Run | Build.  You can switch the Build Mode by using the Compiler Project
Options under Project | Project Options | Compiler Options and selecting either
the Release or Debug Build Mode.

Delphi is presently unsupported due to the extensive use of Lazarus features.


Contact
-------

I can be contacted for further information regarding this tool at the following
address:

        mewpokemon {you know what goes here} hotmail {and here} com

Please include the word "GEOSFileViewer" in the subject line.

Thanks for using GEOSFileViewer!



Daniel England.
