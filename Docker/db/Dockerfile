FROM mysql:8.0.33
LABEL "Project"="omisapp"
LABEL "Author"="omis"

ENV MYSQL_ROOT_PASSWORD="omisdbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql