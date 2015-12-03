
# Dockerized-PHP-FPM-NGINX-MYSQL

> Dockerized PHP development stack:  PHP-FPM, NGINX, MYSQL. Inspired form PHP DOCKERIZED

[![Build Status](https://travis-ci.org/kasperisager/php-dockerized.svg)](https://travis-ci.org/kasperisager/php-dockerized)

Dockerized-PHP-FPM-NGINX-MYSQL tries to replicate the LAMP stack to kick off your full stack PHP project. This method is inspired from the Dockerized PHP which has even more feature So if you want to use it to fullest then please use Dockerized PHP.

## Following official images are used.

* [Nginx](http://nginx.org/)
* [MySQL](http://www.mysql.com/)
* [PHP-FPM](http://php-fpm.org/)

## Required Docker tools

* [Docker Engine](https://docs.docker.com/installation/)
* [Docker Compose](https://docs.docker.com/compose/)
* [Docker Machine](https://docs.docker.com/machine/) (Mac and Windows only)

## Running

After all the docker tools are setup, please run the following command

```sh
$ docker-compose up
```

You can now run the app in the browser. Go to http://Docker-Machine-IP:Selected Port

## License

Copyright &copy; 2015-16 [Babish Shrestha]. Licensed under the terms of the [MIT license](LICENSE.md).

