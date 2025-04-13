# Java Hotel Management System

## Overview

Hotel Management System is a comprehensive hotel management application developed in Java. The system supports booking management, customer management, hotel services, payments, and statistical reporting.

## Technologies Used

- **Backend**: Java, Spring Boot, Hibernate
- **Frontend**: JavaScript, React, Bootstrap
- **Database**: MySQL
- **Authentication**: JWT, Spring Security
- **API Documentation**: Swagger
- **Build Tool**: Maven/Gradle

## Installation and Running

### System Requirements

- Java JDK 11 or higher
- Maven 3.6.x or Gradle 7.x
- MySQL 8.x/PostgreSQL 13.x
- Node.js 14.x (for Frontend)

### Backend setup

```bash
# Clone repository
git clone https://github.com/nguyenduykiet72/Hotel-Management

# Navigate to backend directory
cd hotel-management/Hotel-BE

# Install dependencies and build project
mvn clean install

# Run application
java -jar target/hotel-management-1.0.0.jar
```

### Frontend setup

```bash
# Navigate to frontend directory
cd ../Hotel-FE

# Install dependencies
npm install

# Run application
npm start
```

## Project Structure

```
hotel-management/
├── Hotel-BE/                   # Backend code
│   ├── src/main/java/          # Java source code
│   ├── src/main/resources/     # Configuration files
│   └── src/test/               # Unit tests
├── Hotel-FE/                   # Frontend code
│   ├── public/                 # Static files
│   └── src/                    # React components
└── README.md                   # Project documentation
```

