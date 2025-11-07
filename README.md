# gradgateway-backend

Backend API of **GradGateway.lk** built using **.NET 8 Web API** and **MySQL**.

## Project Structure

This project follows the **Clean Architecture** pattern with the following layers:

- **GradGateway.API** – Entry point (controllers, API configuration)
- **GradGateway.Application** – Business logic and use cases
- **GradGateway.Domain** – Core entities and domain models
- **GradGateway.Infrastructure** – Database context and external service implementations

## Tech Stack

- **.NET 8**
- **C#**
- **MySQL**
- **Dapper / EF Core (based on use case)**
- **Swagger** for API documentation

## Getting Started

To run the project locally:

```bash
dotnet build
dotnet run --project GradGateway.API
