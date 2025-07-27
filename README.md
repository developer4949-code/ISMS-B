# ISMS Backend

## Overview
This is the backend for the Institute/Integrated Student Management System (ISMS). It is built using Java Spring Boot and provides RESTful APIs for all academic and administrative operations.

## Tech Stack
- Java 8+
- Spring Boot
- Gradle
- Firebase (for authentication/notifications)
- Google Groups (for group emails)
- Docker

## Features
- RESTful APIs for all modules (students, faculty, courses, grievances, notices, results, etc.)
- Secure authentication and authorization
- Email and group communication integration
- Modular service and controller structure
- Dockerized for easy deployment

## Getting Started

1. **Clone the repository**
2. **Configure Firebase and Google credentials** in `src/main/resources`
3. **Build the project**
   ```
   ./gradlew build
   ```
4. **Run the application**
   ```
   ./gradlew bootRun
   ```
5. **Access the APIs** at `http://localhost:8080/`

## Folder Structure
- `controller/` - REST controllers
- `service/` - Business logic
- `model/` - Data models
- `config/` - Configuration files
- `resources/` - Properties and credentials

## Contribution
Contributions are welcome! Please fork the repo and submit a pull request.

## License
[Specify your license here]
