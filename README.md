mihailbinev/php7-fpm
====================

With 

* Supervisor, to manage the PHP-FPM

PHP extensions:

* bcmath
* ctype
* dom
* gettext
* intl
* json
* mbstring
* mcrypt
* mysqli
* opcache
* pcntl
* pdo
* pdo_mysql
* pdo_pgsql
* pdo_sqlite
* simplexml
* shmop
* xml
* zip

Build and run
-------------

```sh
docker build -t php7 .

docker run --rm -it php7

# to find the running container id with image name "php7"
docker ps

# after that you can enter the container
docker exec -it <container id here> /bin/bash
```

