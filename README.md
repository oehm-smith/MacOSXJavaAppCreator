MacOSXJavaAppCreator
====================

Nothing too amazing here.  Just a script or two and some instructions on creating Java Apps for Macs using Maven.  

First is the script buildIcns.sh that uses 'sips' to create icon sized files (all Mac systems have this installed on it).  

Next is the advice to use Maven and add the [http://mojo.codehaus.org/osxappbundle-maven-plugin](http://mojo.codehaus.org/osxappbundle-maven-plugin) to create the .dmg file.

I will modify the script to use Maven properties for the location of the graphic etc...

