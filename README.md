# calculator
A full-stack calculator application with frontend UI and backend API built with Java and Gradle. Demonstrates modern architecture patterns.

## Project Structure

This is a **full-stack calculator application** demonstrating modern architecture patterns:

```
calculator/
├── build.gradle              # Gradle build configuration
├── README.md                 # Project documentation
└── src/
    └── main/
        ├── java/
        │   └── com/calculator/
        │       └── CalculatorApp.java    # Spring Boot REST API Backend
        └── resources/
            ├── index.html                # Frontend UI
            └── application.properties    # Application Configuration
```

## Technology Stack

- **Backend**: Java 11+, Spring Boot, Spring Web
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Build Tool**: Gradle
- **Architecture**: REST API with Client-Server Model

## Features

### Backend API Endpoints
- `GET /api/calculator/add?a=10&b=5` - Addition
- `GET /api/calculator/subtract?a=10&b=5` - Subtraction
- `GET /api/calculator/multiply?a=10&b=5` - Multiplication
- `GET /api/calculator/divide?a=10&b=5` - Division
- `GET /api/calculator/health` - Health Check

### Frontend UI
- Beautiful responsive interface with gradient background
- Input fields for two numbers
- Operation buttons (Add, Subtract, Multiply, Divide)
- Real-time result display
- Error handling

## Getting Started

### Prerequisites
- Java 11 or higher
- Gradle 7.0+

### Build
```bash
gradle build
```

### Run
```bash
gradle run
```

The application will start on `http://localhost:8080`

## API Usage

```bash
# Addition
curl http://localhost:8080/api/calculator/add?a=10&b=5

# Subtraction
curl http://localhost:8080/api/calculator/subtract?a=10&b=5

# Multiplication
curl http://localhost:8080/api/calculator/multiply?a=10&b=5

# Division
curl http://localhost:8080/api/calculator/divide?a=10&b=5
```

## Configuration

Edit `src/main/resources/application.properties` to customize:
- Server port (default: 8080)
- CORS settings
- Logging levels

## Demonstrates

- ✅ Spring Boot Application Development
- ✅ REST API Design
- ✅ Client-Server Architecture
- ✅ Gradle Build Configuration
- ✅ Frontend-Backend Integration
- ✅ Error Handling
- ✅ CORS Configuration

## Author

MOHAN KRISHNA AREVARAPU
- Backend Java Developer | Solution Architect
- Specializing in Microservices Architecture & Spring Boot

## License

MIT License
