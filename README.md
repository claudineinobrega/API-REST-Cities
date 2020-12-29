# API REST Cities

## API para Consulta de Cidades do Brasil

### Framework do Projeto
- [Spring Initializr](https://start.spring.io/ "Spring Initializr")
- **Project:** Gradle Project
- **Language:** Java
- **Spring Boot:** 2.4.1

### Dependencies
- Spring Web
- Spring Data JPA
- PostgreSQL Driver

### DataBase
- [Postgres Docker Hub](https://hub.docker.com/_/postgres "Postgres Docker Hub")
- docker pull postgres
- docker run --name cities-db -d -p 5432:5432 -e POSTGRES_USER=postgres_user_city -e POSTGRES_PASSWORD=super_password -e POSTGRES_DB=cities postgres

### Properties
- [Spring](https://docs.spring.io/spring-boot/docs/current/reference/html/appendix-application-properties.html "Spring")
- [JDBC](https://www.codejava.net/java-se/jdbc/jdbc-database-connection-url-for-common-databases "JDBC")
