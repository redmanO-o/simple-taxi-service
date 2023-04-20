#  Simple 🚕taxi-service🚕


######  🔗 _project navigation_
- [Project description](#-project-description)
- [Features](#-features)
- [How to run](#-how-to-run)
- [Project structure](#-project-structure)
- [Used technologies](#-used-technologies)
- [Link](#-author)


### 📚 Project description
This web application is an immitation of an simple taxi service
with authentication, registration, and CRUD operations.
It is developed using SOLID
principles and the Dependency Injection pattern.
The main features include authentication,
CRUD operations for cars and drivers,
logical layer separation, and authentication filtering.
The application is user-friendly,
adheres to programming standards,
and provides a convenient user interface for users.


### 💎 Features
- Registration and login
- Create new models
- Display all models
- Add models
- Display all info by current user
- Soft delete models


### ▶️ How to run
1) ✅[Clone](https://github.com/redmanO-o/simple-taxi-service/fork) the project from GitHub
2) ✅Use [init_db.sql](src/main/resources/init_db.sql) 
to create a schema and tables
3) ✅Configure [ConnectionUtil](src/main/java/taxi/util/ConnectionUtil.java) 
 with your own URL, username, password and JDBC driver
2) ✅Configure Tomcat server (it is recommended to use version 
 [9.0.73](https://tomcat.apache.org/download-90.cgi#9.0.73) ❗️)

🚀 Run and enjoy the program


### 📂 Project structure
##### _The project has N-tier architecture_ 
  + [**Dao**](src/main/java/taxi/dao) _(access to DB)_
  + [**Service**](src/main/java/taxi/service) _(business logic)_
  + [**Controller**](src/main/java/taxi/controller) _(client-server communication)_


### ⚙️ Used technologies
| Technology | Version |
|------------|:-------:|
| JDK        |   17    |
| Maven      |  3.8.7  |
| TomCat     | 9.0.73  |
| MySQL      | 8.0.32  |
| Servlet    |  4.0.1  |
| JSTL       |   1.2   |


### 📌 Author  
#### Oleksandr Krasnov <br/>[LinkedIn](https://www.linkedin.com/in/oleksandr-krasnov-106415234)
