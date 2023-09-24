FROM php:8.0-apache
COPY . /var/www/html

RUN apt-get update

EXPOSE 80

RUN a2enmod rewrite
RUN a2enmod cgi

CMD ["apache2-foreground"]