FROM php:7.4-fpm-alpine3.12
RUN apk add --no-cache libpng libpng-dev && docker-php-ext-install gd && apk del libpng-dev
RUN docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-install mysqli && docker-php-ext-enable mysqli
