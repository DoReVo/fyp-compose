FROM php:7.4-apache

RUN docker-php-ext-install pdo pdo_mysql
RUN chown -R www-data:www-data /var/www
RUN chmod -R 755 /var/www
RUN a2enmod rewrite