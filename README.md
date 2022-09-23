# BKChem
BKChem is a 2D molecular drawing program.

This repository contains a fork based on the v0.14 of the original BKChem software, developed by Reinis Danne. The original website is : official website on http://zirael.org/bkchem/

For more info on program capabilities, install instructions etc. see
documentation in directory "doc" in the main BKChem directory 

BKChem is free software and is distributed under GNU GPL. The program is
provided as is without warranty of any kind. For details see the
file "gpl.txt".

## Installation

For installation instructions see the file INSTALL in main BKChem directory.
 
## Notes

* Piddle sources are shipped together with BKChem. Piddle is a library provided under the GPL license and seems to be dead since several years. Therefore it was decided to put it inside BKChem sources and distribute any eventual additions this way. In case any major changes will be made Piddle will be released as a standalone library.
* Pmw (http://pmw.sourceforge.net/) sources (version 1.2) are shipped together with BKChem. There were needed some minor fixes in Pwm and as it is a library provided under the GPL license and seems to be dead it was decided to put it inside bkchem sources and distribute the fixed version this way.
* The official InChI software from IUPAC is bundled in a binary form together with BKChem in Windows binary builds. All the credit for this nice piece of
software goes to its creators. This information comes with the software:
> Copyright © The International Union of Pure and Applied Chemistry 2005: IUPAC
> International Chemical Identifier (InChI)
> (contact: secretariat@iupac.org)
