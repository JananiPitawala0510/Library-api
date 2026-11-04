# Library Management REST API

A simple RESTful API developed using Java and Spring Boot for managing library books as part of the Enterprise Application Development (EAD) lab.

## Technologies Used
- Java 21
- Spring Boot
- Spring Data JPA
- MySQL
- Maven

## How to Run

1. Clone the repository.
2. Create a MySQL database named `library_db`.
3. Configure the database environment variables (`DB_URL`, `DB_USERNAME`, `DB_PASSWORD`).
4. Run the application using:

   ```bash
   ./mvnw spring-boot:run
   ```

Database tables are generated automatically through Hibernate.

## API Testing

The REST API endpoints can be tested using Postman.

## Author

Janani Pitawala
