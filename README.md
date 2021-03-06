

# Service Two

## Use case

A simple application which generates UUID every minute and updates the same in H2/MySQL database. It also stores the UUID value generated by other service in its database asynchronously by Rabbit MQ (in case of docker environment).

Below are the architecture of the application in different environments:

#### Default Environment

![alt tag](https://github.com/microservices-sample/service-two/blob/master/doc/architecture/service-two%20(default).png?raw=true)

##### Development

Execute mvn build spring-boot:run to bring up the application in default environment

#### Docker Environment

![alt tag](https://github.com/microservices-sample/service-two/blob/master/doc/architecture/service-two%20(docker).png?raw=true)

##### Development

Refer: [https://github.com/microservices-sample/project-initializer] to bring up the micro services sample complete application using docker profile.

### Technology

Microservices sample project uses a number of open source projects to work properly:

* [SpringBoot 2.0] - Application Framework
* [Project Reactor] - Reactive Systems
* [Docker] - Containerization Platform
* [Consul] - Registration & Discovery
* [MySQL] - Relational Database
* [Swagger] - API Documentation
* [Rabbit MQ] - Message Broker
* [Logstash] - Log Collector
* [H2] - In-memory Database

### Tools

* [Java] - Programming
* [Maven] - Build
* [Git] - Version control
* [Docker] - Deployment


### Help

Feel free to reach "vijayendrap@gmail.com" incase of any concerns.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job.)

   [SpringBoot]: <https://projects.spring.io/spring-boot/>
   [Consul]: <https://www.consul.io>
   [Project Reactor]: <https://projectreactor.io/>
   [Docker]: <https://www.docker.com>
   [Maven]: <https://maven.apache.org>
   [Git]: <https://git-scm.com>
   [Java]: <https://go.java>
   [Rabbit MQ]: <https://www.rabbitmq.com/>
   [Swagger]: <https://swagger.io/>
   [Logstash]: <https://www.elastic.co/products/logstash>
   [MySQL]: <https://www.mysql.com/>
   [H2]: <http://www.h2database.com/html/main.html>
   [https://github.com/microservices-sample/project-initializer]: <https://github.com/microservices-sample/project-initializer>
