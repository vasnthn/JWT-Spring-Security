# JWT Spring Security

A Spring Boot application that secures RESTful APIs using JSON Web Tokens (JWT). This project demonstrates how to integrate Spring Security with JWT for authentication and authorization, leveraging MySQL as the database.

## Features
✅ User registration and login  
✅ JWT-based authentication and authorization  
✅ Role-based access control  
✅ Secure RESTful APIs  
✅ Custom exception handling  
✅ MySQL database integration  

## Technologies Used
- **Java**
- **Spring Boot**
- **Spring Security**
- **JSON Web Tokens (JWT)**
- **Maven**
- **MySQL**

## Real-World Effectiveness
- **🔒 Scalable Security**: Stateless JWT authentication allows better scalability and performance.
- **⚙️ Flexibility**: Role-based access control supports different user roles and permissions.
- **🛡️ Enhanced Security**: Secure token-based authentication reduces security vulnerabilities.
- **🔗 Easy Integration**: Spring Security simplifies implementation, allowing focus on core features.
- **🗄️ Reliable Data Storage**: MySQL ensures data integrity and consistency.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Java 8 or higher
- Maven
- Git
- MySQL

### Installation
```sh
# Clone the repository
git clone https://github.com/your-username/jwt-spring-security.git
cd jwt-spring-security

# Build the project
mvn clean install

# Run the application
mvn spring-boot:run
```

### API Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| **POST** | `/api/v1/auth/register` | Register a new user |
| **POST** | `/api/v1/auth/authenticate` | Authenticate a user and get JWT token |
| **GET** | `/api/v1/demo-controller` | Access a secured endpoint |

## Project Structure
📂 **ApplicationConfig.java** - Configures authentication and password encoding.  
📂 **JwtAuthenticationFilter.java** - Validates JWT tokens and authenticates users.  
📂 **JwtService.java** - Creates and validates JWT tokens.  
📂 **SecurityConfiguration.java** - Sets up security filters, session management, and authentication providers.  
📂 **DemoController.java** - Example secured endpoint.  
📂 **User.java** - Defines user entity and implements `UserDetails`.  

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue. 

## Acknowledgments
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring Security](https://spring.io/projects/spring-security)
- [JWT](https://jwt.io/)
- [MySQL](https://www.mysql.com/)

