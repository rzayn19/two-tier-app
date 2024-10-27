# Use the official MySQL image from Docker Hub
FROM mysql:8.0

# Set the root password for MySQL (use secrets or environment variables for sensitive information in production)
ENV MYSQL_ROOT_PASSWORD=rootpassword

# Optionally, specify a database name to be created on container startup
ENV MYSQL_DATABASE=mydatabase

# Optionally, specify a user and password to be created for the database
ENV MYSQL_USER=myuser
ENV MYSQL_PASSWORD=mypassword

# Expose the default MySQL port
EXPOSE 3306

# Optionally, copy an SQL file to automatically initialize the database
# (Uncomment the following line if you have an init.sql file to be copied)
# COPY ./init.sql /docker-entrypoint-initdb.d/

# Set default command to run MySQL server
CMD ["mysqld"]
