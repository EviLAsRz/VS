FROM mariadb:latest
COPY db.sql /docker-entrypoint-initdb.d
EXPOSE 3306

ENV MARIADB_ROOT_PASSWORD=root