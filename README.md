# Cinema-App
___
## Description
This project is a simple cinema booking system. It allows user to register, manage different movies and cinema halls. There is also a posibility to add tickets to your shopping cart and complete the orders!
___
## Project features
1. Registration/authentication of user
2. Log in / Log out
3. User can have user or admin role
4. Admin features:
    + add / see cinema halls
    + add new / see available movies
    + create / change / delete / see movie sessions
    + find users by-email
5. User features:
    + see all movies, cinema halls, available movie-sessions
    + add tickets to the shopping cart
    + complete the order
___
## Project structure
This project has an 3-tier architecture
+ DAO - all communication with databases happens here
+ Service - all business logic on this level
+ Controller - this level allows the user to work with our application
___
## Technologies
+ Java 11
+ Maven
+ Spring WEB
+ Spring MVC
+ Spring Security
+ MySQL
+ Tomcat (9.0.50)
+ Hibernate
___
## Instruction to run this project
1. Fork this repository
2. Open IntelliJ IDEA and write git clone <SSH link> in console
3. Configure db.properties - set necessary parameters:
```java
        db.driver=YOUR_DRIVER
        db.url=YOUR_URL
        db.user=YOUR_USERNAME
        db.password=YOUR_PASSWORD
```
4. Install [Tomcat](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/) version 9.0.50
5. Configure the Tomcat server in your IDEA
6. Run the project
___

