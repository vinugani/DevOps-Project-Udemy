FROM mysql:5.7.25
LABEL "Project"="Omisweb"
LABEL "Author"="Omisam"

ENV MYSQL_ROOT_PASSWORD="omisdbpass"
ENV MYSQL_DATABASE="accounts"


ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
