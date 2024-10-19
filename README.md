# PaymentApplication

PaymentApplication is a backend application developed using Java, Spring Boot, Hibernate, JDBC, and MySQL for interacting with a relational database. This project simulates a simple payment processing system with CRUD operations, focusing on database interactions.

## Features

- Add a new payment record
- Get all payment records
- Get a specific payment record by transaction ID
- Update an existing payment record
- Delete a payment record by transaction ID

## Technologies Used

- Java
- Spring Boot for building the REST API
- Hibernate and JDBC for database interaction
- MySQL for database management
- Maven for project build management
- Postman for testing endpoints

## Database Integration

This application uses Hibernate ORM and JDBC to interact with a MySQL database. Payments are persisted in the MySQL database and can be retrieved, updated, or deleted using standard CRUD operations.

## Future Enhancements

- Implementing pagination and sorting for payment records
- Adding authentication and authorization for secure API access
- Logging and monitoring using Spring Boot Actuator
