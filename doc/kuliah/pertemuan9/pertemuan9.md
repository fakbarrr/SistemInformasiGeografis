Background

MapServer is an Open Source application that enables a map data accessed via the web. This technology was first developed by the University of Minesotta United States. MapServer presence makes the job of creating the Digital Map becomes easier and interactive. Interactive map here means that users can easily view and change the map display such as zoom, rotate, and display information (such as displaying road info) and analysis (such as determining the route of travel) on the surface of geography.

Discussion Problems And Solutions

installation Mapserver

MapServer installation phase is explained in this chapter.

Centos 6

Perform installation of MapServer through elgis repository by adding the repository elgis first, before elgis repo repo deals Epel

# Rpm -Uvh http://download.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
# Rpm -Uvh http://elgis.argeo.org/repos/6/elgis-release-6-6_0.noarch.rpm

An error occurred in the library armadillo in Epel. Exclude armadillo of repo Epel because it will cause an error. edit file epel.repo add exclude = armadillo and armadillo install or download through other repo manual.
