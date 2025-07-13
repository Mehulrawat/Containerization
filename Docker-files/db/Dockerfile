FROM mysql:8.0.33 as mysql
ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"
COPY db_backup.sql docker-entrypoint-initdb.d