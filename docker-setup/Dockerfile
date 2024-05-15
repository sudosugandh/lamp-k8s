FROM php:7.4-apache

# Install MySQL extensions
RUN docker-php-ext-install mysqli pdo pdo_mysql

COPY src/ /var/www/html/
RUN chown -R www-data:www-data /var/www/html
