FROM php:7.4.14-apache 

LABEL version="1.0" maintainer="Sony level"
LABEL description="This is a custom image for the Injection challenge. It contains a custom php.ini file."

RUN apt update && \ 
    apt upgrade -y
   
RUN docker-php-ext-install pdo_mysql 
RUN chmod 755 /var/www/html

EXPOSE 80