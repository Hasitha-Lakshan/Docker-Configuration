FROM mysql:8.0.27
ENV MYSQL_DATABASE=mydatabase
ENV MYSQL_USER=myuser
ENV MYSQL_PASSWORD=mypassword
ENV MYSQL_ROOT_PASSWORD=myrootpassword
COPY init.sql /docker-entrypoint-initdb.d/
EXPOSE 3306
CMD ["mysqld"]
