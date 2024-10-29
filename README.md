# Customer Management System

## Overview
The **Customer Management System** is a backend application built using **Spring Boot** with **Spring Data JPA**, designed to manage customer data efficiently. This system allows users to create, read, update, and delete (CRUD) customer information through a RESTful API. The data is stored in a **PostgreSQL** database, which is containerized using **Docker** for consistent deployment across different environments.

## Features
- RESTful API for managing customer data
- CRUD operations for customer management
- Integration with PostgreSQL for data storage
- Docker containerization for easy deployment and environment consistency
- Error handling and proper status codes in API responses

## Technologies Used
- **Java** - Primary programming language
- **Spring Boot** - Framework for building the application
- **Spring Data JPA** - For data access and manipulation
- **PostgreSQL** - Database for storing customer data
- **Docker** - Containerization tool for the database and application

## Getting Started

### Prerequisites
- Java 11 or higher
- Docker and Docker Compose

### Installation

1. Clone the repository.
2. Navigate to the project directory.
3. Build the application.
4. Run the Docker containers.
5. The application will be accessible at `http://localhost:8080`.

### API Endpoints

- **Create Customer**: `POST /api/customers`
- **Get All Customers**: `GET /api/customers`
- **Get Customer by ID**: `GET /api/customers/{id}`
- **Update Customer**: `PUT /api/customers/{id}`
- **Delete Customer**: `DELETE /api/customers/{id}`

### Testing with Postman
You can use Postman to interact with the API endpoints. Set the request type to match the endpoint you are testing and provide the necessary request body for creating or updating customer records.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss improvements or bugs.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
- [Chidozie Green](https://github.com/HeisGreen)
