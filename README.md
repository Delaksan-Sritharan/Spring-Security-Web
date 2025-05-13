# Spring Security Web Demo

A simple Spring Boot web application demonstrating basic Spring Security features including:
- Authentication
- Authorization
- Custom login page
- Logout functionality

## Features

- Home page accessible to all users
- Protected "/hello" endpoint requiring authentication
- Custom login page
- Logout functionality
- In-memory user authentication with default credentials

## Technologies Used

- Spring Boot
- Spring Security
- Thymeleaf (for templating)
- Maven (dependency management)

## Setup & Running

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spring-security-web-demo.git

Navigate to the project directory:
       cd spring-security-web-demo
Run the application:
      mvn spring-boot:run
Access the application at: http://localhost:8080

Default Credentials:
    Username: user
    Password: password

Endpoints:
    / or /home - Public home page
    /login - Custom login page
    /hello - Protected page (requires authentication)
    /logout - Logout endpoint

Project Structure:
    MvcConfig - Configures view controllers
    WebSecurityConfig - Configures Spring Security
    SecuringWebApplication - Main application class
    Thymeleaf templates in src/main/resources/templates/

Screenshots:
<img width="1440" alt="Screenshot 2025-05-13 at 1 58 23 PM" src="https://github.com/user-attachments/assets/bcb1ccc8-caa5-4f21-aa77-b038bd3ad30e" />
<img width="1440" alt="Screenshot 2025-05-13 at 1 59 02 PM" src="https://github.com/user-attachments/assets/6d47d118-90b5-4f08-a3d5-1c49a8bfaed0" />
<img width="1440" alt="Screenshot 2025-05-13 at 1 59 48 PM" src="https://github.com/user-attachments/assets/b35baf51-de29-4e61-b68d-2425ea4f8660" />


