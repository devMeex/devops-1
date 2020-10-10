FROM ubuntu:16.04 AS base
RUN apt-get update && apt-get -y install nginx
WORKDIR /var/www/html
COPY ./web .
ENTRYPOINT ["nginx", "-g", "daemon off;"]