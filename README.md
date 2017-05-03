# osm-import-scripts

This is a simple shell script for importing osm data into postgis database.
It automates postgresql database drop/creation, downloading and importing data via osm2pgsql. 

Script expects to find `osm-import.conf` in the current directory or in /etc/

PostgreSQL credentials should be configured in ~/.pgpass. Postgres superuser rights are required.
