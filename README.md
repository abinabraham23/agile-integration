Agile Integration Technical Overview Materials
==============================================

The Purpose of this Repository
------------------------------

The source code and other files in this repository are supposed to be used as
companions to the Agile Integration Technical Overview recorded with Red Hat in
August 2019.

Content and Structure
---------------------

There are essentially three technologies we are showcasing:

 - Red Hat AMQ
 - Red Hat Fuse (with Apache Camel)
 - Red Hat Thorntail (with a simple REST API provider)

Each of the above lives in a separate subdirectory with accompanying source
code and documentation in their respective locations.

Due to the data model sharing between the Fuse and Thorntail projects, an
additional project was created, called ``model``, which basically only contains
a couple of classes used by both projects.

Additionally, there is a simple dummy PHP app that can be used to showcase
OpenShift language detection, image building, and deployment capability.

Copyright, Copying & License
----------------------------

Copyright (c) Grega Bremec <gregab@p0f.net>, 2019
All rights reserved.

See the LICENSE file in this directory for more information.

