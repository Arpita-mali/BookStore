
# 📚 Book Store Application

A simple **Book Store Management System** built using **Spring Boot**, **Thymeleaf**, and **Spring Data JPA**.
This project allows users to add, view, edit, and delete books, as well as maintain their personal book list.

---

## 🚀 Features

* 📖 View all available books
* ➕ Add new books to the store
* ✏️ Edit or update book details
* ❌ Delete books from the store
* ❤️ Add books to “My Book List”
* 🏠 User-friendly web interface using Thymeleaf

---

## 🛠️ Technologies Used

| Layer       | Technology              |
| ----------- | ----------------------- |
| Framework   | Spring Boot             |
| View Layer  | Thymeleaf, HTML, CSS    |
| Persistence | Spring Data JPA         |
| Database    | MySQL                   |
| Build Tool  | Maven                   |
| IDE         | Eclipse / IntelliJ IDEA |

---

## ⚙️ Project Setup and Installation

### 1️⃣ Prerequisites

* Java 17 or above
* Maven 3+
* MySQL Server
* Eclipse or IntelliJ IDEA

---

## 🌐 Access the Application

After starting the project:

* Open your browser and go to 👉 **[http://localhost:8080/](http://localhost:8080/)**
* Home Page → `/home`
* View All Books → `/available_books`
* Add Book → `/book_register`
* My Books → `/my_books`

---

## 📁 Project Structure

```
bookStore/
 ├── src/
 │   ├── main/
 │   │   ├── java/com/bookStore/
 │   │   │   ├── controller/        # Book and MyBookList controllers
 │   │   │   ├── entity/            # JPA Entities (Book, MyBookList)
 │   │   │   ├── repository/        # JPA Repositories
 │   │   │   ├── service/           # Service Layer for business logic
 │   │   │   └── BookStoreApplication.java
 │   │   └── resources/
 │   │       ├── templates/         # Thymeleaf HTML files
 │   │       │   ├── home.html
 │   │       │   ├── bookList.html
 │   │       │   ├── bookRegister.html
 │   │       │   ├── bookEdit.html
 │   │       │   └── myBooks.html
 │   │       ├── static/            # Images and static assets
 │   │       └── application.properties
 │   └── test/
 │       └── java/com/bookStore/
 │           └── BookStoreApplicationTests.java
 ├── pom.xml                        # Maven dependencies
 ├── mvnw / mvnw.cmd                # Maven wrapper scripts
 └── README.md
```

---

## 🧩 Key Classes Overview

| Package      | Description                                       |
| ------------ | ------------------------------------------------- |
| `controller` | Handles web requests and maps to templates        |
| `entity`     | Defines JPA entity classes (`Book`, `MyBookList`) |
| `repository` | Interfaces for database operations                |
| `service`    | Contains business logic for managing books        |
| `templates`  | HTML pages rendered using Thymeleaf               |

---

## 🧪 Example Pages

| Page         | Path               | Description               |
| ------------ | ------------------ | ------------------------- |
| Home         | `/home`            | Landing page of the app   |
| Add Book     | `/book_register`   | Form to add new book      |
| View Books   | `/available_books` | Shows list of books       |
| Edit Book    | `/editBook/{id}`   | Edit existing book        |
| My Book List | `/my_books`        | Personal saved books list |

---

## 💡 Future Enhancements

* Add login & authentication using Spring Security
* Implement RESTful APIs for external access
* Add search and sorting functionality
* Integrate with online payment gateway

---
💬 Author

Developed by: Arpita Bajrang Mali
Email: maliarpita627@gmail.com

GitHub: Arpita-mali
