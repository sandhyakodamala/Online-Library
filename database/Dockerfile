FROM mysql/mysql-server:5.7
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_USER=root
EXPOSE 3306
COPY databse.sql /docker-entrypoint-initdb.d/database.sql
