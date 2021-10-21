## About project
This is a simple taxi service project that was created to show my knowledge of Java, JDBC, Web, OOP and Solid principles. 
"Taxi service" is based on a three-tier architecture 
that includes Dao, Service and Controller levels.
This application is able to process HTTP requests, connect to the database and perform CRUD operations on it.
For example, you can register as a driver, login to the application and see all drivers in the database. 
Or you can create your dream car and add yourself as its driver and this will be noted in the database.

## Technologies
Project is created with:
```
* Java 11
* MySQL
* JDBC
* Javax servlet API
* JSP
* Jstl
* Tomcat 9.0.50 (to run app locally)
```

## How to try it?
I prepared online version of this project:
* https://taxi-service-v-lekhter.herokuapp.com/login

Or you can run this app locally:

* install MySQL
* install Tomcat 9.0.50
* fork this project and clone it
* initialize your database using init_db.sql file located in resources
* add your database info to ConnectionUtil located in util to be able to connect to your database

```java
public class ConnectionUtil {
    private static final String URL = "Your Database url";
    private static final String USERNAME = "Username";
    private static final String PASSWORD = "Password";
```

* run this project using Tomcat's local server