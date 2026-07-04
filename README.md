# Employee Management System

A Full Stack Employee Management System built using **Spring Boot**, **React.js**, **MySQL**, and **REST APIs**. This application allows users to perform CRUD (Create, Read, Update, Delete) operations on employee records.

## 🚀 Features

- Add new employees
- View all employees
- Update employee details
- Delete employees
- Responsive user interface
- REST API integration between React and Spring Boot

## 🛠️ Tech Stack

### Backend
- Java 21
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven

### Frontend
- React.js
- React Router
- Axios
- Bootstrap 5

## 📂 Project Structure

### Backend
```
employee-management-backend
 ├── controller
 ├── service
 ├── repository
 ├── entity
 ├── exception
 └── resources
```

### Frontend
```
employee-management-frontend
 ├── src
 │   ├── components
 │   ├── services
 │   ├── App.js
 │   └── index.js
 └── public
```


## 📌 REST API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | /api/employees | Get All Employees |
| GET | /api/employees/{id} | Get Employee By Id |
| POST | /api/employees | Add Employee |
| PUT | /api/employees/{id} | Update Employee |
| DELETE | /api/employees/{id} | Delete Employee |


## ⭐ Future Enhancements

- Employee Search
- Pagination
- Authentication & Authorization (JWT)
- Sorting and Filtering
- Docker Deployment

---
If you like this project, give it a ⭐ on GitHub.
