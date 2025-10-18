# 🚗 Spare Parts Online Store - ASP.NET Core

A modern, scalable e-commerce platform for automotive spare parts built with **.NET 8** and **Clean Architecture** principles. This project demonstrates advanced .NET development skills, enterprise-level design patterns, and best practices.

## 🎯 Project Overview

This application manages an online store for automotive spare parts, featuring car manufacturers, categories, suppliers, and product management with comprehensive CRUD operations and relationships.

## 🛠️ Tech Stack & Architecture

### **Backend Framework**
- **.NET 8** - Latest LTS version
- **ASP.NET Core Web API** - RESTful API design
- **C# 12** - Modern language features

### **Architecture Pattern**
- **Clean Architecture** - Separation of concerns
- **CQRS (Command Query Responsibility Segregation)** - with MediatR
- **Repository Pattern** - Data access abstraction
- **Dependency Injection** - Built-in DI container

### **Key Libraries & NuGet Packages**

| Library | Purpose |
|---------|---------|
| **MediatR** | CQRS implementation and request/response handling |
| **Entity Framework Core** | ORM and database operations |
| **FluentValidation** | Input validation and business rules |
| **Swagger/OpenAPI** | API documentation and testing |
| **SQL Server** | Database provider |

### **Project Structure**
```
📁 Spareparts.API          # Presentation Layer (Controllers, Middleware)
📁 Spareparts.Application  # Business Logic (Commands, Queries, DTOs)
📁 Spareparts.Domain       # Core Entities and Interfaces
📁 Spareparts.Infrastructure # Data Access (EF Core, Repositories)
```

## 🔧 Key Features Implemented

- ✅ **Clean Architecture** with proper separation of layers
- ✅ **CQRS Pattern** using MediatR for command/query separation  
- ✅ **Repository Pattern** for data access abstraction
- ✅ **Entity Framework Core** with Code-First migrations
- ✅ **FluentValidation** for robust input validation
- ✅ **Swagger Documentation** for API testing
- ✅ **Exception Handling Middleware** for centralized error management
- ✅ **Dependency Injection** throughout the application
- ✅ **Database Seeding** for initial data setup

## 🚀 Skills Demonstrated

This project showcases proficiency in:

- **Modern .NET Development** (NET 8, C# 12)
- **Enterprise Architecture Patterns** (Clean Architecture, CQRS)
- **Database Design** (Entity relationships, migrations)
- **API Development** (RESTful services, OpenAPI)
- **Code Quality** (Validation, error handling, separation of concerns)
- **Dependency Management** (NuGet packages, project references)

## 📋 Domain Models

- **Cars** - Vehicle information with manufacturer relationships
- **Manufacturers** - Car manufacturers (Toyota, Ford, etc.)
- **Categories** - Spare part categories (Engine, Brake, etc.)
- **Suppliers** - Parts suppliers and vendors
- **ProductDetails** - Spare parts catalog with pricing
- **Relationships** - Many-to-many between cars/products and suppliers/products

---

*This project demonstrates modern .NET development practices and enterprise-level application architecture suitable for production environments.*