# JWTAuthentication
This is a spring boot application that supports token based authentication with JWT, it covers the following concepts

- Flow for user signup and signin with JWT Authentication
- Spring boot application architecture with spring security
- Data models definitions
- Using spring data JPA to interact with `h2` database

This application runs on `h2` database and the `RESTApi` are tested on postman.

### Getting Started

### Spring Security
Here is the spring boot server diagram how the process flows.

<img src="screenshot/spring_server.PNG" width="500"/>

### Technology Used
- java8
- Spring boot2 (with spring security.Spring web Spring Data JPA)
- h2 database
- Maven




### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.7.5/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.7.5/gradle-plugin/reference/html/#build-image)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/2.7.5/reference/htmlsingle/#data.sql.jpa-and-spring-data)
* [Spring Security](https://docs.spring.io/spring-boot/docs/2.7.5/reference/htmlsingle/#web.security)