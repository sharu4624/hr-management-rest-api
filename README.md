# HR Management System

A backend REST API application for managing human resources operations,
built with **Spring Boot** and a **SQL database**. All endpoints are
tested using **Postman**.

## Features
- Add, view, update, and delete employee records (CRUD)
- Manage departments and job roles
- RESTful endpoints using HTTP methods (GET, POST, PUT, DELETE)
- Data persistence with Spring Data JPA / Hibernate
- Input validation and proper HTTP status codes
- Exception handling with meaningful error responses

## Tech Stack
| Layer     | Technology                    |
|-----------|-------------------------------|
| Backend   | Java, Spring Boot             |
| Database  | MySQL / SQL                   |
| ORM       | Spring Data JPA, Hibernate    |
| API Testing | Postman                     |
| Build Tool | Maven                        |

## API Endpoints
| Method | Endpoint              | Description            |
|--------|-----------------------|------------------------|
| POST   | /api/employees        | Add a new employee     |
| GET    | /api/employees        | Get all employees      |
| GET    | /api/employees/{id}   | Get employee by ID     |
| PUT    | /api/employees/{id}   | Update employee        |
| DELETE | /api/employees/{id}   | Delete employee        |

## Setup and Run
1. Clone the repository
   `git clone https://github.com/your-username/hr-management-system.git`
2. Create a database: `CREATE DATABASE hr_management;`
3. Update `application.properties` with your DB username and password
4. Run the application: `mvn spring-boot:run`
5. Test the APIs using Postman at `http://localhost:8080`

## Future Enhancements
- Spring Security with JWT authentication
- Leave and attendance management
- Payroll module
- Frontend with React or Angular
