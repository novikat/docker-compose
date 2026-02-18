# Library application

## 💬Overview
Application based on Spring Boot intended for storing, retrieving, searching books, making lists of
favorites, writing reviews, etc.

- Used PostgreSQL for data storage and MongoDB for file storage.
- Configured security via Spring Security and Keycloak.
- Established connection between microservices via Spring Cloud Eureka and OpenFeign.

---

## ⚠ Attention
Project currently is being updated. Newer versions (if exist) are located in "***develop***" branch of the repositories listed below.\
\
Expected changes:

+ Adding ***gateway*** for request routing and primary security checks.
+ Transfering ***file-loader*** microservice from Mvc to WebFlux.
+ Addind ***Docker-compose*** for one-command deployment.
+ Adding ***Swagger***.
+ Cleaning code and resolving issues.



---
## 🧰 Repositories

| Component | Description | Repo |
|------------|--------------|------|
| ⚙️ **Docker-compose** | Docker Compose + deployment setup | [docker-compose](https://github.com/novikat/docker-compose.git) |
| 📚 **Library Service** | Spring-based microservice, connects to Postgres DB that stores data about books, authors, and users | [library-service](https://github.com/novikat/library-service.git) |
| 🗂️ **File-Loader Service** | Spring-based reactive microservice, connects to MongoDB that stores book files | [file-loader](https://github.com/novikat/file-loader.git) |
| 🌐 **Gateway** | Manages routing and security configurations | [gateway](placeholder) |
| 🔍 **Eureka Server** | Service discovery | [eureka-server](https://github.com/novikat/eureka-server.git) |
---

## 🧪 Run Locally

**Local deployment is currently anavailable.**
