# Specify the base image
FROM mariadb:latest

# Set environment variables for MariaDB to initialize
ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=mydatabase
ENV MYSQL_USER=myuser
ENV MYSQL_PASSWORD=mypassword

# Optional: Copy a custom configuration file if you have one
# COPY my-custom.cnf /etc/mysql/conf.d/

# Expose the port MariaDB uses
EXPOSE 3306

# Set the default command to run when starting the container
CMD ["mysqld"]
