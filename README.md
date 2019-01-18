# precedent

LAMP in docker

We have three containers.

First: Ubuntu based on nginx: the last

Second: php-fpm version 7.2

Third: mysql version 5.7

Containers are builded automatically using a docker-compose.

In all containers ports are forwarded: 80, 9000 and 3306, respectively.

To run, just do:

docker-compose up

For check:
<ip_addreess_server> - in the browser returns infophp page

<ip_addreess_server> /test_mysql.php
- should return a successful database connection page
