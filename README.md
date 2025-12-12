## Bookstore Management System

# Project Overview  
This application provides basic Create, Read, Update, Delete (CRUD) operations for a bookstore:

**Add new books**

**List all books**

**Update book details**

**Delete books**

The UI is built with plain HTML/CSS and Bootstrap components; Spring Boot exposes REST endpoints; MySQL stores the data.

# Features Implemented
- ✅ Add a book with title, author, price.
- ✅ View all books. 
- ✅ Edit book details
- ✅ Delete a book


# Tech Stack

# Frontend:
HTML, CSS, Bootstrap (v4 or v5)

# Backend: 
Java (JDK 11+), Spring Boot (Spring Web, Spring Data JPA)

# Database: 
MySQL (or compatible, e.g., MariaDB)

# Build tool: 
Maven (pom.xml) — or Gradle if you prefer


# Prerequisites
- Java JDK 11+ installed and JAVA_HOME set

- Maven (or Gradle) installed

- MySQL server running

- Git (optional)
  
# Quick Start (local development)

1. Clone repository
```powershell
git clone (https://github.com/yamini-kolli/Bookstore_Management_System.git)
cd BookStore
```
2. Install Java & Maven
- Check versions:
```powershell
java -version
mvn -version
```

3. Set Up MySQL Database
- Start MySQL server
- Create a database:

```powershell
CREATE DATABASE book;
# (Optional) Verify using:

# SHOW DATABASES;
```

4. Configure Spring Boot

- Update src/main/resources/application.properties with your database credentials:
```powershell
spring.datasource.url=jdbc:mysql://localhost:3306/bookstore?useSSL=false&serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
server.port=1001
```


5. Install Dependencies & Build

Using Maven:
```powershell
mvn clean install
```

6. Run the Application
```powershell
Start the server:

mvn spring-boot:run
```

Or run the generated JAR:
```powershell
java -jar target/bookstore-0.0.1-SNAPSHOT.jar
```

The backend will run at:
```powershell
http://localhost:1001/
```
Open index.html in a browser, or if served by Spring Boot:
```powershell
http://localhost:1001/
```

Screenshots

  ## Screenshots

### Home Page  
![Home Page](https://github.com/yamini-kolli/Bookstore_Management_System/blob/main/Screenshot%202025-12-12%20164035.png)

### NewBookRegister Page  
![AddNewBook Page](https://github.com/yamini-kolli/Bookstore_Management_System/blob/main/Screenshot%202025-12-12%20164045.png)

### Update Book Details
![UpdateBookDetails Page](https://github.com/yamini-kolli/Bookstore_Management_System/blob/main/Screenshot%202025-12-12%20164500.png)

### BookList page
  ![BookList Page](https://github.com/yamini-kolli/Bookstore_Management_System/blob/main/Screenshot%202025-12-12%20164513.png)
  

  ![Mylist Page](https://github.com/yamini-kolli/Bookstore_Management_System/blob/main/Screenshot%202025-12-12%20164531.png)

### Database 
![Book database](https://github.com/yamini-kolli/Bookstore_Management_System/blob/main/Screenshot%202025-12-12%20164716.png)


![My Book List database ](https://github.com/yamini-kolli/Bookstore_Management_System/blob/main/Screenshot%202025-12-12%20164731.png)



