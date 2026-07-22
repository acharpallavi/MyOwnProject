# MyOwnProject

A Spring Boot REST API project implementing JWT Authentication using Spring Security.

## 🚀 Features

- User Registration (Signup)
- User Login
- JWT Authentication
- Secure REST APIs
- Password Encryption using BCrypt
- H2 Database Integration
- Global Exception Handling

## 🛠 Technologies Used

- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA
- JWT (JSON Web Token)
- Maven
- H2 Database
- Postman

## 📁 Project Structure

```
src
 ├── config
 ├── controller
 ├── dto
 ├── exception
 ├── model
 ├── repository
 ├── service
```

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/acharpallavi/MyOwnProject.git
```

2. Open the project in IntelliJ IDEA.

3. Run the application:

```
MyOwnProjectApplication.java
```

4. Open the H2 Console:

```
http://localhost:8080/h2-console
```

5. Test the APIs using Postman.

## 📌 API Endpoints

### Signup

```
POST /api/users/signup
```

### Login

```
POST /api/users/login
```

### Protected API

```
GET /api/users/hello
```

## 👩‍💻 Author

**Pallavi Achar**
