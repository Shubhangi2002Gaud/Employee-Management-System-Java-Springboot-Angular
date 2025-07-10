# Employee Management System 

A full-stack **Employee Management System** built using **Java + Spring Boot (backend)** and **Angular (frontend)**. It provides CRUD functionality for managing employees in an organization.

---

## Tech Stack

- **Frontend**: Angular 16, TypeScript, HTML5, SCSS/Bootstrap
- **Backend**: Spring Boot 3.x, Spring MVC, Spring Data JPA
- **Database**: MySQL 
- **Build Tools**: Maven (backend), Angular CLI (frontend)
- **API Communication**: RESTful APIs with JSON
- **Deployment**: Docker (Optional), Localhost

---

##  Features

✅ Add New Employees  
✅ View All Employees  
✅ Update Employee Details  
✅ Delete Employees  
✅ Search Employees by Name or Email  
✅ Responsive UI with Angular Material or Bootstrap  
✅ CORS Enabled API for frontend-backend integration

---
## Installation & Run Locally

###  Backend (Spring Boot)

```bash
cd backend
#Update src/main/resources/application.properties with your DB credentials

# Run using Maven
./mvnw spring-boot:run

 ### Frontend
cd frontend
npm install
ng serve
Access Angular app at http://localhost:4200

----
| Method | Endpoint              | Description        |
| ------ | --------------------- | ------------------ |
| GET    | `/api/employees`      | List all employees |
| POST   | `/api/employees`      | Add new employee   |
| PUT    | `/api/employees/{id}` | Update employee    |
| DELETE | `/api/employees/{id}` | Delete employee    |









