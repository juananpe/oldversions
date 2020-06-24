This is a  docker-compose file for joomla OLD versions (they have security issues, don't use in production!). 
Parts of this repo are taken from the official joomla docker repo.

## How-to run

You need to install [docker-compose](https://docs.docker.com/compose/install/) then clone this repository or take just the docker-compose file. In the file you may change the logins and passwords then fire it up with `docker-compose up`

You should be able then to access the joomla installation at http://localhost:8080 . In the database configuration dialog choose `mysql` as the `Host Name` and insert username, password and database name like it is configured in the docker-compose file.


