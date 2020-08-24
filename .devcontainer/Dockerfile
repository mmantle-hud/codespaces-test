FROM php:7.3-apache
RUN apt-get update && apt-get install libzip-dev && apt-get install -y git zlib1g-dev && docker-php-ext-install pdo pdo_mysql zip
#sudo COPY ./src /var/www/html
#COPY php.ini /usr/local/etc/php/php.ini


# RUN apt-get update && apt-get upgrade -y
# RUN docker-php-ext-install pdo_mysql && docker-php-ext-enable pdo_mysql
