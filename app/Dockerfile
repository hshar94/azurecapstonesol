FROM ubuntu:16.04
RUN apt-get update
RUN apt-get -y install apache2
COPY ./index.html /var/www/html
CMD apachectl -D FOREGROUND
