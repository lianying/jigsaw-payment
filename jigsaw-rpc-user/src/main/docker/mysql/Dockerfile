FROM mysql:5.7
MAINTAINER jigsaw paymentrpc@gmail.com
ARG character-set-server=utf8mb4  \
    collation-server=utf8mb4_unicode_ci  \
    max_allowed_packet=32M

ENV MYSQL_DATABASE=jigsaw-user  \
    MYSQL_ROOT_PASSWORD=zaq1XSW@ \
    MYSQL_USER=jigsaw  \
    MYSQL_PASSWORD=zaq1XSW@  

COPY *.sql /docker-entrypoint-initdb.d/

EXPOSE 3306
