FROM oraclelinux:8.3

MAINTAINER sonu

RUN yum install httpd -y

COPY index.html training.html trainer.html  /var/www/html/

CMD [ "httpd", "-DFOREGROUND" ] 
