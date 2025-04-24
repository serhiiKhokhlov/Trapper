=================
 TRAPPER client
=================

Overview
--------

**trapper-client** is a `kivy <https://kivy.org/>`_ application written in `Python3 <https://www.python.org/>`_ which helps with creating camera trapping data packages compatible with `TRAPPER <https://gitlab.com/oscf/trapper-project>`_ system, an open source web-based application to manage camera trapping projects. You can use **trapper-client** to communicate with TRAPPER directly, i.e. to organize pictures and videos recorded by your camera traps into structured data packages and to upload them to TRAPPER server. The app contains tools that facilitate processing of large collections of raw camera trapping data. Using this app you can:

**CONVERT**: convert raw video files (e.g. AVI) into one of web-friendly video formats (e.g. mp4, webm)

**PACKAGE**: generate data packages which are .zip files with accompanying package definition files (YAML); these packages are further used by TRAPPER to automatically link uploaded files to corresponding deployments and to update database with records primary metadata

**UPLOAD**: upload data packages to a server via FTP protocol; uploaded data packages are placed on a server in a dedicated directory associated with a TRAPPER's user profile

To setup the entire process properly all raw camera trapping data should be stored in one directory (e.g. project) with collections of recorded files (e.g. recording sessions) as its sub-directories. Each collection can have another level of sub-directories aggregating data into deployments (e.g. an array of camera traps deployed during a session) with names of these directories corresponding to codes of deployments as defined in TRAPPER database.


Documentation
-------------

`<https://trapper-client.readthedocs.io>`_


Contribute
----------

- Issue Tracker: `<https://gitlab.com/oscf/trapper-client/issues>`_
- Source Code: `<https://gitlab.com/oscf/trapper-client>`_  

  
Support
-------

If you are having issues, please let us know:

contact@os-conservation.org

We also have a mailing list:

trapper-project@googlegroups.com

https://groups.google.com/d/forum/trapper-project


TRAPPER gitlab repository
------------------------------

`<https://gitlab.com/oscf/trapper-project>`_

Read more about TRAPPER
-----------------------

Bubnicki, J. W., Churski, M. and Kuijper, D. P. (2016), TRAPPER: an open source web‐based application to manage camera trapping projects. Methods Ecol Evol, 7: 1209-1216. doi:10.1111/2041-210X.12571

`<https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12571>`_

For more news about TRAPPER please visit the Open Science Conservation Fund (OSCF) website:

`<https://os-conservation.org>`_


License
-------

Copyright (C) 2023 Open Science Conservation Fund (OSCF)

TRAPPER-CLIENT is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

TRAPPER-CLIENT is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with TRAPPER-CLIENT. If not, see http://www.gnu.org/licenses/.
