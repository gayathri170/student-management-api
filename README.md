# 🎓 Student Management API

A RESTful backend application built using Spring Boot to manage student data efficiently. This project demonstrates CRUD operations, layered architecture, and exception handling in a real-world backend system.

---

## 🚀 Features

* Add a new student
* View all students
* Get student by ID
* Update student details
* Delete student
* Global exception handling

---

## 🛠️ Tech Stack

* Java 17+
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL / H2 Database
* Maven

---

## 📁 Project Structure

* **Controller** → Handles API requests
* **Service** → Business logic layer
* **Repository** → Database interaction
* **Entity** → Database model
* **DTO** → Data transfer objects
* **Exception** → Centralized error handling

---

## 📌 API Endpoints

| Method | Endpoint       | Description            |
| ------ | -------------- | ---------------------- |
| POST   | /students      | Create a new student   |
| GET    | /students      | Get all students       |
| GET    | /students/{id} | Get student by ID      |
| PUT    | /students/{id} | Update student details |
| DELETE | /students/{id} | Delete student         |

---

## ⚙️ How to Run the Project

1. Clone the repository
2. Open the project in IntelliJ IDEA / Eclipse
3. Configure database in `application.properties`
4. Run `DemoApplication.java`
5. Use Postman or browser to test APIs

---

## 📷 Sample Request JSON

```json
{
  "name": "Gayathri",
  "email": "gayathri@example.com",
  "course": "ECE"
}
```

---

## 💡 Future Enhancements

* Add Authentication & Authorization (JWT)
* Implement Pagination & Sorting
* Deploy the application on cloud (AWS / Render)

---

## 👩‍💻 Author

**Gayathri Ramya**
