kibana-4-deb
============

Debian packages for Kibana 4

These use start-stop-daemon to package the kibana 4 tar.gz into a regular debian service.

Files are installed into /usr/share/kibana

There aren't any depenendencies setup so obviously you would need to have Java.

To build run:
mvn package

