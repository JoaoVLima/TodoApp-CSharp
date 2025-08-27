# Todo App — C# (ASP.NET)
📝 A Todo app implemented in C# with ASP.NET Core, showcasing the MVC pattern, Razor Pages, and Entity Framework Core for database access. This project is part of a series where the same app is built in multiple frameworks (Spring Boot, Laravel, Rails, Scotty) to explore differences in language, architecture, and developer experience.

This is the **C# + ASP.NET Core implementation** of the [**Multi-Framework Todo App**](https://github.com/JoaoVLima/MultiFrameworkTodoApp) project.

The goal of the overall project is to implement the same simple **Todo List application** across multiple programming languages and web frameworks, in order to **compare architectures, developer experiences, and trade-offs**.

---

## 🚀 Project Overview

The Todo App is a minimal CRUD application.
Features:

* List all todos
* View a single todo
* Create a new todo
* Update an existing todo
* Delete a todo

---

## 💻 Why C# + ASP.NET Core?

ASP.NET Core is Microsoft’s modern web framework for building cross-platform, high-performance web applications. It provides:

* Strongly typed **C# language features**
* **MVC (Model-View-Controller)** architecture for clean separation of concerns
* **Entity Framework Core** for database interaction
* **Razor Pages** for rendering dynamic views
* Great tooling with **Visual Studio** and **Visual Studio Code**

Compared to the other frameworks in this series, .NET combines **enterprise-level robustness** with strong tooling and cross-platform support.

---

## 📂 Project Structure

```
dotnet-todo/
 ├── Controllers/       # TodoController (handles routes)
 ├── Models/            # Todo model (entity)
 ├── Data/              # EF Core DbContext
 ├── Views/             # Razor views for todos
 ├── Program.cs         # Entry point
 ├── appsettings.json   # Config (DB, etc.)
 └── README.md
```

---

## ⚡ Getting Started

### Prerequisites

* .NET 6 or later
* SQLite (or another database configured in `appsettings.json`)

### Run the app

```bash
# Clone the repo
git clone https://github.com/JoaoVLima/dotnet-todo.git
cd dotnet-todo

# Restore dependencies
dotnet restore

# Run the app
dotnet run
```

The app will be available at:
👉 `http://localhost:5000/todos`

---

## 🛠 API Endpoints

| Method | Endpoint      | Description       |
| ------ | ------------- | ----------------- |
| GET    | `/todos`      | List all todos    |
| GET    | `/todos/{id}` | Get a single todo |
| POST   | `/todos`      | Create a new todo |
| PUT    | `/todos/{id}` | Update a todo     |
| DELETE | `/todos/{id}` | Delete a todo     |

---

## 🔑 Reflection Points (.NET)

* ✅ Excellent tooling (Visual Studio, VS Code)
* ✅ Strongly typed and enterprise-ready
* ⚠️ Steeper learning curve for newcomers
* ⚡ Ideal for **large organizations, APIs, and enterprise apps**

---

Do you want me to also prepare the **README drafts for Laravel, Rails, and Scotty** now, so all repos have a consistent style from the start?
