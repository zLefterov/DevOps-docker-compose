Hello everyone! 
Welcome to my Docker-based project setup. 
This project allows you to quickly deploy a basic yet powerful server environment suitable for hosting and managing web applications. 
It's a great starting point for building your website's infrastructure.

Services
In this setup, we're using Docker to create containers for the following services:

Nginx: A high-performance web server and reverse proxy.
Tomcat: An open-source implementation of the Java Servlet, JavaServer Pages, and Java Expression Language technologies.
RabbitMQ: A robust, scalable, and easy-to-use message broker.
Memcached: A distributed memory object caching system.
MySQL: A popular open-source relational database management system.
These tools together provide a solid foundation for hosting dynamic websites and applications.

Getting Started
Prerequisites
Docker and Docker Compose should be installed on your system. If not, you can install them from Docker's official website.
Installation and Usage
Clone the Repository:

in terminal/console: git clone https://github.com/zLefterov/DevOps-docker-compose

Navigate to the Project Directory:
in terminal/console: cd /Project1

Start the Services:
in Terminal/Console: docker-compose up
This command will start all the services as defined in the docker-compose.yml file.

Access the Services:

Nginx is accessible at http://localhost.
Tomcat at http://localhost:8080.
RabbitMQ management interface at http://localhost:15672.
MySQL can be accessed at port 3306 with the credentials specified in docker-compose.yml.

Feel free to fork the project and submit pull requests with any enhancements. 

Your contributions are always welcome!
