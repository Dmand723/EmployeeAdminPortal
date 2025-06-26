# Employee Database Management System API

A RESTful API built with .NET 8 for managing employee data. This API provides endpoints to create, read, update, and delete (CRUD) employee records.

## Features

- Add new employees
- Retrieve employee details (single or all)
- Update existing employee information
- Delete employee records

## Technologies

- .NET 8
- ASP.NET Core Web API
- Entity Framework Core

## Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- SQL Server (or update connection string for your DB)

### Setup

1. **Clone the repository:**

2. **Restore dependencies:**	

3. **Apply database migrations:**

4. **Run the API:**	

5. The API will be available at `https://localhost:5001` or `http://localhost:5000`.

## API Endpoints

| Method | Endpoint                | Description                |
|--------|------------------------ |----------------------------|
| GET    | /api/employees          | Get all employees          |
| GET    | /api/employees/{id}     | Get employee by ID         |
| POST   | /api/employees          | Add a new employee         |
| PUT    | /api/employees/{id}     | Update an employee         |
| DELETE | /api/employees/{id}     | Delete an employee         |

### Example Employee Object	

```json
{
    "id": "0abe6cbe-28b9-4754-5c1e-08ddb4f0abd7",
    "name": "John Doe",
    "email": "notReal@email.com",
    "phone": null,
    "salary": 5000000
  }
  ```
## Usage

You can test the API using tools like [Postman](https://www.postman.com/) or [curl](https://curl.se/).

