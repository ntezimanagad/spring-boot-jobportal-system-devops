Job Portal System

A full-featured Job Portal built with **Spring Boot**, enabling users to register as applicants or companies, post jobs, apply to jobs, and manage job applications.

Features

- User Registration & Login (JWT/Session based)
- Company profile creation & job posting
- Applicant profile with resume upload
- Job application submission & tracking
- Role-based access control
- Admin control panel (optional)
- Integrated unit & integration testing
- CI/CD ready for deployment (Render)


Tech Stack

| Layer              | Tech                             |
|-------------------|----------------------------------|
| Backend           | Spring Boot, Spring Security     |
| ORM & DB          | Spring Data JPA, MySQL/PostgreSQL|
| JSON Mapper       | Jackson, Lombok                  |
| Mapping           | MapStruct                        |
| API Testing       | Postman                          |
| Build Tool        | Maven or Gradle                  |
| Deployment        | Render / Docker (Optional)       |

Project Structure

com.learn.chatapp
├── controller  REST controllers
├── dto  Data Transfer Objects
├── model  JPA Entities
├── repository  Spring Data Repos
├── service  Business Logic
├── mapper  MapStruct Mappers
├── JWT JWT related
└── exception Custom Exceptions & Handlers
└── config Custom Exceptions & Handlers

