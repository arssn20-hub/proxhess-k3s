FROM php:8.2-apache

#activation des extensions PHP utiles
RUN docker-php-ext-install mysqli pdo pdo_mysql

#copue du code source vers le dossier web apache
COPY src/ /var/www/html/

#affectation des droits sur le dossier
RUN chown -R www-data:www-data /var/www/html 
