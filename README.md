# 📚 LibraryApp

**LibraryApp** is a console-based CRUD application for managing books in a library.  
It follows the MVC (Model–View–Controller) architecture and connects to a MySQL database using JDBC.  
This project is part of our learning journey in Java programming, software architecture, and database integration.

[Library.png](https://postimg.cc/jw2Knb9T)
[Library-Flow-Chart-1.png](https://postimg.cc/68xvrjtg)

---

## 🎯 Learning Objective

This project was created with the purpose of practicing and strengthening the following skills:

- Java fundamentals
- Object-Oriented Programming (OOP)
- MVC architecture
- JDBC and MySQL integration
- Test-driven development using JUnit and Mockito
- Clean code organization in multi-package projects

---

## 🧱 Project Structure

```
📦library-app
┣ 📂config
┃ ┗ 📜DBManager.java
┣ 📂controller
┃ ┗ 📜BookController.java
┣ 📂model
┃ ┗ 📜Book.java
┣ 📂repository
┃ ┗ 📜BookRepository.java
┣ 📂view
┃ ┗ 📜BookView.java
┣ 📂main
┃ ┗ 📜Main.java
┗ 📂test
    ┗ 📂controller
        ┗ 📜BookControllerTest.java
```
---

## 🛠️ Technologies Used

- Java 21
- MySQL
- JDBC
- Maven
- JUnit 5
- Mockito
- Git/GitHub
- IntelliJ IDEA

---

## 🚀 How to Run the Project

1. **Clone the repository**
   git clone https://github.com/FemCodersLibrary/library.git
2. Set up the MySQL database
3. Create a database named library
4. Create the books table (you can request a SQL script if needed)
5. Update DB credentials
6. Go to config/DBManager.java and make sure the user, password, and database name match your setup
7. Compile and run
8. mvn clean compile

## 🖼️ VIEW 

![img.png](img.png)

## 🧪 TESTING

mvn test
The controller is tested using Mockito, which allows us to verify the interaction with the repository without connecting to a real database.
This ensures fast and isolated unit tests focused on the controller logic.

## 👩‍💻 Authors

- <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20"> [@may-leth](https://github.com/may-leth)  
- <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20"> [@thaisrqueiroz](https://github.com/thaisrqueiroz)  
- <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20"> [@marykenny123](https://github.com/marykenny123)  
- <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20"> [@Alexandracoder](https://github.com/Alexandracoder)  













