# CleverKit

CleverKit is a modern web application built with Spring Boot and React, designed to provide a robust and scalable solution for your needs.

## Features

- Modern web interface built with React
- Robust backend powered by Spring Boot
- Docker support for easy deployment
- RESTful API architecture

## Prerequisites

- Java 17 or higher
- Node.js 16 or higher
- Docker and Docker Compose (for containerized deployment)
- Maven (for backend build)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/cleverkit.git
cd cleverkit
```

2. Start the application using Docker Compose:
```bash
docker-compose up -d
```

3. Access the application:
- Frontend: http://localhost:3000
- Backend API: http://localhost:8080

## Development

### Backend Development
```bash
cd cleverkit
./mvnw spring-boot:run
```

### Frontend Development
```bash
cd cleverkit/frontend
npm install
npm start
```

## API Documentation

API documentation is available at `/swagger-ui.html` when running the application.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for a list of changes. 