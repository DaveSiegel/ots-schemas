# ots-schemas
Automatically exported from code.google.com/p/ots-schemas

OTS-Schemas is a Java library for reading and writing common library XML schemas. It currently supports PREMIS, MODS, TextMD, DocumentMD, MIX, AES AudioObject, METS (partial support), and several custom formats. It is developed as part of the Harvard University Library Digital Repository Service (DRS), an access and preservation repository.

Please note that this should be considered beta software. The MIX and MODS sub-packages perform checking of schema-restricted values during runtime. However, in memory validation for parsed XML and objects built from scratch, is not yet supported.

Java 1.6 is required. See the JUnit tests included in the download for usage examples.

OTS-Schemas uses the following open source libraries:

JDOM (Apache-like license, modified Apache version 1.1) http://code.google.com/p/fits/wiki/jdom_license

staxmate http://staxmate.codehaus.org/ (BSD (new version)) http://www.opensource.org/licenses/bsd-license.php

stax2 http://docs.codehaus.org/display/WSTX/StAX2 (LGPL version 2.1) http://www.gnu.org/licenses/licenses.html#LGPL

Woodstox http://docs.codehaus.org/display/WSTX/Home (LGPL version 2.1) http://www.gnu.org/licenses/licenses.html#LGPL

xercesImpl http://xerces.apache.org/xerces2-j/ (Apache Public License version 2) http://www.opensource.org/licenses/apache2.0.php

xml-apis xml-apis http://xml.apache.org/commons/ (Apache Public License version 2) http://www.opensource.org/licenses/apache2.0.php

xmlunit xmlunit (BSD (new version)) http://www.opensource.org/licenses/bsd-license.php


The source code for each of the above libraries is available on their websites.

To get started see the User Guide.
