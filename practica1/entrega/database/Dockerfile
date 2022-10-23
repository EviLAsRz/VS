FROM mariadb:latest
COPY db.sql /docker-entrypoint-initdb.d
EXPOSE 3306
RUN apt-get update
ENV MARIADB_ROOT_PASSWORD=root
