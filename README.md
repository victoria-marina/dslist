# DSList

**DSList** is a Java Spring Boot application that provides a RESTful API for managing a list of games. It uses JPA for persistence and supports both in-memory (H2) and PostgreSQL databases.

- List all games
- Retrieve game details by ID
- Organize games into custom lists
- Use H2 (in-memory) or PostgreSQL database
- RESTful API architecture

## Tech Stack

- Java 21
- Spring Boot 3.4.5
- Spring Data JPA
- Spring Web
- H2 Database (for development/testing)
- PostgreSQL (for production)
- Maven

## Getting Started

### Prerequisites

- Java 21+
- Maven
- PostgreSQL (optional, if not using H2)

### Running the Application

#### Using H2 (default)

```bash
mvn spring-boot:run
