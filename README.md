# Custom Query
- Demo Project for customers queries by method name and also using query annotation query for all mysql keywords which are given in JPA documentation.
## Framework and Language Used
* SpringBoot 
* Java 
## Architecture Used
### Controller
- StudentController
### Model
- Student
### Service
- StudentService
### dao
* Here we have extended JPARepository and the main @query annotation is used
- StudentRepository
### Postman(endpoinst)
- addStudent(POST):- http://localhost:8080/addstudent

- getbyage(GET):- http://localhost:8080/byAge/33

- getstudents(GET):- http://localhost:8080/getstudents

- getbyfirsname(GET):-http://localhost:8080/getbyfirstname/Arun

- getbylastname(GET):-http://localhost:8080/getbyLastName/chauhan

## DataBase Used

### MYSQL

### Project Summary

- In this project we are performing the operation using native Query and retriving the data from DataBase..
### @Query Annotation
- The @Query annotation is a feature in the Spring Data JPA module, which is used in Spring Boot applications for implementing database queries. It is used to define - custom queries in the repository interface for retrieving data from the database.

- By default, Spring Data JPA automatically generates queries based on the method name and parameters. However, in some cases, it may be necessary to define more -   complex queries that cannot be automatically generated. In such cases, you can use the @Query annotation to specify a custom SQL query or JPQL (Java Persistence  Query Language) query.
