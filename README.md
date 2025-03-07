# Spring Boot Repertoire

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
![Last Commit](https://img.shields.io/github/last-commit/pesnik/springboot-repertoire)

**A curated collection of Spring Boot projects and experiments, showcasing the journey toward mastery with Spring Boot in the cutting-edge tech world of 2025.**

---

## Table of Contents

- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Projects](#projects)
  - [Basics](#basics)
  - [Intermediate](#intermediate)
  - [Advanced](#advanced)
  - [Experiments](#experiments)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

---

## Introduction

Welcome to **Spring Boot Repertoire**! This repository is a personal showcase of Spring Boot projects, experiments, and learning materials, reflecting a journey toward mastering the Spring Boot framework. Inspired by the performing arts—where a "repertoire" represents a collection of mastered works—this repository captures the evolution from foundational concepts to advanced, innovative applications.

The `*-repertoire` naming pattern (e.g., `springboot-repertoire`) signifies a sophisticated, mastery-focused approach, moving beyond beginner tutorials to a curated set of skills and projects. Here, you’ll find implementations covering core Spring Boot concepts alongside modern trends like reactive programming, microservices, and AI integration, keeping it relevant to 2025’s tech landscape.

---

## Repository Structure

The repository is organized into directories, each containing self-contained Spring Boot projects with their own documentation and dependencies:

```
springboot-repertoire/
├── basics/
│   ├── hello_world/
│   ├── rest_api/
│   ├── database_integration/
│   └── ...
├── intermediate/
│   ├── security/
│   ├── testing/
│   ├── i18n/
│   ├── email_sending/
│   └── ...
├── advanced/
│   ├── reactive_programming/
│   ├── microservices/
│   ├── serverless/
│   ├── ai_integration/
│   ├── kubernetes_deployment/
│   └── ...
└── experiments/
    ├── latest_features/
    ├── graphql_api/
    ├── event_driven_architecture/
    └── ...
```

Each project directory includes:
- **README.md**: Project-specific details, including purpose and setup instructions.
- **pom.xml**: Maven dependencies for the project.
- **application.properties**: Configuration file for the project.

Root-level files include `.gitignore`, `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `LICENSE`, and this `README.md`.

---

## Projects

Projects are categorized by skill level and purpose, emphasizing challenges that resonate with 2025’s tech trends.

### Basics
- **[Hello World Application](basics/hello_world/)**: A simple Spring Boot application to understand the basic structure and setup.
- **[REST API](basics/rest_api/)**: Build a RESTful API to demonstrate controllers, services, and repositories.
- **[Database Integration](basics/database_integration/)**: Use Spring Data to connect to a database and perform CRUD operations.

### Intermediate
- **[Security](intermediate/security/)**: Implement authentication and authorization using Spring Security.
- **[Testing](intermediate/testing/)**: Write unit and integration tests using JUnit and MockMvc.
- **[Internationalization (i18n)](intermediate/i18n/)**: Handle multiple languages using Spring’s message source.
- **[Email Sending](intermediate/email_sending/)**: Configure and send emails using Spring Mail.

### Advanced
- **[Reactive Programming](advanced/reactive_programming/)**: Build a reactive application using Project Reactor for asynchronous operations.
- **[Microservices](advanced/microservices/)**: Create a microservices architecture with Spring Cloud Netflix Eureka.
- **[Serverless with Spring Boot](advanced/serverless/)**: Deploy on AWS Lambda, optimizing for serverless environments.
- **[AI Integration](advanced/ai_integration/)**: Integrate a sentiment analysis service using pre-trained ML models.
- **[Kubernetes Deployment](advanced/kubernetes_deployment/)**: Configure and deploy a Spring Boot app on Kubernetes, including scaling.

### Experiments
- **[Latest Features in Spring Boot 4](experiments/latest_features/)**: Explore and implement projects using Spring Boot 4 features, like Java 23 support.
- **[GraphQL API](experiments/graphql_api/)**: Build a GraphQL API with Spring Boot and the graphql-java library.
- **[Event-Driven Architecture](experiments/event_driven_architecture/)**: Use Spring Boot with Spring Kafka for event-driven patterns.

---

## Getting Started

To explore the projects, ensure you have the following installed:
- **Java 23**
- **Maven 3.9.0 or higher**
- **Git**

---

## How to Use

Follow these steps to set up and run any project:

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/pesnik/springboot-repertoire.git
   ```

2. **Navigate to a project directory**:  
   For example, the Hello World Application:  
   ```bash
   cd springboot-repertoire/basics/hello_world
   ```

3. **Build and run the project**:  
   - Using Maven:  
     ```bash
     mvn spring-boot:run
     ```
   - Using Gradle (if applicable):  
     ```bash
     ./gradlew bootRun
     ```

4. **Access the application**:  
   Open your browser and navigate to `http://localhost:8080`.

> **Note**: Some projects may require additional setup (e.g., database configuration or third-party services). Check the project’s `README.md` for details.

---

## Contributing

Contributions are encouraged! To contribute:

1. Fork the repository.  
2. Create a new branch:  
   ```bash
   git checkout -b feature/your-feature
   ```  
3. Commit your changes:  
   ```bash
   git commit -m "Add your message"
   ```  
4. Push to your branch:  
   ```bash
   git push origin feature/your-feature
   ```  
5. Submit a pull request.

Please follow the [code of conduct](CODE_OF_CONDUCT.md) and [contributing guidelines](CONTRIBUTING.md).

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [Spring Boot Documentation](https://docs.spring.io/spring-boot)
- [Baeldung](https://www.baeldung.com)
- [Spring Guides](https://spring.io/guides)

---

## Contact

Questions or feedback? Open an issue or contact [pesnik](https://github.com/pesnik).
