FROM mysql:8.0.33
LABEL "author"="banderrras"
LABEL "project"="vprofile"

ENV MYSQL_ROOT_PASSWORD="admin123"
ENV MYSQL_DATABASE="acounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql