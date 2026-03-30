# 🚌 Public Transport API

## 📖 Overview

This project is a RESTful API built with .NET 8 using the Minimal API approach.
It simulates a public transport system, allowing the management of bus data through standard CRUD operations. The focus is on clean endpoint design and practical use of Entity Framework Core.

---

## 🚀 Features

- Create, read, update, and delete bus records  
- RESTful endpoints following best practices  
- In-memory database for development and testing  
- Swagger integration for API testing  

---

## 🛠️ Tech Stack

- .NET 8  
- ASP.NET Core Minimal API  
- Entity Framework Core  
- In-Memory Database  

---

## ⚙️ Endpoints

| Method | Route            | Description           |
|--------|------------------|-----------------------|
| GET    | /api/Onibus      | Get all buses         |
| GET    | /api/Onibus/{id} | Get bus by ID         |
| POST   | /api/Onibus      | Create new bus        |
| PUT    | /api/Onibus/{id} | Update bus            |
| DELETE | /api/Onibus/{id} | Delete bus            |

---

## 🧠 Technical Highlights

- Implementation using **Minimal API pattern**  
- Use of **Entity Framework Core** for data handling  
- Structured endpoints with **typed results (Results<>)**  
- Basic input validation in POST endpoint  
- Clean and simple architecture  
