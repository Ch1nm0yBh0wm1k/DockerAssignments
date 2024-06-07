FROM ubuntu:latest
LABEL maintainer="ch1nm0y"
RUN apt-get update && apt-get install -y apache2
COPY static-website-example /var/www/html/
EXPOSE 80
CMD ["apache2ctl","-D","FOREGROUND"]
