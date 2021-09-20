# SAMS
## SAMS - Spectral Analysis and Management System

Home

code migrated from an image of the original CVS repo

The Spectral Analysis and Management System (SAMS) is a Java application to manage field spectra databases and analyses. Features include: import/export options in various formats, signature groupings, metadata management, common operations on single or multiple signatures, richer set of plotting capabilities, and a simple data structure for easy integration with other applications.

SAMS was originally developed at the [http://www.cstars.ucdavis.edu/ University of California Davis Center for Spatial Technologies and Remote Sensing (CSTARS)] and hosted at https://projects.atlas.ca.gov/projects/sams/. As of November 20 2011 the new project location is at Google Code.

Please note, there is no any significant update in the software or documentation and there is no concrete plans to make any further development at this point. However, as an open source project, you might be interested in helping keep some form of activity, for example by sharing any experiences you have had with the system or useful links (the [http://groups.google.com/group/cstars-sams google group] would be a good space for this kind of information). Something needed --for quite so long--is updated documentation to reflect the version 3.2 of the software, let us know if you have any tutorials or materials to share! For those more inclined to development, the new hosting should facilitate things quite a bit; feel free to request joining the project or clone the code base, etc.

What follows are notes from the original sites.

Installation
Requirement: A Java Runtime Environment (JRE), version 1.4 or newer, is required on your system. You can download a JRE from http://java.com/.
Download the SAMS installer from the download page, say install-sams-XXXX.jar.
Run the installer: Note that the SAMS installer is an "executable JAR file." On some systems it will suffice to double-click the installer from a file explorer window to execute it. If this does not work, then you can run the installer manually as follows:
Open a command window (DOS prompt / console / terminal)
Enter the following at the command prompt: java -jar install-sams-XXXX.jar
Then follow the SAMS installer instructions. Basically you will need to specify a directory where the SAMS system will be installed. (Windows users: please avoid a location having any spaces in the path.)

Change log
Changes in 3.2

Improved support for ENVI datasets. The following data types are now supported: Byte, Int16, UInt16, Int32, UInt32, Float32, and Float64. Both Intel and network IEEE byte orders are also recognized in importing signatures from ENVI datasets.
A suffix pattern can now be specified to name the signatures imported from an ASCII file.
Scripted operation can now be reloaded from within the GUI interface.
New reference-based operation to compute radiance from reflectance and total spectral irradiance.
FWHM resampling operation improved.
Changes in 3.1

New installer mechanism that allows the creation of shortcuts on some operating systems.
Changes in 3.0

Internally, SAMS now uses a different, more flexible scheme to store databases.
More than one database can be open simultaneously, each on its own window.
Elements in the spectra table can now be sorted and filtered.
Grouping creation has been reimplemented to allow for more general criteria. A grouping is specified as a list of expressions. Expressions may have different forms, the name of an attribute being one very common. Groups are created according to different values of given expressions.
Better progress report in long operations: dialog boxes show what is being done, involved signatures, and error messages.
"paste" is now a real copy of signatures. ("paste reference" is no longer available.)
Copyright
Copyright (c) 2002-2005 The Regents of the University of California. All rights reserved.

Permission is hereby granted, without written agreement and without license or royalty fees, to use, copy, modify, and distribute this software and its documentation for any purpose, provided that the above copyright notice and the following two paragraphs appear in all copies of this software.

IN NO EVENT SHALL THE UNIVERSITY OF CALIFORNIA BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OF THIS SOFTWARE AND ITS DOCUMENTATION, EVEN IF THE UNIVERSITY OF CALIFORNIA HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

THE UNIVERSITY OF CALIFORNIA SPECIFICALLY DISCLAIMS ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE SOFTWARE PROVIDED HEREUNDER IS ON AN "AS IS" BASIS, AND THE UNIVERSITY OF CALIFORNIA HAS NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.
