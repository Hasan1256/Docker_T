#pull official mysql image from dockerhub
FROM mysql:8.0

#set environment variables for mysql root password, database name, username and password
ENV MYSQL_ROOT_PASSWORD=demopassword
ENV MYSQL_DATABASE=demodb

#copy the initialization script to the container's /docker-entrypoint-initdb.d/ directory
COPY init.sql /docker-entrypoint-initdb.d/

#expose the default mysql port
EXPOSE 3307