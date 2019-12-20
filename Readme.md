## Spring Boot, MySQL, JPA, Hibernate REST API Demo

## Tutorial

Check out the complete tutorial on the CalliCoder blog -

[Spring Boot, MySQL, JPA, Hibernate RESTful CRUD API Example](https://www.callicoder.com/spring-boot-jpa-hibernate-postgresql-restful-crud-api-example/)

## Steps to Setup

**1. Clone the repository**

```bash
https://github.com/DouglasEleuterio/spring-boot-postgresql-jpa-hibernate-rest-api-demo.git
```

**2. Configure MySQL**

First, create a database named `demo`. Then, open `src/main/resources/application.properties` file and change the spring datasource username and password as per your MySQL installation.

**3. Run the app**

Type the following command from the root directory of the project to run it -

```bash
mvn spring-boot:run
```

Alternatively, you can package the application in the form of a JAR file and then run it like so -

```bash
mvn clean package
java -jar target/postgres-demo-0.0.1-SNAPSHOT.jar
```