AndroidCMWrench
===============

AndroidCMwrench set of ant scripts are meant to be executed after your IDE has 
executed its incremental build. They are not at this time meant to be used in 
a Contiuous Integration Server environment.

Website and Example
==================

You can see an example and the website explaining everything at:

[AndroidCMWrench website](http://shareme.github.com/AndroidCMWrench/)


If You Do Not Have Eclipse
======================

Relax, as long as your IDE has abox in your run-as ant conrfiguration that 
says somthing to the effect run project build before executing the ant
script you are fine and can just right click the androdicmwrench.xml file and 
do run-as-antscript.

To Use
======
Obviously, move all the tool accessory files/folders to your project root.
Edit local.porperties and put in yoru paths to android jars, see the template.
Also, change the project name at project root in the androidcmwrench.xml file
to reflect your project name.

Whether, you set this as builder to be for the IDE to run after the project builds
automatically will depend upon the project type and size of project and 
number of android project libraries. Obviously, if its big you might not want to and
only right-click and execute it manually.

Releases
========

Alpha 1.0 1-26-2012


License
=======

Apache Licesne 2.0


Resources
=========

[My blog on android development](http://fredgrott.wordpress.com)
