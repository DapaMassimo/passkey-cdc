FROM mysql

ENV MYSQL_ROOT_PASSWORD ${DATABASE_MASTER_PASSWORD}
ADD db.sql /docker-entrypoint-initdb.d

EXPOSE 3306