FROM php:fpm-alpine
RUN docker-php-ext-install opcache mysqli
COPY php/production/opcache.ini /usr/local/etc/php/conf.d/opcache.ini
COPY php/php.ini /usr/local/etc/php/php.ini
COPY ./data/ /var/www/html
