FROM mysql:8.0.33
LABEL "project"="vprofile"
LABEL "name"="mitul"

ENV MYSQL_ROOT_PASSWORD="mysql"
ENV MYSQL_DATABASE="account"

ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql
