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

##ESPAÑOL##
El Sistema de Análisis y Gestión Espectral (SAMS) es una aplicación Java para gestionar bases de datos y análisis de espectros de campo. Sus características incluyen: opciones de importación/exportación en varios formatos, agrupación de firmas, gestión de metadatos, operaciones comunes en firmas individuales o múltiples, conjunto más amplio de capacidades de trazado, y una estructura de datos simple para una fácil integración con otras aplicaciones.

SAMS fue desarrollado originalmente en el Centro de Tecnologías Espaciales y Teledetección (CSTARS) de la Universidad de California, Davis, y se alojaba en https://projects.atlas.ca.gov/projects/sams/. A partir del 20 de noviembre de 2011, la nueva ubicación del proyecto es en Google Code.

Ten en cuenta que no ha habido actualizaciones significativas en el software o la documentación, y no hay planes concretos para realizar más desarrollos en este momento. Sin embargo, como proyecto de código abierto, podrías estar interesado en ayudar a mantener alguna forma de actividad, por ejemplo, compartiendo experiencias que hayas tenido con el sistema o enlaces útiles (el grupo de Google sería un buen espacio para este tipo de información). Algo que ha sido necesario, durante mucho tiempo, es una documentación actualizada que refleje la versión 3.2 del software; ¡avísanos si tienes tutoriales o materiales para compartir! Para aquellos más inclinados al desarrollo, la nueva ubicación debería facilitar las cosas bastante; siéntete libre de solicitar unirte al proyecto o clonar la base de código, etc.

A continuación, se presentan notas de los sitios originales.

Requisitos de instalación: Se requiere un entorno de ejecución de Java (JRE), versión 1.4 o superior, en tu sistema. Puedes descargar un JRE desde http://java.com/. Descarga el instalador de SAMS desde la página de descargas, por ejemplo, install-sams-XXXX.jar. Ejecuta el instalador: ten en cuenta que el instalador de SAMS es un "archivo JAR ejecutable". En algunos sistemas, será suficiente con hacer doble clic en el instalador desde una ventana del explorador de archivos para ejecutarlo. Si esto no funciona, puedes ejecutar el instalador manualmente de la siguiente manera: abre una ventana de comandos (símbolo del sistema / consola / terminal) e ingresa lo siguiente en el símbolo del sistema: java -jar install-sams-XXXX.jar. Luego, sigue las instrucciones del instalador de SAMS. Básicamente, deberás especificar un directorio donde se instalará el sistema SAMS. (Usuarios de Windows: eviten una ubicación que contenga espacios en la ruta).

Registro de cambios Cambios en 3.2

Mejorado el soporte para conjuntos de datos ENVI. Ahora se admiten los siguientes tipos de datos: Byte, Int16, UInt16, Int32, UInt32, Float32 y Float64. También se reconocen el orden de bytes Intel y IEEE de red al importar firmas desde conjuntos de datos ENVI. Ahora se puede especificar un patrón de sufijo para nombrar las firmas importadas desde un archivo ASCII. Las operaciones script ahora se pueden recargar desde la interfaz gráfica de usuario (GUI). Nueva operación basada en referencia para calcular la radiancia a partir de la reflectancia y la irradiancia espectral total. Se mejoró la operación de muestreo de ancho completo a media altura (FWHM). Cambios en 3.1

Nuevo mecanismo de instalación que permite la creación de accesos directos en algunos sistemas operativos. Cambios en 3.0

Internamente, SAMS ahora utiliza un esquema diferente y más flexible para almacenar bases de datos. Se pueden abrir más de una base de datos simultáneamente, cada una en su propia ventana. Los elementos en la tabla de espectros ahora se pueden ordenar y filtrar. La creación de grupos se ha vuelto a implementar para permitir criterios más generales. Un grupo se especifica como una lista de expresiones. Las expresiones pueden tener diferentes formas, siendo el nombre de un atributo muy común. Los grupos se crean según diferentes valores de expresiones dadas. Mejor informe de progreso en operaciones largas: las ventanas de diálogo muestran lo que se está haciendo, las firmas involucradas y los mensajes de error. "pegar" ahora es una copia real de firmas. ("pegar referencia" ya no está disponible.) Derechos de autor (c) 2002-2005 Los Regentes de la Universidad de California. Todos los derechos reservados.

Se concede el permiso, sin acuerdo escrito y sin tarifas de licencia o regalías, para usar, copiar, modificar y distribuir este software y su documentación con cualquier propósito, siempre que el aviso de derechos de autor anterior y los dos párrafos siguientes aparezcan en todas las copias de este software.

EN NINGÚN CASO LA UNIVERSIDAD DE CALIFORNIA SERÁ RESPONSABLE ANTE NINGUNA PARTE POR DAÑOS DIRECTOS, INDIRECTOS, ESPECIALES, INCIDENTALES O CONSECUENTES DERIVADOS DEL USO DE ESTE SOFTWARE Y SU DOCUMENTACIÓN, INCLUSO SI LA UNIVERSIDAD DE CALIFORNIA HA SIDO ADVERTIDA DE LA POSIBILIDAD DE TALES DAÑOS.

LA UNIVERSIDAD DE CALIFORNIA RENUNCIA EXPRESAMENTE A CUALQUIER GARANTÍA, INCLUYENDO, PERO NO LIMITADO A, LAS GARANTÍAS IMPLÍCITAS DE COMERCIABILIDAD Y APTITUD PARA UN PROPÓSITO PARTICULAR. EL SOFTWARE PROPORCIONADO EN VIRTUD DE ESTE DOCUMENTO SE OFRECE "TAL CUAL", Y LA UNIVERSIDAD DE CALIFORNIA NO TIENE OBLIGACIÓN DE PROPORCIONAR MANTENIMIENTO, SOPORTE, ACTUALIZACIONES, MEJORAS O MODIFICACIONES.
