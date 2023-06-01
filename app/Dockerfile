FROM ubuntu:18.04

RUN apt-get update
RUN apt-get install -y nginx

WORKDIR /var/www/html/
COPY ./webpage .


EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
