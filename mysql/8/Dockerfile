FROM mysql:8.1.0
COPY ./initdb /docker-entrypoint-initdb.d
EXPOSE 3306
CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_unicode_ci"]