FROM mysql:8.0.33
LABEL Project=vprofile
LABEL Author=chimosky

ENV MYSQL_ROOT_PASSWORD="pass123"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
