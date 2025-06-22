
<h1 align="center">👨‍💼 Employee CRUD API</h1>
<p align="center">A clean, scalable Spring Boot REST API for managing employee data with MySQL, JPA, and Lombok.</p>

---

##  Overview

This project is a backend REST API built with **Spring Boot** that allows full **CRUD operations** (Create, Read, Update, Delete) on employee records. It demonstrates how to structure a Java Spring Boot app with clean code, layers, and best practices.

---

## 🛠 Tech Stack

-  Spring Boot 3.2.2  
-  Java 17  
-  Spring Data JPA  
-  MySQL (Database)  
-  Lombok (Boilerplate-free models)  
-  Maven (Project management)

---

##  Features

- Add new employees  
- Get all or individual employee details  
- Update existing employee info  
- Delete employees  
- RESTful structure with clean layers (Controller → Service → Repository)  
- Simple config using `application.properties`  
- Testing setup via `spring-boot-starter-test`

---

##  Project Structure

```
employee-crud/
├── pom.xml
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── employee/
│       │           └── demo/
│       │               ├── controller/
│       │               │   └── EmployeeController.java
│       │               ├── entity/
│       │               │   └── Employee.java
│       │               ├── repository/
│       │               │   └── EmployeeRepository.java
│       │               ├── service/
│       │               │   └── EmployeeService.java
│       │               └── DemoApplication.java
│       └── resources/
│           └── application.properties
└── target/

```

---

##  Configuration

Edit `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
spring.datasource.username=your_mysql_user
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update
```

---

##  Running the Project

1. Clone the repository:
```bash
git clone https://github.com/najuaircrack/employee-crud.git
cd employee-crud
```

2. Start MySQL server & create the DB:
```sql
CREATE DATABASE employee_db;
```

3. Run the app:
```bash
mvn spring-boot:run
```

**Najuaircrack**  
 Discord: `@najuaircrack`  
 Email: `kcnajwan7@gmail.com`  

---
