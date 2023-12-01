# Udemy-Microservices-Project
The following tools were used in the project:
- ASP .NET Core 7.0
- Microservices Architecture
- Databases:
  - MSSQL
  - PostgreSQL
  - MongoDB
  - Redis
- IdentityServer
- AutoMapper
- Dapper
- Domain Driven Design
- CQRS
- RabbitMQ with MassTransit
- Docker and Portainer

The microservice project structure we built in the "Microservices with .Net 7.0" course

- Catalog Microservice
  - Responsible for storing and presenting information about our courses.
  - Database: MongoDB
  - Relationships: One-To-Many/One-To-One

- Basket Microservice
  - Responsible for basket-related operations.
  - Database: RedisDB

- Discount Microservice
  - Responsible for managing user-specific discount coupons.
  - Database: PostgreSQL

- Order Microservice
  - Responsible for order-related operations. Developed using the Domain Driven Design approach and implementing the CQRS design pattern using the MediatR library.
  - Database: SQL Server

- FakePayment Microservice
  - Responsible for payment-related operations.

- IdentityServer Microservice
  - Responsible for storing user data, generating tokens and refresh tokens.
  - Database: SQL Server

- PhotoStock Microservice
  - Responsible for storing and presenting course photos.
  - API Gateway
  - Using the Ocelot library.

- Message Broker
  - Using RabbitMQ as the message queue system.
  - Communication with RabbitMQ is facilitated using the MassTransit library.

- Identity Server
  - Responsible for token/refresh token generation, protecting microservices with access tokens, and building a structure compliant with OAuth 2.0/OpenID Connect protocols.

- Asp.Net Core MVC Microservice
  - Responsible for displaying data received from microservices to users and interacting with users.

![microservice_mimari](https://user-images.githubusercontent.com/46678087/114802958-42c15d80-9da7-11eb-8391-ba0abf87a1b1.png)
