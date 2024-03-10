# Technology Stack:

## Java, Maven, Spring Boot, Hibernate: 
* I chose Java as the programming language due to its robustness and widespread usage. Spring Boot simplifies the setup of Spring-based applications, while Hibernate facilitates object-relational mapping (ORM), streamlining database interactions.
## H2 In-Memory Database: 
* Used H2 as Database to store user, project, and task databases. Utilizing an in-memory database like H2 offers fast data access and persistence without the need for external database setup, making development and testing more efficient.

## Scalability and SOLID Principles:

* SOLID Principles:
> By adhering to SOLID principles (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion), I've designed a system that is modular, maintainable, and easily extensible, laying the foundation for scalability and future enhancements.

## Entity Structure:

* User, Project, and Task Entities:
  > Created these entities, which represent the core components of your project management system. Users interact with projects, and projects consist of tasks, forming a hierarchical structure.
* Entity Relationships:
  > 'Ive established mappings between entities using Hibernate annotations, ensured proper data associations and integrity between the entities.

## CRUD Operations:

* Create, Read, Update, Delete (CRUD):
  > Implemented crud operations, which allows users to manage projects and his tasks for the projects effectively. They can create new projects, view existing ones, update project details, and remove projects as needed, providing comprehensive functionality.

## Validation:

* Validation Framework:
  > Utilized a validation framework such as Spring's built-in validation capabilities ensures consistent and reliable validation across the application, enhancing robustness and reliability.

## Documentation:

> Swagger2 Integration:
* Integrated Swagger2, which enables automatic generation of comprehensive API documentation. This documentation describes available endpoints, request/response formats, and parameters, facilitating easier integration and usage by other developers.

## Testing:

* JUnit and Mockito:
  > Tested the controller endpoints using JUnit and Mockito, where JUnit is a widely-used testing framework for Java applications, while Mockito is a popular mocking framework. Together, they allow for thorough testing of controller methods and REST APIs, ensuring correct behavior and identifying potential issues early in the development cycle.

## Postman Validation:

* Functional Testing:
  > Used Postman to enables functional testing of REST APIs by sending requests and validating responses. This ensures that endpoints function correctly and meet specified requirements, enhancing system reliability and user confidence.
