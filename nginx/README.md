# nginx Docker files

Configures nginx with SSL and HTTP/2 and some optimizations. The *vhost* uses the `/var/www/public` folder, sou you can
mount your application to `/var/www/`. See [prooph/proophessor-do app](https://github.com/prooph/proophessor-do) for an
example.

## nginx www
Use the following image: `prooph/nginx:www`.

## nginx with Zend Z-Ray
Use the following image: `prooph/nginx:zray`.

[Zend Z-Ray](http://www.zend.com/de/products/server/z-ray) is a PHP Profiler and is used together with
one of the `prooph/php:[version]-fpm-zray` Docker images.