DLPR - a DMENU LPR file printer
==============

Copyright
-------------

magnific0 http://www.github.com/magnific0 (c) Copyright 2012
Licenced under the GPLv3

About
--------------

DLPR is a small script that lets the user print a file by selecting a printer 
and setting the options with DMENU. This script operates lpoptions and lpr 
command-line utilities supplied with any CUPS installation. The program will 
therefore directly print PDF and PS files. 

Installation
--------------

You can run (as any user that is allowed to generate print jobs) without
installation. However if you want to install the script onto your system you can
simply run:

        sudo make install

Usage
--------------

From command-line run:

	dlpr [ files(s) ]

and select your printer from the DMENU interface. Subsequently set options 
untill satisfied. DMENU will exit and your job will be send to the printer.

Example:

	dlpr file.pdf


