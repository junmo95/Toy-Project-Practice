FROM mysql:latest

MAINTAINER junmo

COPY init.sql /docker-entrypoint-initdb.d

ENV MYSQL_ROOT_PASSWORD=root

VOLUME /mysql_data

EXPOSE 3306