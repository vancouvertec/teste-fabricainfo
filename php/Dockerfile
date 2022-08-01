FROM php:7.2.4-apache

RUN apt update && apt install -y zlib1g-dev g++ libicu-dev zip libzip-dev zip libpq-dev \
    && docker-php-ext-install intl opcache pdo pgsql pdo_pgsql \
    && pecl install apcu \
    && docker-php-ext-enable apcu \
    && docker-php-ext-configure zip \
    && docker-php-ext-install zip \
    && apt-get install -y git \
    && apt-get install vim \
    && a2enmod rewrite


WORKDIR /var/www/html
RUN chmod 777 /var/www/html
RUN mkdir storage
RUN chmod 777 -R storage
RUN chown -R www-data:www-data storage
USER root
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
EXPOSE 80

