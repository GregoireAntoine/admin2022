FROM php:7.2-apache
RUN docker-php-ext-install mysqli pdo pdo_mysql
COPY conf/sites-available /etc/apache2/sites-available
RUN a2ensite b2b.woodytoys.domaineprojetadmin.ovh 
RUN a2ensite woodytoys.domaineprojetadmin.ovh
RUN a2dissite 000-default