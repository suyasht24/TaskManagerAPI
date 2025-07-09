# 🧠 Task Manager REST API

A simple yet scalable backend application built with **Spring Boot**, performing full CRUD operations for managing tasks. Integrated with **MySQL**, it's perfect for showcasing your Java backend skills to recruiters and companies.

---

## 🚀 Tech Stack

- **Java 17**
- **Spring Boot 2.7.5**
- **Spring Data JPA**
- **MySQL**
- **Maven**
- **Postman** (for testing)

---

## 📦 Features

- 📝 Add, update, delete, and view tasks
- 🔁 RESTful API architecture
- 🗃️ MySQL integration via Spring Data JPA
- 🧩 Clean code with layered structure (Controller, Service, Repository)
- 🛠️ Easily extendable and scalable

---

## 🔌 Getting Started

### ⚙️ Prerequisites

- Java 17+
- Maven
- MySQL Server running locally
- IDE (IntelliJ, VS Code, Eclipse)

### 🧪 Setup Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/suyash24/TaskManagerAPI.git
2. Create a MySQL database named:
   taskdb
3. Update DB credentials in:
   src/main/resources/application.properties
4. Run the application:
   mvn spring-boot:run
5. Open Postman or your browser and test:
   http://localhost:8080/api/tasks

## Folder Structure
TaskManagerAPI
├── src
│   └── main
│       ├── java
│       │   └── com.example.taskmanager
│       │       ├── controller
│       │       ├── model
│       │       ├── repository
│       │       └── service
│       └── resources
│           └── application.properties
├── pom.xml
├── .gitignore
└── README.md

## API Endpoints
| Method | URL               | Description       |
| ------ | ----------------- | ----------------- |
| GET    | `/api/tasks`      | Fetch all tasks   |
| POST   | `/api/tasks`      | Create a new task |
| PUT    | `/api/tasks/{id}` | Update task by ID |
| DELETE | `/api/tasks/{id}` | Delete task by ID |

## Screenshot
![Screenshot (174)](https://github.com/user-attachments/assets/2aeb88ef-31d4-43e4-b238-e7217e6a787d)
![Screenshot (175)](https://github.com/user-attachments/assets/cacb5e20-2d29-4c20-901b-c141b0244121)

## Author
Suyash Sunil Thamake
Aspiring Backend Engineer | AI & Data Science Student
📍 Pune | Tech Lover
📧 Connect: LinkedIn (https://www.linkedin.com/in/suyash-thamake-013950227/)
