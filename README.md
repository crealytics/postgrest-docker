# postgrest-docker

**DEPRECATED**
There is now an official [docker image](https://hub.docker.com/r/begriffs/postgrest/)


Dockerfile for a [postgrest](http://postgrest.com/) instance

Copied and adapted from https://github.com/begriffs/postgrest/issues/408

Expects the following env variables:

* POSTGREST\_DBHOST
* POSTGREST\_DBPORT
* POSTGREST\_DBNAME
* POSTGREST\_DBUSER
* POSTGREST\_DBPASS
* POSTGREST\_SCHEMA\_NAME

The postgrest instance is exposed on port 3000 in the container.
