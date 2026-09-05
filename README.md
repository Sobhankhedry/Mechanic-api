# 🔧 Mechanic API

A RESTful backend API for a **vehicle mechanic and repair shop management system**, built with **ASP.NET Core 8**.

The project is designed as a backend foundation for managing mechanics, vehicles, repair services, and workshop-related operations through a RESTful API.

## 🚀 Overview

**Mechanic API** is a backend project focused on building a scalable and maintainable API for an automotive repair management system.

The project is built with modern .NET technologies and follows the standard ASP.NET Core Web API approach, making it suitable for integration with web, mobile, or other client applications.

## ✨ Features

* RESTful API architecture
* ASP.NET Core 8 Web API
* Swagger / OpenAPI documentation
* HTTPS support
* Controller-based API structure
* Development and production configuration support
* Nullable reference types enabled
* Ready for database and business-logic expansion

## 🛠️ Tech Stack

| Technology               | Purpose                     |
| ------------------------ | --------------------------- |
| **C#**                   | Programming language        |
| **.NET 8**               | Backend framework           |
| **ASP.NET Core Web API** | REST API                    |
| **Swagger / OpenAPI**    | API documentation & testing |
| **Swashbuckle**          | Swagger integration         |

## 📁 Project Structure

```text
Mechanic-api/
│
├── MechanicAPI/
│   ├── Properties/
│   ├── Program.cs
│   ├── MechanicAPI.csproj
│   ├── MechanicAPI.http
│   ├── appsettings.json
│   └── appsettings.Development.json
│
├── MechanicAPI.sln
├── .gitignore
├── LICENSE
└── README.md
```

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

* [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
* Git

### Clone the repository

```bash
git clone https://github.com/Sobhankhedry/Mechanic-api.git
cd Mechanic-api
```

### Restore dependencies

```bash
dotnet restore
```

### Build the project

```bash
dotnet build
```

### Run the API

```bash
dotnet run --project MechanicAPI
```

Once the application is running, the API will be available locally according to the URL shown in the terminal.

## 📖 API Documentation

When running in the **Development** environment, Swagger UI is enabled.

Open:

```text
/swagger
```

Swagger provides an interactive interface for exploring and testing the available API endpoints.

## 🧪 Testing the API

The project also includes an HTTP request file:

```text
MechanicAPI/MechanicAPI.http
```

You can use it with IDEs such as **Visual Studio** or **JetBrains Rider** to send HTTP requests directly to the API.

## 🔐 Configuration

Application configuration is handled through ASP.NET Core configuration files.

Development-specific configuration can be placed in:

```text
MechanicAPI/appsettings.Development.json
```

Avoid committing sensitive information such as:

* Database credentials
* API keys
* Connection strings containing passwords
* Authentication secrets

Use environment variables or user secrets for sensitive configuration.

## 🗺️ Roadmap

The project is intended to evolve into a complete mechanic/workshop management backend.

Planned areas include:

* [ ] Vehicle management
* [ ] Customer management
* [ ] Mechanic management
* [ ] Repair/service management
* [ ] Service history
* [ ] Appointment scheduling
* [ ] Spare parts management
* [ ] Inventory management
* [ ] Billing and invoices
* [ ] Authentication & authorization
* [ ] Role-based access control
* [ ] Database integration
* [ ] Validation & global error handling
* [ ] Unit & integration testing
* [ ] Docker support
* [ ] CI/CD pipeline

## 🎯 Project Goals

The main goals of this project are:

1. Build a real-world RESTful backend using ASP.NET Core.
2. Practice clean API design and backend architecture.
3. Implement common business workflows found in automotive repair systems.
4. Improve maintainability, scalability, and testability.
5. Provide a backend that can be consumed by web and mobile clients.

## 📌 Project Status

> 🚧 **Work in Progress**

The project is currently under development. New features, database integration, business logic, authentication, testing, and deployment improvements will be added over time.

## 📄 License

This project is licensed under the **MIT License**.

---

### Author

**Sobhan Khedry**

GitHub: [@Sobhankhedry](https://github.com/Sobhankhedry)
