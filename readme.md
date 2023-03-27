## Test Spring Boot CRUD REST APIs using Postman Client
### Spring Boot REST API CRUD+Exception Handling(used Spring Boot 3+Lombok+Spring Data JPA+MySQL Database.)
### Create Database schema My Sql Workbench

![img_5.png](img_5.png)

### Create User REST API:

http://localhost:8080/api/users
![img.png](img.png)

### Get All Users REST API:
http://localhost:8080/api/users
![img_1.png](img_1.png)

### Get Single User REST API:
http://localhost:8080/api/users/1
![img_2.png](img_2.png)

### Update User REST API:
http://localhost:8080/api/users/4
![img_3.png](img_3.png)

### Delete User REST API:
http://localhost:8080/api/users/1
![img_4.png](img_4.png)

### Exception Handling
###### Note:when using devtools stack trace comes default for disable remove devtools dependenceies or use server.error.include-stacktrace=never in propertes files
###### if user not found then getting customized exception,here user id not avilabel in Databases (boot specfic exception)
http://localhost:8080/api/users/19
![img_6.png](img_6.png)

### Custom Exception(global exceptions,specfic exceptions)
http://localhost:8080/api/users/19
![img_7.png](img_7.png)
