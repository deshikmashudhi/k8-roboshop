FROM mysql:5.7

ENV MYSQL_ALLOW_EMPTY_PASSWORD \
MYSQL_DATABASE=cities \
MYSQL_USER=shipping \
MYSQL_PASSWORD=Roboshop@1

COPY scripts/* /docker-entrypoint-initdb.d/