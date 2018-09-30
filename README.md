# BOOK API - Spring MVC, MySQL, Hibernate Rest API Tutorial

Build Restful CRUD API for a simple Book-Manage application using Spring MVC, Mysql and Hibernate.

## Requirements

1. Java - 1.8.x

2. Maven - 3.3.9

3. MySQL - 5.7.12    

## Steps to Setup

**1. Clone the application**

```bash
git clone https://github.com/scbushan05/book-api.git
```

**2. Create Mysql database**

```bash
create database bookdb
```

**3. Change mysql username and password as per your installation**

+ open `src/main/resources/db.properties`

+ change `mysql.user` and `mysql.password` as per your mysql installation

**4. Build and run the app using maven**

```bash
mvn package
```

A new WAR file will be generated at `project/target/bookapi-0.0.1-SNAPSHOT.war`, just copy and deploy to your Tomcat.

The app will start running at <http://localhost:8080/bookapi/>.

## Explore Rest APIs

The app defines following CRUD APIs.

    GET /api/book
    
    POST /api/book
    
    GET /api/book/{bookId}
    
    PUT /api/book/{bookId}
    
    DELETE /api/book/{bookId}

You can test them using postman or any other rest client.

## Learn more

You can find the tutorial for this application on my blog - 

<http://bushansirgur.in/angular-2-and-spring-mvc-simple-crud-application/>
