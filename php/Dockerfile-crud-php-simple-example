FROM php:7.4-apache

# Enable the headers module
RUN a2enmod headers
RUN a2enmod rewrite
RUN docker-php-ext-install mysqli
