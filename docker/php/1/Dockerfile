FROM php:8.1-fpm

RUN mkdir /var/www/app

RUN sed -i 's/listen = 127.0.0.1:9000/listen = 127.0.0.1:9001/' /usr/local/etc/php-fpm.d/www.conf
RUN sed -i 's/listen = 127.0.0.1:9000/listen = 127.0.0.1:9001/' /usr/local/etc/php-fpm.d/www.conf.default
RUN sed -i 's/listen = 9000/listen = 9001/' /usr/local/etc/php-fpm.d/zz-docker.conf

EXPOSE 9001
