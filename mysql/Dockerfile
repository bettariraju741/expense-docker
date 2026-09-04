FROM mysql:8.0
ENV MYSQL_PPORT_PASSWORD=ExpenseApp@1
RUN groupadd expense && \
    useradd -g expense && \
    chown -R expense:expense /var/lib/mysql /var/run/mysqld/docker-entrypoint-initdb.d
ADD script/*.sql /docker-entrypoint-initdb.b
USER expense