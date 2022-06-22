from php:7.2-apache

RUN apt-get update \  
&& apt-get install git mariadb-client -y \  
&& apt-get clean

RUN docker-php-ext-install mysqli
RUN docker-php-ext-enable mysqli
