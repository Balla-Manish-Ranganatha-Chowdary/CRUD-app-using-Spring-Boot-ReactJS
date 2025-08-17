# ReactJS + Spring Boot CRUD Full Stack Application  

A **full-stack web application** built using **ReactJS (frontend)** and **Spring Boot (backend)** with **MySQL database** integration. This project demonstrates end-to-end CRUD (Create, Read, Update, Delete) operations, making it a solid foundation for enterprise-level applications.  

---

## 🚀 Features  
- **Spring Boot REST API** as backend  
- **ReactJS** frontend with responsive UI  
- **CRUD functionality** (Create, Read, Update, Delete) for managing records  
- **MySQL database** integration using JPA & Hibernate  
- **RESTful architecture** with clean separation of concerns  
- **Cross-origin support** for frontend-backend communication  
- **Modular, scalable project structure**  

---

## 🛠️ Tech Stack  
**Frontend:** ReactJS, Axios, Bootstrap  
**Backend:** Java, Spring Boot, Spring Data JPA, Hibernate  
**Database:** MySQL  
**Build Tools:** Maven (backend), npm (frontend)  

---

## ⚙️ Installation & Setup  

### 🔹 Prerequisites  
- Java 17+  
- Maven 3+  
- Node.js & npm  
- MySQL server  

### 🔹 Backend Setup (Spring Boot)  
1. Clone the repository: 
   ```bash
   git clone https://github.com/Balla-Manish-Ranganatha-Chowdary/CRUD-app-using-Spring-Boot-ReactJS.git
   cd CRUD-app-using-Spring-Boot-ReactJS
   ```
2. Configure MySQL database in application.properties:  
   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/your_db
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```
3. Build & run:  
   ```bash
   mvn spring-boot:run
   ```
The backend will start on http://localhost:8080

---

### 🔹 Frontend Setup (ReactJS)
1. Navigate to frontend folder:  
   ```bash
   cd frontend
   ```
2. Install dependencies:  
   ```bash
   npm install
   ```
3. Run React app:
   ```bash
   npm start
   ```
The frontend will start on http://localhost:3000

---

### 📂 Project Structure
CRUD-app-using-Spring-Boot-ReactJS
│── backend/          # Spring Boot backend
│   ├── src/main/java # Java source code
│   ├── src/main/resources/application.properties
│   └── pom.xml
│
│── frontend/         # React frontend
│   ├── public/
│   ├── src/
│   └── package.json
│
└── README.md

---

### 🎯 Learning Outcomes
- Full-stack development with React + Spring Boot
- Building and consuming REST APIs
- Connecting frontend with backend using Axios
- Handling CRUD operations efficiently
- Working with MySQL database using Spring Data JPA

---
